# ryng-master.github.io
Ryng is a flash-card-based memory testing tool. It uses mathematical and psychological models to help you remember data efficiently and easily.

Requirements: mySQL

- To start Ryng:

> On Microsoft windows: Choose Start > All programs > Ryng Memory tool

The Ryng login window will appear with boxes for user credentials.

Hover your mouse over any icon/button to see what it does.

- To login to your Ryng account:

> Under the "mySQL password:" section: Type the password to your local mySQL connection. It should be the same password that you use to enter mySQL.

> Under the "Username:" section: If this is your first time or you want to create a new account, type a new username here. Later on you can enter this username to access your Ryng account.

> Click the Submit button. The login window will close and the main window will appear on the screen. 

- Using the main window:

> In the centre there will be an area with the headings "Decks", "Due" and "New". This is the treeview where all your created decks and information about them will appear. If you have no decks then this area will be empty. 
Otherwise you will see the names of decks, how many cards are due to be learnt and how many are new. You can right-click on a deck to rename/delete it.

> Above the main treeview of the decks, you will see 3 buttons representing a plus sign, a file with a magnifying glass and a light bulb/moon respectively.

On clicking the plus sign, the Add Cards/Decks window appears. This window will allow you to create decks and add cards to them. See "Using Add Cards/Decks window" for more information.

On clicking the files symbol, the Browse Cards window appears.This window allows you to browse all your created decks, cards, assign them flags, find cards by their names, flags, card state or find duplicates. See "Using Browse Cards window" for more information.

On clicking the lightbulb/moon symbol the theme of the program switches between light and dark mode. In light mode this symbol appears as a moon and in dark mode it appears as a lightbulb.

> Below the treeview, you can see two buttons labelled "Test all Cards" and "Test" respectively. You have to first select a deck that you want to test yourself with. Then click Test button if you want the program to test you using it's algorithm. Otherwise click Test all Cards button if you want to learn all cards. On clicking either option, the treeview disappears and cards start appearing to test you. See "Using test window" for more information.

> At the top right, you can see a red circle with 2 yellow arrows in it. This is the refresh button. Click on it to display the latest updated data in the treeview. Auto-refreshing takes place every few seconds anyway.

> At the top left, under the title "Main window", you can see a button labelled "Options". Click on it to open the Options menu. Here you will see 3 options: Clear data, Logout, Delete account. 

On clicking the Clear data option, all the data in your Ryng account is deleted, including information about your decks and cards. Your account still exists, just without any decks.

On clicking the Logout option, the Main window with the treeview closes and you are taken back to the login screen.

On clicking the Delete account option, your account with all it's data is lost and can't be accessed again. You are taken back to the login screen as in the Logout option above.

- Using Add cards/decks window:

> On the top left there is a button labelled "Choose Deck". Click on it to open a menu where you can choose a deck you have already created to add new cards to it or click on the "Add deck" option to create a new deck.

> When you click on the "Add deck" option, a text bar appears under the heading "Deck". Type the name of your new deck here. Then there are radio buttons below to select the intensity of learning (more or less intensive) and whether to allow reverse cards or not. Select your requirements for this deck. Then click on the Add option below to create this deck.

> When you click on an already created deck, 3 text fields appear under the headings "Front", "Back" and "Notes". Here type the text at the front of the card under "Front", the text at the back of the card under "Back" and extra notes under "Notes".
Once done, click on the Add option to add the card to the deck.

> Once done you can close the Add Cards/Decks window.

- Using Browse Cards window:

> A large window with many options appears on the screen. There is again a large tree-view with the headings "Front" and "Back". This is where all the cards with their fronts and backs will be displayed.

> On the left there are 3 text fields with drop-down menus:

> The first one is to choose a deck from the decks you created in this account. On choosing a deck, all the cards of that deck are displayed in the main treeview. 

> The second one is to sort cards by their flags (colours). On selecting a flag, only the cards of that flag (colour) will appear in the treeview.

> The third one is to sort cards by their state, either new or learning.

> There is also a search bar above the treeview where you can type the details of a card and it will display cards with matching search terms.

> There are 3 text fields below the treeview. When you select a card from the main treeview, it's details will be displayed here. You can change these by selecting a text field and typing new data.

> You can click the "Find Duplicates" button below this to find cards with the same data as the selected one.

> There are 5 options below the "Find Duplicates" button in different colours. You can select any one of these to assign a flag to your selected card.

> At the bottom of the screen there are 2 buttons representing "Save" and "Delete" from left to right respectively. Click on "Save" to apply the changes made above to a single card. Click on "Delete" to delete the selected card.

> Once done, you can close the Browse Cards window.

- Using test window:

> Once a testing option is selected, cards start flashing one by one, depending on the deck and option you have selected.

> The front of a card is displayed. You have to try and remember the information on the back of the card. Once you are sure, click on the cards symbol at the bottom to show the back of the card.

> On clicking the cards symbol, the entire card with all it's information is displayed to you, along with 5 options at the bottom rated from "Easy" to "Forgot". Rate yourself using these options based on how well you were able to remember the information on this card.

> Once you're done, click on the green arrow symbol at the bottom to go to the next card. All the cards selected by the computer will be displayed to you like this. If at any time you want to go back to the main window, you can click the red arrow symbol at the top. Otherwise the program will automatically take you back to the main window after completing all the ready cards. 

> In the main window, the decks are displayed with updated card information reflecting the changes after you have learnt a particular deck.

Happy remembering!
