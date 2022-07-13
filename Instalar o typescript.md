### Instalação e preparação do Typescript no VS Code

<br>
<br>

<ol>
  <li>Instalar o Node js</li>
  <br>
  <p>
  É necessária a instalação do Node pois iremos utilizar o gerenciador de pacotes que vem junto com o node para instalar o Typescript, o Node Package Manager (NPM);
  </p>
  
  <li>Testagem</li>
  <br>
  <p>O seguinte comando</p>

    node -v 

  <p>mostra como verificar a versão do node, caso não funcione, este pode ser um sinal de que a instalação não foi bem sucedida.</p>

  <li>Instalar o typescript</li>
  <br>
  
  <p>Este comando instalará o typescript</p>

    npm i -g typescript

  <p>Podemos verificar também a versão do typescript que fora instalada através do comando</p>

    tsc -v
  <li>Praparar o typescript para rodar e compilar arquivos .ts</li>
  <br>
  <p>Para inicializar o typescript basta rodar o comando</p>

    tsc --init

  <p>Isto criará um arquivo .json para que seja passado alguns parâmetros importantes para executar as compilações typescript</p>

  <li>Alterando o arquivo gerado</li>
  <br>
  <p>Iremos as seguintes linhas no arquivo:</p>
  <ul>
    <li>"rootDir": "./assets/ts"</li>
    Responsável por armazenar o caminho do arquivo .ts dentro do pojeto
    <br>
    <br>
   <li>"outDir": "./assets/js"</li>
    Responsável por armazenar a pasta de saida do arquivo que será gerado com a compilação do typescript. Sendo assim, quando o typescript é compilado, ele gera um arquivo .js que é lido pel navegador.
  </ul>
  <br>
  <li>Inicializar o compilador automático para aquivos .ts</li>
  <br>
  <p>Para fazer isso basta rodar o seguinte comando:</p>

    tsc -w
</ol>


	


