// PD4: Kintamieji
let petName;
let petAge;
petName = 'Buddy';
petAge = 3;
console.log('Pet name:', petName);
console.log('Pet age:', petAge);
petName = 'Max';
petAge = 5;
const buildingAddress = '123 Main St';
console.log('Building address:', buildingAddress);

// PD5: Duomenų tipai
const number = 42;
console.log('Number:', number);
const bigInt = 1234567890123456789012345678901234567890n;
console.log('BigInt:', bigInt);
const text = 'Hello, world!';
console.log('String:', text);
const bool = true;
console.log('Boolean:', bool);
let undef;
console.log('Undefined:', undef);
const nul = null;
console.log('Null:', nul);
const obj = { key: 'value' };
console.log('Object:', obj);
console.log('Type of number:', typeof number);
console.log('Type of text:', typeof text);
console.log('Type of bool:', typeof bool);

// PD6: Duomenų tipų konvertavimas
let funnyNumber = 12345; // Convert to String
console.log(typeof funnyNumber); // Rezultatas: number
funnyNumber = funnyNumber.toString();
console.log(typeof funnyNumber); // Rezultatas: string

let funnyString = '12345'; // Convert to Number
console.log(typeof funnyString); // Rezultatas: string
funnyString = parseInt(funnyString);
console.log(typeof funnyString); // Rezultatas: number

let funnyTrue = '1'; // Convert to Boolean
console.log(typeof funnyTrue); // Rezultatas: string
funnyTrue = Boolean(funnyTrue);
console.log(typeof funnyTrue); // Rezultatas: boolean

let funnyFalse = '0'; // Convert to Boolean
console.log(typeof funnyFalse); // Rezultatas: string
funnyFalse = Boolean(funnyFalse);
console.log(typeof funnyFalse); // Rezultatas: boolean

let isTrue = false; // Convert to String
console.log(typeof isTrue); // Rezultatas: boolean
isTrue = isTrue.toString();
console.log(typeof isTrue); // Rezultatas: string

let isFalse = true; // Convert to Number
console.log(typeof isFalse); // Rezultatas: boolean
isFalse = Number(isFalse);
console.log(typeof isFalse); // Rezultatas: number

let funnyText = 'JavaScript is dynamic programming language.'; // Convert to Number
console.log(typeof funnyText); // Rezultatas: string
funnyText = parseInt(funnyText);
console.log(typeof funnyText); // Rezultatas: number (jei nėra skaičiaus, gražins NaN)

let funnyNull = null; // Convert to String
console.log(typeof funnyNull); // Rezultatas: object
funnyNull = String(funnyNull);
console.log(typeof funnyNull); // Rezultatas: string

let funnyUndefined = undefined; // Convert to String
console.log(typeof funnyUndefined); // Rezultatas: undefined
funnyUndefined = String(funnyUndefined);
console.log(typeof funnyUndefined); // Rezultatas: string

let isTrueStr = true; // Convert to String
console.log(typeof isTrueStr); // Rezultatas: boolean
isTrueStr = isTrueStr.toString();
console.log(typeof isTrueStr); // Rezultatas: string

let isFalseStr = false; // Convert to String
console.log(typeof isFalseStr); // Rezultatas: boolean
isFalseStr = isFalseStr.toString();
console.log(typeof isFalseStr); // Rezultatas: string

let booleanString = 'true'; // Convert to Number
console.log(typeof booleanString); // Rezultatas: string
booleanString = parseInt(booleanString);
console.log(typeof booleanString); // Rezultatas: number

let otherBooleanString = 'false'; // Convert to Boolean
console.log(typeof otherBooleanString); // Rezultatas: string
otherBooleanString = Boolean(otherBooleanString);
console.log(typeof otherBooleanString); // Rezultatas: boolean

// PD7: Aritmetiniai operatoriai
let numberOne = 10;
let numberTwo = 20;

