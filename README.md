# pin_chanllenge

What it looks like and what it does:

# The PIN screen
In this screen, you simply have:
1. A number input field
2. A numerical keypad

The PIN screen  directly appear after the application is loaded & It prevents the user from going to the next screen unless the correct pin is entered.

The user is allowed to enter 4 digits only.

The application should verify the PIN automatically.

The correct PIN should be locally and randomly generated every time the PIN screen is loaded.

The PIN should be revealed to the user by swiping/scratching over the keypad buttons... as doing so will reveal a finger print, or a sign of some sort to show that these are the correct numbers.

IF a wrong code is entered: Plays a sound that resembles an error
IF a correct code is entered: Moves to the contacts screen

# The Contacts Screen
Once the pin code has been cracked... we head into the contacts screen:

A screen that contains a list of contacts.

Each contact card contains: i. Name ii. Number and iii. Image.

This should reflect the local contacts on the phone itself and then:

1. Send the total count of contacts to an API endpoint.
2. The endpoint will return a list of JSON objects where each object contains an image URL and boolean fields.
3. One of these objects resembles the pirate. Render the received images in the contact cards and color the pirate box with a different color.