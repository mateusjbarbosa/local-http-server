# Passo a passo para criar um servidor HTTP local

1. Acesse [este link](https://nodejs.org/en) e baixe a versão LTS. Siga as instruções ditas no site.

2. Após instalado, execute `node --version` para validar que o Node.js foi instalado corretamente.

3. Na raiz deste projeto, execute `npm install` para inicializar o projeto e instalar as dependências.

4. Substitua o conteúdo da pasta `public` pelo conteúdo que deseja hospedar no seu servidor HTTP local.

5. Execute o comando `npm start` e utilize o IP `http://127.0.0.1:8080` para executar em sua máquina ou o inicializado por `http://192.168.` para utilizar em dispositivos que estão na sua rede local como celulares ou outros computadores.

5.1. Caso seja necessário alterar a porta de acesso ao servidor HTTP, basta alterar o argumento `8080` no `package.json.scripts.start`
