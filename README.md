# Projeto-bot-telegram-Lotofacil
Repositório contendo o .ipynb e o arquivo excel para rodar o Bot.

Diariamente eu aposto na loteria Lotofácil, então como uma forma de facilitar minha vida criei esse bot que gera para mim números diariamente para eu apostar. Tokinho (nome que dei a ele) através do CSV que tem todos os últimos resultados da lotofácil desde 2003, filtra os números do dia da aposta se baseando em quais números que mais sairam nesse mesmo dia no passado, por exemplo se no dia 16/01 de 2006 sairam os numeros *1,4,7,8* esse mesmo dia e mes só que em 2017 sairam *1,3,5,6,8* e em outro ano mas mesmo dia sairam *2,3,5,8* ele irá pegar os números **1,3,5,8** pois foram os números que mais sairam nesse mesmo dia. Para conferir quantos números você acertou ou consultar o resultado de um concurso em específico, Tokinho faz um web scraping no site do Estadão, lá ele pega as informações necessárias e te devolve o resultado.

# Como utilizar

Para criar um bot no telegram e pegar seu TOKEN: ![image](https://user-images.githubusercontent.com/90096835/212683480-b3f3c415-2408-4dad-be61-b7abdc9e6b51.png)


- Coloque esse TOKEN na variavel *CHAVE_API*

- Na variável URL coloque o caminho do seu arquivo excel 

Para pegar o caminho do seu excel pelo drive:

*Clice no link onde o mouse está em cima ali, para conectar o drive*

![image](https://user-images.githubusercontent.com/90096835/212684339-bf1dbf6f-e7c3-40ac-b723-3d5f499435a0.png)


*Agora abra a pasta drive e procure onde você colocou o seu excel*

![image](https://user-images.githubusercontent.com/90096835/212684543-9c1211c4-fe65-4212-8df7-e65ccb1d4b2d.png)


*Depois de achar o arquivo clique com o botão direito e copie o caminho, depois só colar na variável*

![image](https://user-images.githubusercontent.com/90096835/212684742-f3891991-1f78-496e-a848-40fd472f4d60.png)


----------------------COMANDOS----------------

*/opcao1* Jogo do dia

*/opcao2* Escolher uma data para pegar os números

*/opcao3* Conferir resultado do ultimo sorteio

*/opcao4* Conferir resultado de um concurso em especifico

*/stop*   Fazer o Tokin parar de funcionar
