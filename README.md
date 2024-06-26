# sennurJS
Module that will be useful to you with many features

# Usage
## Emoji Text (For Discord Bot)
- Converts the text you type into emojis

Example code;
``` js
const sennur = require("sennur")
const text = await sennur.toEmoji("Test")
console.log(text)
``` 
## Top.GG Check Vote (For Discord Bot)
- If your bot is on the Top.GG site, you will be able to easily find out whether any users have voted for your bot!

Example code;
``` js
const sennur = require("sennur")
const result = await sennur.checkVote(`TopGG Bot Token`,`User id`)
console.log(result) // true or false (True: Voted,False: No vote)
```

## Fun Fact
- Gives random fun fact

Example code;
```js
const sennur = require("sennur")
const fact = await sennur.funFact()
console.log(fact) // Fun fact
```

## Leap Year (29 February)
- Indicates whether the entered year is a leap year or not.
- If your site/bot has a birthday system, I recommend using this module!

Example code;
``` js
const sennur = require("sennur")
const result1 = await sennur.isLeapYear("2024")
const result2 = await sennur.isLeapYear("2023")
console.log(result1) // true
console.log(result2) // false
```
# Links
- [Discord](https://discord.gg/nTa2qttkUa)
- [Youtube](https://www.youtube.com/channel/UCakcpjCJKKAJ-6B-fzjnVyA)
