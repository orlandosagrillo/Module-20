# Module-20

# Joint Savings Account

## Background

A company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, the creation of a Solidity smart contract that accepts two user addresses will be carried out. These addresses will be able to control a joint savings account. The smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
## What is being created?

- The completed Solidity JointSavings smart contract.

- A folder named Execution_Results that contains at least eight images. These images should confirm that the deposit and withdrawal transactions, which are            designed to test the JointSavings functionality in the JavaScript VM, worked as expected.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
## Instructions

1. Create a Joint Savings Account Contract in Solidity


2. Compile and Deploy Your Contract in the JavaScript VM


3. Interact with Your Deployed Smart Contract

-----------------------------------------------------------------------------------------------------------------------------------------------------------
## Step 1: Create a Joint Savings Account Contract in Solidity

<img width="937" alt="Screen Shot 2022-09-29 at 1 21 44 pm" src="https://user-images.githubusercontent.com/102783432/192931353-de36e587-efd6-4f8a-a945-e413f670aa60.png">

- When creating a joint savings contract, a variety of variables were utilised to accept arguments, create if statements or functions, and assist in the creation of a free flowing contract. 

-----------------------------------------------------------------------------------------------------------------------------------------------------------
## Step 2: Compile and Deploy Your Contract in the JavaScript VM

<img width="354" alt="Screen Shot 2022-09-29 at 1 08 19 pm" src="https://user-images.githubusercontent.com/102783432/192931590-a48b9880-cc01-40a6-b90d-da168783fedb.png">
- Deploying & Running the transactions

<img width="299" alt="Screen Shot 2022-09-29 at 1 08 42 pm" src="https://user-images.githubusercontent.com/102783432/192931836-5cff5480-e36e-4bb4-9e7e-06cd8f1c650f.png">
- Able to confirm that it successfully deployed the smart contract

-----------------------------------------------------------------------------------------------------------------------------------------------------------
## Step 3: Interact with Your Deployed Smart Contract

### Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

<img width="1326" alt="step 1 deploying" src="https://user-images.githubusercontent.com/102783432/193285985-0c0dfcb6-44c8-47d1-9c6f-2179bab744e0.png">

<img width="1324" alt="step 1 set accounts" src="https://user-images.githubusercontent.com/102783432/193285997-4709f503-dfe9-44c5-8dd4-c843d623acda.png">


### Test the deposit functionality of your smart contract by sending the following amounts of ether

#### Transaction 1: Send 1 ether as wei.
<img width="1322" alt="step 2 1 wei" src="https://user-images.githubusercontent.com/102783432/193286009-ef5f7f1d-7122-4234-9363-424765178a49.png">

#### Transaction 2: Send 10 ether as wei.
<img width="1323" alt="step 2 10 wei" src="https://user-images.githubusercontent.com/102783432/193286025-7b4d1b65-67ec-46f4-bd5e-fb73bbf25f03.png">

#### Transaction 3: Send 5 ether.
<img width="1328" alt="step 2 5 ether" src="https://user-images.githubusercontent.com/102783432/193286083-79b8b46e-7e45-4c17-921e-31418637668e.png">


### Test the contract’s withdrawal functionality

#### Withdrawal - 5 ether into accountOne
<img width="1328" alt="step 3 withdraw 5 ether" src="https://user-images.githubusercontent.com/102783432/193286250-2535c41c-6657-42cf-82b9-301d2ec6dc09.png">

#### Withdrawal - 10 ether into accountTwo
<img width="1323" alt="step 3 withdraw 10 eth" src="https://user-images.githubusercontent.com/102783432/193286259-61833057-f1b2-4211-82da-ca63e7f10078.png">


---------------------------------------------------------------------------------------------------------------------------

The creation of a Solidity Smart Contract that accepts two user addresses has been carried out successfully, as well as being able to fully control a joint savings account, through the management functions to help implement a financial instituation's requirements, has providing features of a joint savings account, proving it's validity. Both accounts were able to withdraw certain amounts of ether, as well as verification of the address and amount, as seen above.






