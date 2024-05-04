let nome = "Polliana"
console.log(nome.toUpper())
console.log(nome.toLower())
console.log(nome[0])

for(let v = 0; v < 10; v++){
    console.log(v)
}
let m = parseInt(prompt('Quantas medias você deseja colocar? '))
let s = 0
for(let t = 0; t <= m; t++){
    console.log(t)
    s += t 
    console.log(`Soma = ${s}|Variavel =${t}|${t+s}`)
}

let n = parseInt(prompt('Qual número deseja ver a tabuada? '))
 for(let x = 0 ; x <= 10 ; x++){
     console.log(`${n}X${x}=${n*x}`)
 }
 
 // Faça um programa qu leia e valide as seguintes informações: Nome (maior que 3 caracteres), Idade (entre 0 e 150), Salário (maior que 0), Sexo ( feminino, masculino) e Estado civil( solteiro, casado, viúo ou divorciado)
 
 let n = prompt('Digite seu nome: ')
 let i = parseInt(prompt('Digite sua idade: '))
 let sa = parseFloat(prompt('Digite seu salário: '))
 let se = prompt('Digite seu sexo: ')
 let e = prompt('Digite seu estado civil, usando apenas a inicial da palavra: ')
 let sex = se.toUpperCase()
 let ec = e.toUpperCase()
 if (n.length>3){
     console.log(`Seu nome, ${n}, é válido`)
 }
 else {
     console.log('Nome é inválido')
     console.log('Seu nome deve conter mais de 3 caracteres')
 }
 if (i<150){
     console.log(`Sua idade, ${i}, é válida`)
 }
 else{
     console.log('Sua idade é inválida') 
     console.log('Ela deve ser menor que 150 anos')
 }
 if (sa>0){
     console.log(`Seu salário, ${sa} reais, é válido`)
 }
 else{
     console.log('Seu salário é inválido') 
     console.log('Ele deve ser maior que 0')
 }
 if (sex=='MASCULINO'){
     console.log(`Seu sexo, ${se}, é válido`)
 }
 else if (sex=='FEMININO'){
     console.log(`Seu sexo, ${se}, é válido`)
 }
 else{
     console.log('Seu sexo é inválido')
     console.log('Ele deve ser se Feminino ou Masculino')
 }
 if (ec=='S'){
     console.log('Seu estado civil, solteiro, é válido')
 }
 else if (ec=='C'){
     console.log('Seu estado civil, casado, é válido')
 }
 else if (ec=='V'){
     console.log('Seu estado civil, viúvo, é válido')
 }
 else if (ec=='D'){
     console.log('Seu estado civil, divorciado, é válido')
 }
 else{
     console.log('Seu estado civil é inválido')
     console.log('Coloque apenas a inicial do seu estado civil')
}

 
 
