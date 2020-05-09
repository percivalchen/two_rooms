# Two Rooms and a Boom - Role Distributor

## Welcome to the virtual version of "Two Rooms and a Boom"
This is a platform to distribute player roles for the game **Two Rooms and a BOOM** via email.
*This is NOT an actual platform for the game itself.*

## How Does This Work?
The game is meant to be played in person or virtually through a video conference call application like Facetime or Zoom.
(But you'll need to figure out how to share cards)

When you run the `main.py` application, the program will go through the `contact.csv` file and send an email containing the player's role and a jpeg of their card. 

### Requirements
* `python3` installed on your machine
* `two_rooms` repo downloaded

### Instructions:
1. Edit the `contact.csv` file to include each in the format `<name>,<email>`
  (We recommend a Google Form for to get contact info)
1. Edit `main.py`: Look for the variable `sender_email` and set it to the gmail address you widh to send emails from
1. Make sure that [allow less secure apps](https://myaccount.google.com/lesssecureapps) is ON
  (You might want to make a new gmail account for this since this is a security issue)
1. Run `python3 main.py` from your terminal in the `two_rooms` directory

## Misc
You can use this script to distribute roles via SMS. To do this, we use cell providers' [SMS gateways](https://en.wikipedia.org/wiki/SMS_gateway#Email_clients), so you will need to know the recipients' cell provider and number. The contact can then be added to `contact.csv` in the form `<number>@<gateway>`
  Ex: The number 1 (999) 123-4567 provided by verizon would be `9991234567@vtext.com`


IMPORTANT: Tuesday Knight Games (from http://tuesdayknightgames.com/) holds the copyright on the game "Two Rooms and a Boom" and it's roles. All designs have been made available under their Creative Commons license BY–NC–SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/). 

A big thank-you to Tuesday Knight Games for the creation of this fun game and for sharing their artwork designs.
