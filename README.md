# ready-bot



Based off the ready-bot and modified exclusively for the Brotherhood Discord. Full Credit goes to <a ref="https://travis-ci.org/BurnsCommaLucas/ready-bot" target="_blank" src="https://travis-ci.org/BurnsCommaLucas/ready-bot.svg?branch=master"></a> for the Bot.




## Usage

Once you add the bot to your server, start a ready check with:

```
!cready <number>
```
and have players ready-up with 
```
!ready
```
Full usage can be found by typing 
```
!ready help
```
Ready checks can be overridden by another instance of the first command, and checks will only be performed if the number entered is greater than 0. The person who initiates the ready check may also respond to the check as ready.

If you experience any unusual behavior from the bot or think of a feature that could be added, please open an issue ticket. 

## Planned Improvements

- Disable @everyone mention on check initiation
- Disable mention for ready-checker upon completion of check
- @everyone upon completion of check
- @ only the people involved in the check
- Remove members as ready-check candidates
- Specify members as ready-check candidates
