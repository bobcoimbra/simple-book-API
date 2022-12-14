
## Testes automatizados para teste de API com Postman 
### SimpleBookApi
Endpoit: https://simple-books-api.glitch.me

Escopo:
- Listar livros disponíveis
- Cadastrar compra de livro
- Modificação a ordem de comprar
- Deletar a ordem de compra

Relatórios gerados com Newman: o primeiro foi gerado com o relatório padrão, e o segundo customizado e disponivel com a instalação do package:
```
npm install -g newman-reporter-htmlextra
```
Comando para geração de relatorio em link compartilhado do projeto:
```
newman run SimpleBookApi.postman_collection.json --reporters=cli,htmlextra
```
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/0dc3f82aae6cf73ec8b6?action=collection%2Fimport)

<p>**note-pt:** Obrigado ao freecodecampo.org e ao Valentin Despa pelas aulas. Eu super recomendo ambos canais. (Links abaixo)</p>
<p>**note-en:** Thanks to freecodecamp.org and Valentin Despa for the classes. I highly recommend bouth channels. (Links below)</p>
<p align="left">
<a href="https://www.youtube.com/@freecodecamp" target="_blank"> <img src="https://yt3.ggpht.com/ytc/AMLnZu9UWrGceKWaqm8AF89vuxrEt8MO3E59qOoQ785Lew=s88-c-k-c0x00ffffff-no-r" alt="robot framework" width="40" height="40"/> </a><a href="https://www.youtube.com/@vdespa" target="_blank"> <img src="https://yt3.googleusercontent.com/ytc/AMLnZu9keYOW3E8lhfmFHrUGtBdopQQpDVQcVk-FaGs2=s88-c-k-c0x00ffffff-no-rj" alt="robot framework" width="40" height="40"/> </a>
