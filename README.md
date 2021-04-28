# Bot para WhatsApp🤖
Robô para WhatsApp utilizando uma biblioteca Node JS chamada Puppeteer. O bot envia mensagens repetidas para algum contato/grupo. O projeto foi baseado [neste vídeo](https://www.youtube.com/watch?v=Cml20VkyB_A) e para mais detalhes do projeto e como fazê-lo, recomendo que o assista.

## O que foi utilizado✔
- Node JS 
- VS Code
- npm puppeteer

### Comandos utilizados no cmd💻
- create-react-app zapbot
- npm i puppeteer OU yarn add puppeteer

### Por que usar o Puppeteer?🤔
Como foi dito anteriormente, o Puppeteer é uma biblioteca de Node JS. Ele fornece uma API de alto nível para controlar o Chrome ou o Chromium através do Protocolo DevTools. A maioria das coisas que você pode realizar manualmente pelo navegador pode ser feita utilizando-o. No próximo tópico apresento onde o Puppeteer foi utilizado neste projeto.

Fonte: [MundoJS](https://www.mundojs.com.br/2020/03/24/conheca-o-puppeteer-uma-biblioteca-nodejs/)

## Destaques🔍
Aqui estão os principais destaques do código:

![image](https://user-images.githubusercontent.com/71889113/116451386-c876eb80-a832-11eb-8edf-e4bb120d047b.png)
1. As linhas 14 a 16 direcionam o usuário diretamente para a página do WhatsApp Web;
2. As linhas 19 e 20 especificam o contato e direcionam para a conversa;
3. As linhas 24 e 25 mantém a ação na barra de texto;
4. A linha 28 determina quantas vezes a mensagem será enviada;
5. As linhas 31 a 38 possuem um loop que determina qual vai ser a mensagem e as enviam.

## Possíveis soluções para erros❌
1. Verifique se o comando para adicionar o Puppeteer foi instalado dentro do diretório do projeto;
2. Nas linhas 15, 21 e 24 são utilizadas as classes da barra de contato e da caixa de texto da conversa respectivamente. Essas classes podem mudar e ocasionar em erros, o que aconteceu comigo inclusive, por isso recomendo que tente inspecionar a página do WhatsApp Web e tente substituí-las.

## Créditos🌟
[Github do Pedro, responsável pelo vídeo](https://github.com/machadop1407)
