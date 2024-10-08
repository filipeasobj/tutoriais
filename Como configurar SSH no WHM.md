## Como configurar SSH no WHM

1. Primeiro, crie uma chave dentro do servidor ou utilize uma já criada. OBS: a chave deve ser criada dentro do servidor. Segue abaixo links úteis para criar uma chave:
- [link 1](https://github.com/appleboy/scp-action)
- [link 2](https://help.umbler.com/hc/pt-br/articles/206576653-Gerando-a-chave-p%C3%BAblica-do-SSH?gad=1&gclid=CjwKCAjw-b-kBhB-EiwA4fvKrCLGxPkkq0JydG2Cw7U_VfjbM5Qt6-mWtTyvOHp3wzN_llQLu0knwhoC6-AQAvD_BwE)
- [link 3](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
2. Depois configure as chaves de action no repositório. Veja abaixo as chaves:
``` 
SSH_HOST: ip do servidor onde vai ficar hospedado
SSH_KEY: chave privada ssh criada na etapa 1.
SSH_PORT: 1157 (porta do ssh no whm. para descobrir qual é o numero da porta, abra o terminal no whm e digite: nano /etc/ssh/sshd_config)
SSH_USER: username da conta do servidor onde vai ficar hospedado
 ```
