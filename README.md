# Decentralized-KYC-Validation-Ethereum-Solidity
Background of the Problem Statement:
KYC (Know Your Customer) is a service provided by financial institutions such as banks. There are both public and private sector banks managed by a central bank. These banks are banned by the central bank from adding any new customer and do any more customer KYCs as they see suspicious activities that need to be sorted out first. Despite this, the banks add new customers and do the KYC in the background.

Solution:
An immutable solution is needed where the central bank maintains a list of all the banks and tracks which banks are allowed to add new customers and perform KYC. 
It can also track which customer KYC is completed or pending along with customer details.
Banks can also add the new customer if allowed and do the KYC of the customers.

Features of KYC Application:
* Add new bank to Blockchain ledger
* Add New customer to the bank
* Check KYC status of existing bank customers
* Perform the KYC of the customer and update the status
* Block bank to add any new customer
* Block bank to do KYC of the customers
* Allow the bank to add new customers which was banned earlier
* Allow the bank to perform customer KYC which was banned earlier
* View customer data

Tools Used:
1.	Smart Contract development: Solidity
2.	IDE tool: Remix
3.	Blockchain: Ethereum
4.	Server: Ganache Blockchain

Required Roles:
Administrator: The deployed Ethereum address plays as a admin user.
Banks details with all the required permissions.
Customers deatils with all the rules and protocols required for the KYC update.

Output for Reference:


![image](https://user-images.githubusercontent.com/114467037/192463218-152f91a0-7312-4ad4-b391-675cfa791202.png)