console.log(numberOne + numberTwo); // Rezultatas: 30
console.log(numberOne - numberTwo); // Rezultatas: -10
console.log(numberOne * numberTwo); // Rezultatas: 200
console.log(numberOne / numberTwo); // Rezultatas: 0.5
console.log(numberOne % numberTwo); // Rezultatas: 10 (liekana po dalybos)

PD8
let numberX = 10;
let numberY = 20;
let result = numberX + numberY;
console.log(result); // 30
result += 10;
console.log(result); // 40
result -= 10;
console.log(result); // 30
result *= 10;
console.log(result); // 300
result /= 10;
console.log(result); // 30
result %= 10;
console.log(result); // 0
result **= 10;
console.log(result); // 0
result += 10 + numberY;
console.log(result); // 30
result *= numberX - numberY;
console.log(result); // -600

PD9
let numberX = 10;
let numberY = '20';

console.log(numberX == numberY); // true (verčiama į skaičių, lygu 10)
console.log(numberX === numberY); // false (skirtingi tipai, skaičius ir string'as)
console.log(numberX != numberY); // false (verčiama į skaičių, lygu 10)
console.log(numberX !== numberY); // true (skirtingi tipai, skaičius ir string'as)
console.log(numberX > numberY); // false (verčiama į skaičių, 10 nėra didesnis už 20)
console.log(numberX < numberY); // true (verčiama į skaičių, 10 yra mažesnis už 20)
console.log(numberX >= numberY); // false (verčiama į skaičių, 10 nėra didesnis arba lygus 20)
console.log(numberX <= numberY); // true (verčiama į skaičių, 10 yra mažesnis arba lygus 20)

// PD10: Loginiai operatoriai
let isTrue = true;
let isFalse = false;

console.log(isTrue && isTrue); // true
console.log(isTrue && isFalse); // false
console.log(isFalse && isFalse); // false
console.log(isTrue || isTrue); // true
console.log(isTrue || isFalse); // true
console.log(isFalse || isFalse); // false
console.log(!isTrue); // false
console.log(!isFalse); // true
console.log(!isFalse && isTrue); // true
console.log(!isFalse && !isTrue); // false
console.log(!isFalse || isTrue); // true

// PD11: Bitiniai operatoriai
let bitNumberOne = 10;
let bitNumberTwo = 20;

console.log(bitNumberOne & bitNumberTwo); // 0
console.log(bitNumberOne | bitNumberTwo); // 30
console.log(~bitNumberTwo); // -21
console.log(bitNumberOne ^ bitNumberTwo); // 30
console.log(bitNumberOne << 1); // 20
console.log(bitNumberOne << 5); // 320
console.log(bitNumberOne >> 1); // 5

PD12
// 1. Užduotis: Suskaičiuoti paskaitų skaičių per savaitę ir kiek tai sudarys minučių.

function skaiciuotiLaika() {
    // Duomenys
    const paskaituSkaicius = {
        pirmadienis: 5,
        antradienis: 6,
        treciadienis: 4,
        ketvirtadienis: 5,
        penktadienis: 4
    };
    const paskaitosLaikasMinutemis = 45;

    // Skaičiavimas
    let visoPaskaitu = 0;
    for (let diena in paskaituSkaicius) {
        visoPaskaitu += paskaituSkaicius[diena];
    }
    const visoLaikoMinutemis = visoPaskaitu * paskaitosLaikasMinutemis;

    // Rezultato išvedimas
    console.log(`Paskaitų skaičius per savaitę - ${visoPaskaitu}. Tai sudaro ${visoLaikoMinutemis} minučių.`);
}

// Paleidimas
skaiciuotiLaika();

// 2. Užduotis: Apskaičiuoti pilnas ir likusias dėžutes su puodeliais.

function apskaiciuotiDezes() {
    // Duomenys
    const puodeliuSkaicius = 7;
    const puodeliuDezeje = 3;

    // Skaičiavimas
    const pilnuDeziu = Math.floor(puodeliuSkaicius / puodeliuDezeje);
    const likusiosPuodeliai = puodeliuSkaicius % puodeliuDezeje;

    // Rezultato išvedimas
    console.log(`Pilnų dėžučių skaičius: ${pilnuDeziu}. Nesupakuotų puodelių skaičius: ${likusiosPuodeliai}.`);
}

