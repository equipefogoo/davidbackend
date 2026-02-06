const parte1 = "Node";
const parte2 = ".js";
// Guardamos o resultado da junção em uma terceira variável antes de imprimir
const resultado = parte1 + parte2;
console.log(resultado);
// 'fs' é o módulo de File System (Sistema de Arquivos)
const fs = require('fs'); 
// O comando abaixo cria (ou sobrescreve) um arquivo chamado 'vazio.txt' com conteúdo vazio ('')
fs.writeFileSync('vazio.txt', ''); 
console.log("Arquivo criado no teu computador!");
// 'new Date()' é um comando interno do JavaScript que captura o momento atual do sistema
console.log("Data atual: " + new Date());
