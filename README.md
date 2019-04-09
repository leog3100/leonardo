# leonardo

function somar(primeiro, segundo){
    return primeiro + segundo;
}

function subtrair(primeiro, segundo){
    return primeiro - segundo;
}

function multiplicar(primeiro, segundo){
    return primeiro * segundo;
}

function dividir(primeiro, segundo){
    return segundo === 0 
    ? alert('Não permitido divisao por zero')
    : primeiro / segundo;
}

console.log(somar(1, 2));
console.log(subtrair(1, 2));
console.log(multiplicar(1, 2));
console.log(dividir(1, 2));

const animais = ['Cachorro', 'Gato', 'Jabuti', 'Papagaio', 'Tigre', 'Coruja'];
console.log(animais.sort());
const addHappySufix = animais.map(function(animal){
    return animal + 'feliz';
})
console.log(addHappySufix);



const numbers = [314,100,3,2,250,9,1000];
function insertSort(numeroAtual, proximoNumero){
    return numeroAtual - proximoNumero;
}
console.log(numbers.sort(function(numeroAtual, proximoNumero) {
    return insertSort(numeroAtual, proximoNumero);
}));

const doubleOfNumbers = numbers.map(function(number){
    return number * 2;
});
console.log(doubleOfNumbers);

const higherOrEqualThanOneHundred = numbers.filter(function(number){
    return number >= 100;
})

console.log(numbers, higherOrEqualThanOneHundred);


const numbers2 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 0];

    function isEven(number){
    return number % 2 === 0;
}
    function isOdd(number){
        return number % 2 !=0
    }
        const evenNumbers = numbers2.filter(isEven);
        const oddNumbers = numbers2.filter(isOdd)
   
    console.log(numbers2, evenNumbers);
