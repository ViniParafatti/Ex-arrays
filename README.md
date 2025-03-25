# Ex-arrays

// 1
function concatenarArrays(array1, array2) {
    return array1.concat(array2);
}

// 2
const numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
const parteNumeros = numeros.slice(3, 8); 
console.log(parteNumeros); 

// 3
const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi'];
frutas.splice(2, 2, 'Kiwi', 'Pêssego'); 
console.log(frutas); 

// 4
const menuPrincipal = ['entrada', 'prato principal', 'bebida'];
const menuDeSobremesas = ['sobremesa 1', 'sobremesa 2'];
const menuCompleto = menuPrincipal.concat(menuDeSobremesas);
console.log(menuCompleto); 
