## Como iniciar projeto com pm2 no servidor

1. Primeiro, utilize [esse link](https://pm2.keymetrics.io/docs/usage/quick-start/#cheatsheet) como guia.
2. Abra o servidor e procure o terminal.
3. No terminal, percorra até a pasta do projeto onde você deseja startar o pm2
4. Faça o build do projeto.
5. execute o seguinte comando ``` pm2 start CAMINHO_ATE_O_ARQUIVO.js --name nome-do-projeto-production ``` OBS: o CAMINHO_ATE_O_ARQUIVO.js deve ser o caminho a partir da pasta do projeto até o arquivo .js que starta o servidor.