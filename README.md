# function calculateTime(t1, t2, t3) {
    const v1 = 1 / t1;
    const v2 = 1 / t2;
    const v3 = 1 / t3;
    const V_total = v1 + v2 + v3;
    const T_total = 1 / V_total;
    return T_total.toFixed(2);
}

const t1 = 3;
const t2 = 3;
const t3 = 3;
const result = calculateTime(t1, t2, t3);
console.log(`Час, необхідний для з'їдання пирога: ${result} годин`);
