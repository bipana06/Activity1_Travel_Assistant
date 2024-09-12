## PPDS: Activity 1- Data Features

This file includes a description of a simple data feature that helps users, travelers especially, to find cheap flight options and convert the flight prices to their local currencies. Budgeting and planning are integral aspects of travelling. Hence, outside of the prototype converting flight costs to the local cost, users can also use this data feature to convert currencies based on the most recent currency exchange rates.

### Features
- Converts currencies as requested by a user based on the most recent exchange rates using the currencybeacon API.
- Searches for flight options to a destination for a particular date based on the user request using the amaDEUS API.
- Gives the user the 7 most cheapest flight options with the details about the flight duration, price (in local currency) and aircraft details. 

### Prerequisites

The following credentials are required to run the notebook:

- API Key for amaDEUS API. 
- Secret Key for amaDEUS API. 
- API key for currencybeacon API. 

### Usage
- Run individual cells in the notebook.
- When prompted for user input:
  1. For departure/destination, input the Airport Codes of the respective locations.
  2. When entering the travel class, make sure the input is capitalized.
  3. Finally, for the local currency, put the short form of the currencies, for example USD for Unided States Dollar. 





