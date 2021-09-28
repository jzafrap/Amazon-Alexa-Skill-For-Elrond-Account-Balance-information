# Amazon-Alexa-Skill-For-Elrond-Account-Balance-information
This Alexa Skill allows configuration of Elrond blockchain address, showing your balance (EGLD, MEX and other tokens like LPs of Farm tokens)

This skill will implement two intents:
One of them is AddressConfiguracionIntent, used for configuration the user address and is stored for later calls (can be changed). It could be better to use herotag if public api rest allows to do. 

The other intent is BalanceIntent: by telling alexa "show my balance" it will query elrond API REST for configured address, showing current balance of tokens.

This is WorkInProgress.
