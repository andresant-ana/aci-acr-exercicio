# Fazendo deploy do projeto via ACR e ACI
---
## 1. Criando grupo de recursos:
![PRINT](https://i.imgur.com/ZroCNFR.png)

## 2. Criando um registro de container com o plano ‘Basic’ no grupo de recursos criado anteriormente:
![PRINT](https://i.imgur.com/EtwCmeL.png)

## 3. Conforme aprendido em sala, antes de fazer o pull e push nas imagens, é preciso logar no registro:
![PRINT](https://i.imgur.com/WO3NnWM.png)

## 4. Criando o Dockerfile no diretório ‘app’:
![PRINT](https://i.imgur.com/a5Bm6CL.png)

## 5. Buildando a imagem do container com sucesso:
![PRINT](https://i.imgur.com/fAQKJkx.png)

## 6. Iniciando o container na porta 80 e especificando o nome da imagem:
![PRINT](https://i.imgur.com/xVgSxuA.png)

## 7. App rodando localmente na porta 80:
![PRINT](https://i.imgur.com/kVHzHlF.png)

## 8. Após testar localmente, removendo o container:
![PRINT](https://i.imgur.com/NuYtPaL.png)

## 9. Remarcando a imagem, criando uma nova imagem com o namespace para subir no Azure e realizando o push para o ACR:
![PRINT](https://i.imgur.com/ZaDFmS3.png)

## 10. Após realizar o push, removendo a nova imagem do ambiente local:
![PRINT](https://i.imgur.com/pFQzy8x.png)

## 11. Removendo a imagem original:
![PRINT](https://i.imgur.com/uDjy4W4.png)

## 12. Listando as imagens registradas no Azure:
![PRINT](https://i.imgur.com/jWKuHqE.png)

## 13. Executando a imagem do registro no Azure, com pull automático e executando o container localmente:
![PRINT](https://i.imgur.com/bZkedhR.png)

## 14. Testando no https://localhost:80 :
![PRINT](https://i.imgur.com/Ft6eJFZ.png)

## 15. Limpando o ambiente de desenvolvimento após testar o pull e rodar o container localmente:
![PRINT](https://i.imgur.com/v2yTaXb.png)

## 16. Habilitando admin user no registro para iniciar o deploy do container:
![PRINT](https://i.imgur.com/pIsuRHu.png)

## 17. Fazendo login no Azure CLI com o user e a senha de admin do container registry:
![PRINT](https://i.imgur.com/4UtiR29.png)

## 18. Implantando a imagem em um Container Instance do Azure:
![PRINT](https://i.imgur.com/rh7BKQJ.png)

## 19. Após a implantação concluir, vamos verificar e coletar os valores FQDN e o IP do container criado:
![PRINT](https://i.imgur.com/xgciWBU.png)

## 20. Agora com o endereço coletado, vamos acessar o container (como a porta é a 80, não precisamos inserí-la no URL):
![PRINT](https://i.imgur.com/0nPP53X.png)

## 21. Limpando os recursos
![PRINT](https://i.imgur.com/vt5sDTC.png)
