# Project-bot-telegram-Lotofacil

Every day, I used to bet on Lotofácil, and to simplify this routine, I created a bot called Tokinho. This bot automatically generates the numbers that I should bet, using a CSV file with all Lotofácil results since 2003. Tokinho analyzes the numbers drawn on previous days and selects the ones that historically came out the most on the same day in different years.

For example, if on January 16, 2006 the numbers 1,4,7,8 were drawn, and in 2017 they were 1,3,5,6,8, while in another year there were 2,3,5,8, the bot will choose the numbers 1,3,5,8 for the bet, as they are the ones that came out the most that day over time.

In addition, Tokinho carries out web scraping on the Estadão website to check how many numbers were matched or to consult the results of specific competitions. This way, it extracts the necessary information directly from the website and provides the results quickly and efficiently.

# How to use

To create a bot on Telegram and get your TOKEN: ![image](https://user-images.githubusercontent.com/90096835/212683480-b3f3c415-2408-4dad-be61-b7abdc9e6b51.png)


- Place this TOKEN in the variable *CHAVE_API*

- In the URL variable put the path of your excel file

To get your Excel path from the drive:

*Click on the link where the mouse is above to connect the drive*

![image](https://user-images.githubusercontent.com/90096835/212684339-bf1dbf6f-e7c3-40ac-b723-3d5f499435a0.png)


*Now open the drive folder and look for where you placed your excel*

![image](https://user-images.githubusercontent.com/90096835/212684543-9c1211c4-fe65-4212-8df7-e65ccb1d4b2d.png)


*After finding the file, right-click and copy the path, then just paste it into the variable*

![image](https://user-images.githubusercontent.com/90096835/212684742-f3891991-1f78-496e-a848-40fd472f4d60.png)


**Remember that for the bot to work you need to leave the code running, it is *bot.polling()* that makes the server stay online**

----------------------COMMANDS----------------

*/option1* Game of the day

*/opcao2* Choose a date to collect the numbers

*/opcao3* Check results of the last draw

*/opcao4* Check the results of a specific contest

*/stop* Make Tokin stop working

Any message you send Tokinho will already send you the options, there is no need to send /start.

# Print Showing working
![image](https://user-images.githubusercontent.com/90096835/213453534-3cec2753-51ba-4ea0-b09f-3800b29d74fe.png)

![image](https://user-images.githubusercontent.com/90096835/213454057-70335111-c741-46ab-a72a-48aea28551fc.png)




