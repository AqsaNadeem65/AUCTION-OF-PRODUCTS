# AUCTION-OF-PRODUCTS
Interactive Auction Board System
The Interactive Auction Board System is a C++ program designed to simulate an auction environment for a fictional auction company. This program provides functionalities for both sellers and buyers to interact in an auction setting.

Features
Auction Set Up: Sellers can add items to the auction by providing essential details such as item numbers, descriptions, and reserve prices. The program enforces a minimum requirement of 10 items to start the auction.

Buyer Bids: Buyers are able to participate in the auction by placing bids on items of interest. To place a bid, buyers specify their unique buyer number, the item number they wish to bid on, and the bid amount. The program ensures that bids are higher than any existing bids to maintain fair competition.

End of Auction: Upon concluding the auction, the program evaluates the results. It identifies items that have met their reserve price, marks them as sold, calculates the auction company fee (which is set at 10% of the final bid), and displays the total fee generated from sold items. Additionally, it presents information about items that did not meet the reserve price, items with no bids, and items that were successfully sold.

Usage
To utilize the Interactive Auction Board System, follow these steps:

Compilation: Compile the main.cpp file using a compatible C++ compiler.
Execution: Run the compiled executable.
Operation: Interact with the program through the provided prompts to set up auction items, record bids from buyers, and conclude the auction to view the results.
NOTE:
Buyers can place multiple bids on the same item, and the program will maintain the highest bid for each item.
The program calculates a 10% fee for items successfully sold based on the final bid amount.
