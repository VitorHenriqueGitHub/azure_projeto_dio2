Para completar este projeto eu precisei adquirir as imagens, eu procurei as imagens do inputs na internet, 
e selecionei as 4 que achei mais interessantes, então eu acessei o visual studio e segui o mesmo processo mostrado nos videos anteriores,
eu anexei as imagens do inputs no visual studio e pedi para ele reconher as letras presentes nestas imagens. 
O resultado adquirido foi como o esperado, a IA OCR do visual studio foi capaz de reconhecer e extrair perfeitamente as letras presentes nas imagens,
assim que eu adquiri os resultado tirei print deles e armazenei esses prints na pasta outputs.

Assim que eu consegui todos os arquivos para o projeto, eu fui no github e criei um novo repositorio vazio, uma vez que o repositorio já foi criado, 
eu fui em minha área de trabalho e criei uma nova pasta, armazeinei então as pastas inputs e outputs dentro desta pasta e abri o git, então utilizei esta sequencia de comandos:
git init
git add .
cd inputs
git commit -m"primeiro commit"
git add .
git status
git log
git remote add origin https://github.com/VitorHenriqueGitHub/azure_projeto_dio2.git
git push -u origin main
uma vez que a pasta inputs junto de todos seus arquivos foi enviado para o repositorio no github, eu repeti a mesma sequencia só que desta vez na pasta outputs, e como o esperado, a pasta foi enviada para o git hub
com isto o projeto foi finalizado.
