# Atividade-Avaliativa---0-5---20h10


const express = require('express')
const app = express()
const port = 3000

//Rota padrão ou rota raiz

app.get('/', (req, res) => {
res.send('Hello World!')
})

app.listen(port, () => {
console.log('Está rodando no endereço: http://localhost:${port}')
})


O código inicia importando o módulo express, necessário para criar o servidor.
depois ele cria uma instância chamada app. Criando uma porta 3000,atribuindo esse valor à variável port.
Quando esta rota é acessada via método GET, a resposta 'Hello World!' é enviada de volta.
Usa obQuando o servidor é iniciado com sucesso, imprime uma mensagem.
