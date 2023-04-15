# Mini-curso de Git e Github

  <h1> O que é? </h1>
    <strong> Projeto de Software: </strong>
      <p> Conjunto de arquivos de código de vários desenvolvedores que compõem a produção de um software final. </p>
    <strong>O que é uma CLI?</strong>
      <p> É uma sigla para “Command Line Interface”, as CLI’s são utilizadas por diversas aplicações e funcionam de forma facilitar o envio de comandos aos softwares         através do terminal. </p>
    <strong>Repositório:</strong>
      <p> É onde os arquivos do seu projeto são armazenados juntamente com todas as versões anteriores.É legal quando estiver em equipe criar como organização pois ai todos terão aquele repositório como seu </p>
  
  <h1> Git </h1>
    <strong> Clonar o repositório local</strong>
      <p> É uma fotografia do seu código em um determinado momento no tempo quando fazemos um commit estamos salvando uma versão do nosso código </p>
      <p><strong>Clonar Repositório</strong></p>
      <p> Ele faz uma cópia do próprio projeto que você quer trabalhar e traz tudo para sua máquina. </p>
      <p> 1. Git Bush -> Copiar o link no Code -> HTTPS.</p>
      <p> 2. git clone <url> </p>
      <p> Agora pegou o repositório e trouxe para sua máquina </p>
  
  <h1> Comandos para commit </h1>
    <strong> Os 4 passos para ser enviado para o Github</strong> 
    <strong> Git Status </strong>
      <p> Sempre verifique o que foi mudado antes de commitar, isso impede que coisas indesejáveis vão para o repositório. Tudo o que está em **vermelho** é algo novo       que fizemos e que não está no repositório ainda mas está na pasta. Te mostrar todos os arquivos alterados</p>
    <strong> git add "nome do arquivo" </strong>
      <p> Quais os arquivos você quer que entre no repositório</p>
    <strong> commit -m “mensagem” </strong>
      <p> Serve para nomear o commit e sabermos qual alteração foi feita </p>
  
  <h1> Branches </h1>
    <p> Usamos para que nossa modificação não altere a do colega. São como extensões do tronco principais que tem seu trabalho próprio. </p>
    <strong> Como criar uma Branch  </strong>
      <p>1. Vá para o GitHub  e git clone </p>
      <p>2. git branch <nome da branch> , o branch é um comando que proporciona a criação de uma brench nova, tente padronizar o nome das branches no projeto.</p>
      <p>3. Para entrar na branch git checkout “nome da branch” </p>
      <p>4. touch "nome do arquivo" para criar arquivo na branch </p>
      <p>5. git add "arquivo" </p>
      <p>6. git commit -m "mensagem da commit"</p>
      <p>7. git push --set-upstream origin</p>
    <strong> Como navegar entre branches no Git </strong>
      <p>checkout "nome da branch"</p>
    <strong> fatch </strong>
        <p> O fatch é utilizado para atualizar o repositório local com o repositório compartilhado </p>
      <strong>Pull</strong>
        <p> O pull é utilizado após o fetch, ele serve para atualizar os os arquivos que sofrem mudanças naquela brench</p>
      <strong>git push --set-upstream origin</strong>
      <p>Esse comando mais complexo serve para quando uma branch recém criada não está no repositório compartilhado, ao executar o comando, a branch passará a ser reconhecida remotamente.</p>
      <strong>Pull request<strong>
        <p>São solicitações de incorporação de uma branch em outra. O pull request é uma forma de manter o controle sobre o que entra e o que não entra no projeto. Para fazer um, basta criá-los na plataforma de GIT escolhida, no caso, usaremos o GITHUB para a demonstração.</p>
  <br>
  <br>
  <strong> OBS: </strong>
  <br>
  <p><img align="left"  height="80" width="600" src="https://dune-soprano-18f.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F7f5de5cc-df04-480d-8e30-85834f37e3d0%2FUntitled.png?id=1e88ae50-a555-4084-ba17-748505801502&table=block&spaceId=d742f9fe-0c3e-4980-888f-b424ff5cf418&width=820&userId=&cache=v2"></p>
  <p> O main significa o branch principal do seu repositório</p>
  <p>cd + tab para navegar entre as pastas</p>
  <br>
  <p><img align="left" height="80" width="600" src="https://dune-soprano-18f.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Feb6236e9-9f48-4b5b-afe4-9e027aa31026%2FUntitled.png?id=34ea8a2c-a113-4d3d-be6e-bb868e2f7afd&table=block&spaceId=d742f9fe-0c3e-4980-888f-b424ff5cf418&width=820&userId=&cache=v2"></p>
  <p>touch faz a criação de um novo arquivo naquela pasta</p>
    <br>
    <strong> Referência: </strong>
    <p>https://docs.google.com/presentation/d/1NLpubE07RA0fGjcaICey0Bf12P_0VxTJImqTcAUDqQA/mobilepresent?slide=id.g213be7910ba_0_0</p>
  
  
  
  
  
   
  
