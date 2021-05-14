# Ponto Inteligente Cliente
Código cliente Angular 11 do sistema de ponto inteligente.
### Como executar a aplicação
O código cliente depende da API RESTful [https://github.com/m4rciosouza/ponto-inteligente-api-curso-angular-v2](https://github.com/SPRINGBOOTJAVA/ponto-inteligente-api-curso-angular-v2), que deverá estar configurada e em execução como requisito.
Para executar o cliente (após a execução da API RESTful), execute os seguintes passos:
```
git clone https://github.com/m4rciosouza/ponto-inteligente-client-curso-angular11.git
cd ponto-inteligente-client-curso-angular11
npm install -g @angular/cli
npm install
npm start

ng add @angular/material
npm add hammerjs
npm install @angular/flex-layout

ng serve --aot
```
Acesse a aplicação em [http://localhost:4200](http://localhost:4200)  

*Para sua execução certifique-se também de possuir o [NodeJS](http://nodejs.org).*  
*A instalação do @angular/cli acima pode necessitar ser executada como admin do sistema*  
