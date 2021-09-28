# Amazon-Alexa-Skill-For-Elrond-Account-Balance-information
This Alexa Skill allows configuration of Elrond blockchain address, showing your balance (EGLD, MEX and other tokens like LPs of Farm tokens)

This skill will implement two intents:
One of them is AddressConfiguracionIntent, used for configuration the user address and is stored for later calls (can be changed). It could be better to use herotag if public api rest allows to do. 

The other intent is BalanceIntent: by telling alexa "show my balance" it will query elrond API REST for configured address, showing current balance of tokens.

This is WorkInProgress.

![image](https://user-images.githubusercontent.com/36307819/135113916-247e080b-c3b7-49a6-a1fd-929d7fec411b.png)
![image](https://user-images.githubusercontent.com/36307819/135113145-0217f4b6-8568-487d-b535-62a35987ae51.png)
