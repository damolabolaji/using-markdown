# Heading To My Own File
## Well, here we go


![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


```This is code block for javasript
function gameWithBot(playerChoice){
    if(rockPaperScissors() === playerChoice ){
        return 'You Tied'
    }
    else if ((rockPaperScissors() === 'scissors' && playerChoice === 'rock') ||
    (rockPaperScissors() === 'paper' && playerChoice === 'scissors') ||
    (rockPaperScissors() === 'scissors' && playerChoice === 'rock') ) {
        return'You Win'
    }else{
        return 'You Lose'
    }


}
gameWithBot()
```