// Paleidimas
apskaiciuotiDezes();

// 3. Užduotis: Apskaičiuoti plytų kiekį ir jų kainą.

function apskaiciuotiPlytas() {
    // Duomenys
    const sienosIlgis = 4; // metrai
    const sienosAukstis = 3; // metrai
    const plytosIlgis = 20; // centimetrai
    const plytosAukstis = 10; // centimetrai
    const plytosKaina = 0.5; // Eur

    // Skaičiavimas
    const plytuSkaicius = Math.ceil((sienosIlgis * 100 / plytosIlgis) * (sienosAukstis * 100 / plytosAukstis));
    const plytuKaina = (plytuSkaicius * plytosKaina).toFixed(2);

    // Rezultato išvedimas
    console.log(`Plytų kiekis ${plytuSkaicius}. Plytos kainuos ${plytuKaina} Eur.`);
}

// Paleidimas
apskaiciuotiPlytas();

// 4. Užduotis: Apskaičiuoti automobilio pravažiavimo laiką tuneliu.

function automobilioLaikas() {
    // Duomenys
    const tunelioIlgis = 264; // metrai
    const automobilioGreitisKmh = 60; // km/h

    // Skaičiavimas
    const laikasSekundemis = (tunelioIlgis / (automobilioGreitisKmh * 1000 / 3600)).toFixed(2);

    // Rezultato išvedimas
    console.log(`Automobilis tunelį pravažiuos per ${laikasSekundemis} s`);
}

// Paleidimas
automobilioLaikas();

// 5. Užduotis: Apskaičiuoti žuvų skaičių po n dienų.

function zuvuSkaiciusPoDienas() {
    // Duomenys
    const pradinisZuvuSkaicius = 5;
    const zuvuPridedamaPerDiena = 3;
    const dienuSkaicius = 3;

    // Skaičiavimas
    const galutinisZuvuSkaicius = pradinisZuvuSkaicius + (zuvuPridedamaPerDiena * dienuSkaicius);

    // Rezultato išvedimas
    console.log(`Po ${dienuSkaicius} dienų akvariume gyvens ${galutinisZuvuSkaicius} žuvų.`);
}

// Paleidimas
zuvuSkaiciusPoDienas();

// 6. Užduotis: Apskaičiuoti vidutinį eglutės aukštį.

function vidutinisEglutesAukstis() {
    // Duomenys
    const egluciuAukstis = [167, 134, 145, 156, 155, 176];
    const egluciuKiekis = egluciuAukstis.length;

    // Skaičiavimas
    let suma = 0;
    for (let aukstis of egluciuAukstis) {
        suma += aukstis;
    }
    const vidutinisAukstis = (suma / egluciuKiekis).toFixed(1);

    // Rezultato išvedimas
    console.log(`Eglutės aukščio vidurkis: ${vidutinisAukstis} cm`);
}

// Paleidimas
vidutinisEglutesAukstis();

PD13
let x = 5;
let y = 10;

if (x > y) {
    console.log("Didesnis skaičius yra 'x'");
} else {
    console.log("Didesnis skaičius yra 'y'");
}

let x = 5;
let y = 10;
let z = -12;

let sandauga = x * y * z;

if (sandauga < 0) {
    console.log("Sandaugos ženklas yra '-'");
} else {
    console.log("Sandaugos ženklas yra '+'");
}
let x = 2;
let y = -2;
let z = 4;

let skaiciai = [x, y, z];
skaiciai.sort((a, b) => a - b);

console.log("Rezultatas:", skaiciai.join(", "));
let a = 6;
let b = -6;
let c = 13;

let diskriminantas = b ** 2 - 4 * a * c;

if (diskriminantas > 0) {
    console.log("Lygtis turi du skirtingus sprendinius.");
} else if (diskriminantas === 0) {
    console.log("Lygtis turi vieną sprendinį.");
} else {
    console.log("Lygtis neturi realiųjų skaičių sprendinių aibėje.");
}
