# Personal Front-End Projects - JS, CSS, HTML

## 1. [Guess My Number](https://github.com/beomjookim/JSprojects/tree/main/project1)

- About:  
  A random number is given and the player(you) guesses the number. Every turn you throw your guess and if it's not correct, the program gives you a hint - ups or downs. You have 20 chances and your point decreases by one as you fail to guess each turn. If you get the number right, your point at the moment is your final point. If it's higher than existing highest point, it replaces the existing one.


- What I Learned:  
  My first toy project done using HTML, CSS, JS. Learned about DOM and how to manipulate DOM while working on this project. Also learned multiple ways to connect JS with HTML and CSS, along with a number of JS grammars(such as document.querySelector) frequently used.
  

- Used Languages: <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" align="center" height="20"><img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" align="center" height="20"><img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" align="center" height="20">

- DEMO:  
<div align="center">
  <img src="https://user-images.githubusercontent.com/29809668/133076536-e4aee95d-fe4a-47b1-a97d-1a8dd7557043.gif" width="70%">
</div>
  
<br><br><br><br><br>  


## 4. [Banking App](https://github.com/beomjookim/smallFrontEndPrjoects/tree/main/project4)

- About:  
  An online banking web application that users can have transactions on, loan money from the bank, check balance and transaction histories. Customized timeline and money notation is applied(exchange rate is not applied) for each user. If the user doesn't have any further movements such as log-out, transfer, loan, delete account, the user will automatically logged out for security reasons just like real banking apps do.  
  

- What I Learned:  
  Assuming we got users' data from API(used dummy data instead), I leanred how to implement log-in and log-out functions using them. I used inserAdjacentHTML, the upgraded version of querySelector, to dynamically add HTML codes. I used higher-order functions and arrow function. Functions like Log-in, deposit, loan, deleting account are implemented using event handlers. preventDefault() was easy to forget, but crucial. I renewed UI after each event. Also, I used Intl API to customize the user's timezone and money notation. Also, I used setInterval instead of setTimeOut to show 'time to be automatically logged out' in real time as well as the auto logout function. Lastly, I used exchange rate API to convert money based on currency of each user and exchange rate in real time when transferring. This was my first time fetching data from browser and applying it to the app.
  

- Used Languages: <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" align="center" height="20"><img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" align="center" height="20"><img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" align="center" height="20">

- DEMO:  
<div align="center">
  <img src="https://user-images.githubusercontent.com/29809668/137443411-0f000144-c389-405f-b408-43277e0d38d7.gif" width="70%">
</div>
<br align="left">  
  Log-in interface. Unregistered account cannot sign in. Alert shows up. I will use the account of Jonah Silverman, a virtual Portugese. As I log in, I can see whose ID that I am logged-in, transaction history, balance, and there are Transfer, Loan, Account Delete buttons. The timeline at upper-left side shows my locale(which is Seoul, Korea) and currency, notations are in Portugese way. I see auto log-out time left at lower-right side.
    

<br><br><br>

<div align="center">
  <img src="https://user-images.githubusercontent.com/29809668/137443577-8d1bf03b-0059-401f-880f-ab3b5762f595.gif" width="70%">
</div>
<br align="left">  
  If I click sort button, the transaction history is sorted by the amount of money.
  
<br><br><br>


<div align="center">
  <img src="https://user-images.githubusercontent.com/29809668/137443595-3cad223a-76c3-41ad-bab8-7fbe6c853458.gif" width="70%">
</div>
<br align="left">  
  Transfer money button enables to send money to another user, as long as the amount is within my balance. I send 1200 to jd, who is an american. Then I log-out, and log in as jd. All the interfaces are changed for this American user, and I see 1200 is right there at transaction history. I didn't consider Exchange Rate, but it can be fixed sooner or later (<= issue solved! check the bottom).
  
<br><br><br>


<div align="center">
  <img src="https://user-images.githubusercontent.com/29809668/137443611-6746571f-bdc8-4266-9f3a-96c86b7ae079.gif" width="70%">
</div>
<br align="left">  
  With the Loan button, you can burrow the amount of money less than 10% of the balance.
  


<br><br><br>

<div align="center">
  <img src="https://user-images.githubusercontent.com/29809668/138204981-ab8b7430-184a-4269-9783-df17e567aa64.gif" width="70%">
</div>
<br align="left">  
  I used exchange rate API to convert money based on currency of each user when transferring. For example, when Jonah(EUR) send € 100 to Jessica, Jonah has -€1000 on his account, while Jessica gets +$1167 on her account. The ER between EUR:USD was 1:1.167 at the time. Exchange rate in real time is applied!
  
