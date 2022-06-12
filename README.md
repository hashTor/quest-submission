# quest-submission

## Chapter 1 Day 1 Quests
1. Explain what the Blockchain is in your own words. You can read this to help you, but you don't have to: 
          A blockchain is a public and open decentralized database where you can stored data or information. On which you a user can securely execute a transactions that cannot be altered or modified once executed. 

2. Explain what a Smart Contract is. You can read this to help you, but you don't have to:
         A smart contract is a program running on top of the blockchains to perform certain tasks , transactions and its output can be predicted based on its logic or flow of the program. 

Explain the difference between a script and a transaction.
         Transaction in blockchains means that it will execute a process that involve modification on the blockchain database such as transfer , minting , and etc that had some cost once executed;  while a script is use to view data on the blockchain and that does not perform any modification. 

## Chapter 1 Day 2 Quests
1. What are the 5 Cadence Programming Language Pillars?   
       The five pillars are clarity, approachability, developer experience, and resource oriented programming. 

2. In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful (you don't have to answer this for #5)?   
        For ease of deployment, and users are able to verify whats the smart contract is doing if its harmful or not before they intract with it.
        
 ## Chapter 2 day 1 Quests

1. Deploy a contract to account 0x03 called "JacobTucker". Inside that contract, declare a constant variable named is, and make it have type String. Initialize it to "the best" when your contract gets deployed.

0x03
pub contract JacobTucker{

 
  pub let is: String

 

      init() {

        self.is = "the best"

    }

  
}

 

Script: 

import JacobTucker from 0x03

 pub fun main(): String {

  return JacobTucker.is
 
}


![Chapter2Day1](https://user-images.githubusercontent.com/85352662/173072122-3e83f502-6614-4a25-95d0-bae5acbcfc4f.jpg)




## Chapter 2 day 2 Quests

1. Explain why we wouldn't call changeGreeting in a script.
          - The call "changeGreeting" modified the vasriable  contain those it should ba a transaction not a script.
2. What does the AuthAccount mean in the prepare phase of the transaction?
          -Its means that it will accessing my data on my account, then sign it to approve the trasactions.
         
3. What is the difference between the prepare phase and the execute phase in the transaction?
          prepare is to access the data in my account , while execute phase is to call a function or change the blockchain data.
          
4. This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.

Add two new things inside your contract:

A variable named myNumber that has type Int (set it to 0 when the contract is deployed)
A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber
Add a script that reads myNumber from the contract

Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.


![Chapter2Day2a](https://user-images.githubusercontent.com/85352662/173229602-e16d8295-0085-4075-be2f-18e104a291ff.jpg)

![Chapter2Day2b](https://user-images.githubusercontent.com/85352662/173229606-48ba5dae-d45c-44eb-8851-14caac93b714.jpg)

![Chapter2Day2c](https://user-images.githubusercontent.com/85352662/173229608-9224d740-232d-48eb-bd39-5e1392d2b0fe.jpg)
