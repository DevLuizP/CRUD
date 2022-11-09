#  JS na web: crud com JavaScript assíncrono

-------------------------------------------------

  <h2> Subindo o servidor com BrowserSync </h2>

<p> Após realizar a instalação da extensão Browser-Sync com o comando: </p>

      npm install -g browser-sync
  
<p>basta rodar o comando abaixo para subir o servidor</p>
  
      browser-sync start --server --file . --host --port 5000 --startPath YourPathToFile.html
      

  <h2>Abrindo servidor JSON</h2>
   
<p>
Para iniciar o servidor json responsável por hospedar os dados dos testes, primeiro faça a instalação global do json-server
</p>

    npm install -g json-server

<p>
Agora navegue até a pasta do projeto onde ficará hospedado o arquivo db.jason, no caso desde repositório é a pasta "admin",
e então execute:
</p>

    json-server --watch db.json
    
    
<p>
Para verificar a documentação completa do json-server basta acessar o link abaixo:
</p>

    https://www.npmjs.com/package/json-server
    
