Daş, Kağız, Qayçı (Rock, Paper, Scissors)
Overview
This is a simple web-based implementation of the classic game "Rock, Paper, Scissors." The user plays against an Android opponent, and the game keeps track of the user's score. The interface is designed with HTML, CSS, and JavaScript, and uses images to represent the different choices.

Features
User Interface: A visually appealing interface with images representing rock, paper, and scissors.
Random Opponent: The Android opponent makes random choices.
Score Tracking: The user's score is displayed and updated after each round.
Responsive Design: The layout adjusts for different screen sizes and devices.
Technologies Used
HTML5: Structure of the web page.
CSS3: Styling the interface, including custom fonts and button designs.
JavaScript: Game logic, including user interaction and score calculation.
Google Fonts: Custom fonts for a better visual appeal.
How to Play
Open the game in a web browser.
Choose between rock, paper, and scissors by clicking on the respective button.
The Android opponent will make a random choice.
The result (win, lose, or draw) will be displayed, and the user's score will be updated accordingly.
File Structure
index.html: The main HTML file that contains the structure of the game.
styles.css: The CSS file that styles the game interface (included within the HTML file for simplicity).
script.js: The JavaScript file that contains the game logic (included within the HTML file for simplicity).
Customization
Fonts
The game uses the following Google Fonts:

Pacifico
Russo One
MuseoModerno
Playfair Display
Milonga
You can change these fonts by updating the links in the <head> section of the HTML file.

Colors and Layout
To customize the colors and layout, modify the CSS styles within the <style> tags in the HTML file. Key elements to style include:

#sec and #komp for the player's and opponent's sections.
button for the choice buttons.
#xal and #xal1 for the score display.
Game Logic
The game logic is handled by JavaScript functions:

das(), kagiz(), and qayci() set the user's choice.
emel() generates a random choice for the Android opponent.
netice() determines the result of the round and updates the score.
Running the Game
To run the game, simply open the index.html file in a web browser. No additional setup or dependencies are required.

Contribution
Feel free to fork the repository and submit pull requests for any improvements or new features. For major changes, please open an issue first to discuss what you would like to change.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Thanks to Google Fonts for providing beautiful fonts.
Images are sourced from Imgur.
