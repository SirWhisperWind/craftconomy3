# craftconomy3
A Economy plugin for Bukkit &amp; Canary Recode!

# Initial Setup Commands
### Admin Only

|Command|Description|Permission|
| ------------- |:-------------:|:-------------:|
|/ccsetup|**(Admin Command)** Initial setup command.|craftconomy.setup|
|/craftconomy|Shows the config command help.| Unknown |
|/craftconomy bankprice <Amount>|**(Admin Command)** Change the creation price of a bank account.| craftconomy.config.bankprice |
|/craftconomy holdings <Amount>|**(Admin Command)** Set the default amoutn of money in a player account.|craftconomy.config.holdings|
|/craftconomy format <long/small/sign/majoronly>|**(Admin Command)** Sets the display format.| craftconomy.config.longmode (Unsure)|

## Money
### Player Money Commands
|Command|Description|Permission|
| ------------- |:-------------:|:-------------:|
|/money help|Display the help.| None |
|/money|Display your balance in the current world.|craftconomy.money.balance|
|/money all|Display your balance in all worlds.|craftconomy.money.balance|
|/money balance <Account Name>|Shows the balance of the specific account.|craftconomy.money.balance.others|
|/money pay <PlayerName> <Amount>|Send money to someone.|craftconomy.money.pay|
|/money top <Currency> World|Display the top list of a Currency.|craftconomy.money.top|
|/money log <Page> [Account Name]|Display the account log.|craftconomy.money.log|
||Allow the display of other player log.|craftconomy.money.log.others|
|/money exchange <Current Currency> <New Currency> <Amount>|Exchange money from one currency to another.|Unknown|

### Money Admin Commands
|Command|Description|Permission|
| ------------- |:-------------:|:-------------:|
|/money give <Account name> <Amount> [Currency] [World]|**(Admin Command)** Deposit money in a account.|craftconomy.money.give|
|/money take <Account name> <Amount> [Currency] [World]|**(Admin Command)** Withdraw money from a account.|craftconomy.money.take|
|/money set <Account name> <Amount> [Currency] [World]|*(Admin Command)* Set a balance in a account.|craftconomy.money.set|
|/money create <Account Name>|**(Admin Command)** Create a account.|craftconomy.account.create|
|/money delete <Account Name>|**(Admin Command)** Delete a account.|craftconomy.account.delete|
|/money infinite <Account Name>|**(Admin Command)** Set a account in infinite mode.|craftconomy.money.infinite|

## Banks
### Player Bank Commands
|Command|Description|Permission|
| ------------- |:-------------:|:-------------:|
|/bank|Shows bank help.| None |
|/bank create <Account Name>|Create a bank account.|craftconomy.bank.create|
|/bank balance <Account Name>|Check the balance of a bank account.|craftconomy.account.delete|
|/bank deposit <Account Name> <Amount> [Currency]|Deposit money in a bank account.|craftconomy.bank.deposit|
|/bank withdraw <Account Name> <Amount> [Currency]|Withdraw money from a bank account.|craftconomy.bank.withdraw|
|/bank perm <Account Name> <deposit/withdraw/acl/show> <Player Name> <True/False>|Modify the permission of a player.|craftconomy.bank.perm|
|/bank list|List the bank accounts your have access to.|craftconomy.bank.list|

### Bank Admin Commands

|Command|Description|Permission|
| ------------- |:-------------:|:-------------:|
|/bank list/List <Account Name>|**(Admin Permission)** Set the Access list of any bank accounts.|craftconomy.bank.perm.others|
|/bank give <Account Name> <Amount> [Currency] [World]|**(Admin Command)** Give money in a bank account.|craftconomy.bank.give|
|/bank take <Account Name> <Amount> [Currency] [World]|**(Admin Command)** Take money from a bank account.|craftconomy.bank.take|
|/bank set <Account Name> <Amount> [Currency] [World]|**(Admin Command)** Set a balance in a bank account.|craftconomy.bank.set|

## Multiple Currencies
### Admin Commands
|Command|Description|Permission|
| ------------- |:-------------:|:-------------:|
|/currency add <Name> <Name Plural> <Minor> <Minor Plural>|**(Admin Command)** Add a currency in the system.|craftconomy.currency.add|
|/currency edit <name/nameplural/minor/minorplural> <Currency Name> <new Value>|**(Admin Command)** Edit a currency.|craftconomy.currency.edit|
|/currency delete <Name>|**(Admin Command)** Delete a currency from the system.|craftconomy.currency.delete|
|/currency info <Name>|**(Admin Command)** Shows information about a currency.|craftconomy.currency.info|
|/currency exchange <Currency from> <Currency to> <amount>|**(Admin Command)** Set a currency exchange rate.| Unknown |

## Multiple Worlds
### Admin Commands
|Command|Description|Permission|
| ------------- |:-------------:|:-------------:|
|/ccgroup create <Name>|**(Admin Command)** Create a world group.|craftconomy.group.create|
|/ccgroup addworld <Group Name> <World Name>|**(Admin Command)** Add a world to the world group.|craftconomy.group.addworld|
|/ccgroup delworld <World Name>|**(Admin Command)** Remove a world from a world group. This will revert the world to the default balance.|craftconomy.group.delworld|
 @SirWhisperWind
  
            
 
 

Leave a comment
Attach files by dragging & dropping, , or pasting from the clipboard.  Styling with Markdown is supported
© 2018 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
API
Training
Shop
Blog
About
