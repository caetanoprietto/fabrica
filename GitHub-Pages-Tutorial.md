<h1 align="center">Tutorial para o GitHub Pages</h1>
Aqui será ensinado como utilizar o GitHub Pages para desenvolver e hospedar uma aplicação web completa.

# 1º Passo: Criar um repositório para seu site

Você pode criar um novo repositório ou utilizar um repositório já existente para hospedar seu site no GitHub Pages.

Se o repositório escolhido contiver arquivos que não fazem parte do site, é possível definir uma fonte específica de publicação. Isso significa que você pode, por exemplo, 
reservar um branch ou uma pasta apenas para os arquivos do site, ou ainda configurar um fluxo de trabalho no GitHub Actions para gerar e publicar automaticamente o conteúdo.



<h3>Para criar o repositório, você deve: </h3>

1 - Clicar no +, então, clique em `New repository(Novo repositório)`.

<img width="364" height="400" alt="Captura de tela de 2025-09-03 14-36-41" src="https://github.com/user-attachments/assets/1c7f2828-5c12-4e7e-9e30-8fc1160552c4" />

2 - Adicionar um nome ao repositório. O nome deve ser `<user>.github.io`.

Obs - Vale lembrar que, no caso de contas que utilizam o GitHub Free (para usuários individuais ou organizações), o repositório deve estar configurado como `público` para que o GitHub Pages funcione.

3 - Selecione `Add README(Adicionar LEIAME)`.

4 - Clique em `Create repository (Criar repositório)`.

<img width="748" height="731" alt="Captura de tela de 2025-09-03 14-47-12" src="https://github.com/user-attachments/assets/99f5ecb0-9b3b-41b6-bdd9-5f2795e89cd8" />

# 2° Passo: Criar seu site

Crie o arquivo de entrada para seu site. GitHub Pages procurará um arquivo `index.html`, `index.md` ou `README.md` como o arquivo de entrada do seu site.

Se você definir como fonte de publicação um branch e uma pasta, o arquivo de entrada do site deve estar diretamente no nível superior da pasta no branch de origem. 
Por exemplo: caso a fonte de publicação seja a pasta /docs no branch main, o arquivo de entrada precisa estar localizado dentro de /docs em um branch chamado main.

Caso a publicação seja feita por meio de um fluxo de trabalho do GitHub Actions, o artefato gerado para implantação deve conter o arquivo de entrada na raiz. 
Em vez de manter esse arquivo diretamente no repositório, você pode configurar o fluxo de trabalho do GitHub Actions para criá-lo automaticamente durante a execução.

Acesse `<user>.github.io` para ver seu novo site. Observe que poderá levar até 10 minutos para que as alterações no seu site sejam publicadas depois que você efetuar push das alterações no GitHub.
