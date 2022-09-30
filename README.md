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

## Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.
<img width="1512" alt="step 1 deploying" src="https://user-images.githubusercontent.com/102783432/193284295-a1ae5655-9bc5-472d-af67-19f3364baec6.png">

<img width="1512" alt="step 1 set accounts" src="https://user-images.githubusercontent.com/102783432/193284309-cd10d39d-0eed-4854-b3e0-c0a1f20bad0f.png">

## Test the deposit functionality of your smart contract by sending the following amounts of ether
#### Transaction 1: Send 1 ether as wei.
<img width="1512" alt="step 2 1 wei" src="https://user-images.githubusercontent.com/102783432/193284407-9b5628ff-9d9b-44df-afc1-f2a9b4844408.png">

#### Transaction 2: Send 10 ether as wei.
<img width="1512" alt="step 2 10 wei" src="https://user-images.githubusercontent.com/102783432/193284477-a5d43b81-fa62-4e38-bf73-3e6bd41bda71.png">

#### Transaction 3: Send 5 ether.
<img width="1512" alt="step 2 5 ether" src="https://user-images.githubusercontent.com/102783432/193284531-2bee0398-2279-4a78-9ca6-19d6cf452f1a.png">

#### 
![Screen Shot 2022-09-29 at 1 31 24 pm](https://user-images.githubusercontent.com/102783432/192932432-e994b986-526a-4a19-9f1a-e757e98aab31.png)

### Test the contract’s withdrawal functionality

- 5 ether into accountOne
<img width="273" alt="Screen Shot 2022-09-29 at 1 43 18 pm" src="https://user-images.githubusercontent.com/102783432/192933909-37d9f5c8-6338-416c-81d2-059bc88c5ff0.png">

- 10 ether into accountTwo
<img width="268" alt="Screen Shot 2022-09-29 at 1 14 41 pm" src="https://user-images.githubusercontent.com/102783432/192932566-ef20630b-c1e8-4d8e-ac92-62e2c9968f72.png">

#### View contractBalance function to verify that the funds were withdrawn from the contract, additionally using the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.
<img width="280" alt="Screen Shot 2022-09-29 at 1 37 28 pm" src="https://user-images.githubusercontent.com/102783432/192933143-d60484f1-5f83-4490-902a-9a199f442867.png">
- Verification of the correct amount and address has shown to be valid, as amounts have been successfully transferred

-----------------------------------------------------------------------------------------------------------------------------------------------------------

- The creation of a Solidity Smart Contract that accepts two user addresses has been carried out successfully, as well as being able to fully control a joint savings account, through the management functions to help implement a financial instituation's requirements for providing features of a joint savings account has proved it's validity. Both accounts were able to withdraw certain amounts of ether, as well as verify if the address and amount were correct which through observation of the images above, that is correct. 






