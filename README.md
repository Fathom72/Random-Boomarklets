# Random-Boomarklets
Some random bookmarklets I made. (Work in progress.)
To use them put them into your bookmarks and press them. They sadly wont work on all sites such as Chrome sites and the Google search page.

# Games


Guess My Number
A small game where you have to guess the number. (wont let you exit untill you guess it. lol.)

function RandomNum(min, max){return Math.floor(Math.random() * (max - min)) + min};function TellNum(){if(NumGuess==SecretNum){alert('Exactly! You win!');Guessed=(1)}else{if(NumGuess>SecretNum){alert('Too high!');NumGuess=prompt('Your guess');TellNum()}else{if(NumGuess<SecretNum)alert('Too low.');NumGuess=prompt('Your guess');TellNum()}}};let SecretNum=(RandomNum(1, 100));alert('Guess my number, it is 100 to 1');let Guessed=(0);let NumGuess=prompt('Your guess');if(Guessed==0){TellNum()}

Cookie Clicker
Self expanitory, you can exit anytime but it wont save.
function clicker(){if(window.confirm('Cookies: '+Cookies)){Cookies++;clicker()}else{alert('See you soon! Your cookies: '+Cookies)}};let Cookies=(0);alert('Nice to see you again! Space bar or OK to cook! Cancel or ESC to leave!');clicker()

# More soon!
