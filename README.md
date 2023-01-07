# Purchasing Houses using blockchain and streamlit

# Background
Our Python project aims to make the process of buying and selling houses more efficient and secure by using blockchain technology. We have created a platform that allows users to list their properties for sale and browse available listings.
Once the conditions of the sale have been met, the platform automatically executes the transfer of ownership and funds on the blockchain.
Overall, our Python project utilizing blockchain technology aims to provide a faster and safer way for individuals to buy and sell houses.

##
Our project aims to allow users to purchase / sell a house using blockchain technoledgey. With our program, people have the option to browse photos of the houses, and other important details like sqft, price, adress, and more. The streamlit userface allows for a simple UI for user to interact with. This program is running on a virutal serivce, allowing anyone to view it by using a web address. 

# Blockchain 

In the package, there is a crypto_wallet.py that is made up of basic blockcahin functions. This file contains all the functions, we inherit, in the main .py file. Using ganache, we are able to test the payment system. Becuase of this, the houses are priced according to how much a Ganache wallet holds.

# Main.py

Due to restrints of the test eviroments wallet, the prices of the houses are much lower than actual. Due to the limitations, we price the house in ETH and within the values we had in our test wallets. Otherwise, we'd price the houses in USD then convert to ETH value for transaction

# Imports
crypto_wallet.py
![alt=""](./ReadMe%20Images/Screenshot%202023-01-06%20at%205.54.53%20PM.png)
housing_streamlit.py
![alt=""](./ReadMe%20Images/Screenshot%202023-01-06%20at%205.55.18%20PM.png)

# Configuration

The yaml configuration file is used to store username and password data for login credentials. If an incorrect password is entered the user will receive an error message. This function is just a mock-up and only stores a handful of selected usernames for demo purposes. Plans for future advancement include the ability to store crypto wallet ID's along with the usernames.  

# Crypto_Wallet.py

Crypto wallet that loads user’s dotenv() file for mnemonic phrase. The mnemonic phrase is unique to the user’s crypto wallet authentication keys. It also automatically estimates and sets gas price strategies for all executed transactions. It converts eth into wei which is required for gas fees, and sends a signed transaction for user confirmation.

# Streamlit File

<img width="1440" alt="Screenshot 2023-01-04 at 6 39 32 PM" src="https://user-images.githubusercontent.com/18622578/211123050-fe90e657-b6a3-4dfe-a2d9-b1d9a4bcd75a.png">

Our housing_streamlit file creates a decentralized application (dApp) using Streamlit, where users can purchase and sell homes by selecting a home from the drop down feature.


<img width="323" alt="Screenshot 2023-01-04 at 6 40 36 PM" src="https://user-images.githubusercontent.com/18622578/211123348-cf7f2519-c3f7-4368-9ebe-67bbac02c9ae.png">


Images of the homes available in the database are listed. The app displays the contract address and amount of home. It also provides an efficient and secure payment method with a validated transaction hash.

<img width="328" alt="Screenshot 2023-01-04 at 7 02 29 PM" src="https://user-images.githubusercontent.com/18622578/211123266-9a062d9d-ea0d-4c23-91e2-067623af548c.png">


<img width="1197" alt="Screenshot 2023-01-04 at 7 02 48 PM" src="https://user-images.githubusercontent.com/18622578/211123394-501dcde2-d2ef-4754-b6d5-3a21ffed01ff.png">



