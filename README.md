# Module-20

# Joint Savings Account

## Background

A company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, the creation of a Solidity smart contract that accepts two user addresses will be carried out. These addresses will be able to control a joint savings account. The smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

## What is being created?

- The completed Solidity JointSavings smart contract.

- A folder named Execution_Results that contains at least eight images. These images should confirm that the deposit and withdrawal transactions, which are            designed to test the JointSavings functionality in the JavaScript VM, worked as expected.


## Instructions

1. Create a Joint Savings Account Contract in Solidity


2. Compile and Deploy Your Contract in the JavaScript VM


3. Interact with Your Deployed Smart Contract


## Step 1: Create a Joint Savings Account Contract in Solidity

<img width="937" alt="Screen Shot 2022-09-29 at 1 21 44 pm" src="https://user-images.githubusercontent.com/102783432/192931353-de36e587-efd6-4f8a-a945-e413f670aa60.png">

- When creating a joint savings contract, a variety of variables were utilised to accept arguments, create if statements or functions, and assist in the creation of a free flowing contract. 

## Step 2: Compile and Deploy Your Contract in the JavaScript VM

<img width="354" alt="Screen Shot 2022-09-29 at 1 08 19 pm" src="https://user-images.githubusercontent.com/102783432/192931590-a48b9880-cc01-40a6-b90d-da168783fedb.png">
- Deploying & Running the transactions

<img width="299" alt="Screen Shot 2022-09-29 at 1 08 42 pm" src="https://user-images.githubusercontent.com/102783432/192931836-5cff5480-e36e-4bb4-9e7e-06cd8f1c650f.png">
- Able to confirm that it successfully deployed the smart contract

## Step 3: Interact with Your Deployed Smart Contract

#### Transaction 1: Send 1 ether as wei.
<img width="974" alt="Screen Shot 2022-09-29 at 1 12 29 pm" src="https://user-images.githubusercontent.com/102783432/192932241-46e9878d-dbde-406f-9617-28efb31605cd.png">

#### Transaction 2: Send 10 ether as wei.
<img width="972" alt="Screen Shot 2022-09-29 at 1 12 55 pm" src="https://user-images.githubusercontent.com/102783432/192932276-96dd2d98-db7d-4829-8fda-b5e5dccb29bb.png">

#### Transaction 3: Send 5 ether.
<img width="962" alt="Screen Shot 2022-09-29 at 1 13 07 pm" src="https://user-images.githubusercontent.com/102783432/192932382-6e49e6fb-a7ff-4858-b5f3-be2ea8f0e1e9.png">

#### 16 ETH Balance.
![Screen Shot 2022-09-29 at 1 31 24 pm](https://user-images.githubusercontent.com/102783432/192932432-e994b986-526a-4a19-9f1a-e757e98aab31.png)

### Test the contract’s withdrawal functionality

- 5 ether into accountOne
<img width="273" alt="Screen Shot 2022-09-29 at 1 43 18 pm" src="https://user-images.githubusercontent.com/102783432/192933909-37d9f5c8-6338-416c-81d2-059bc88c5ff0.png">

- 10 ether into accountTwo
<img width="268" alt="Screen Shot 2022-09-29 at 1 14 41 pm" src="https://user-images.githubusercontent.com/102783432/192932566-ef20630b-c1e8-4d8e-ac92-62e2c9968f72.png">

#### View contractBalance function to verify that the funds were withdrawn from the contract, additionally using the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.
<img width="280" alt="Screen Shot 2022-09-29 at 1 37 28 pm" src="https://user-images.githubusercontent.com/102783432/192933143-d60484f1-5f83-4490-902a-9a199f442867.png">
- Verification of the correct amount and address has shown to be valid, as amounts have been successfully transferred



- The creation of a Solidity Smart Contract that accepts two user addresses has been carried out successfully, as well as being able to fully control a joint savings account, through the management functions to help implement a financial instituation's requirements for providing features of a joint savings account has proved it's validity. Both accounts were able to withdraw certain amounts of ether, as well as verify if the address and amount were correct which through observation of the images above, that is correct. 






]
