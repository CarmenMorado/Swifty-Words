# Swifty-Words
Word game based on the popular indie game 7 Little Words. Users are going to see a list of hints and an array of buttons with different letters and need to use those buttons to enter words matching the hints. Throughout the course of this project, I familiarized myself with building a UIKit user interface programmatically,
the firstIndex(of:) and joined() methods, and property observers (didSet). 

In addition, I completed the following challenges:
-Use the techniques you learned in project 2 to draw a thin gray line around the buttons view, to make it stand out from the rest of the UI.
-If the user enters an incorrect guess, show an alert telling them they are wrong. You’ll need to extend the submitTapped() method so that if 
firstIndex(of:) failed to find the guess you show the alert.
-Try making the game also deduct points if the player makes an incorrect guess. Think about how you can move to the next level – we can’t use a simple 
division remainder on the player’s score any more, because they might have lost some points.

![ezgif-3-4a2ebd031b93](https://user-images.githubusercontent.com/42749527/101105279-1f85d680-359b-11eb-8ed1-6b17c4edcd06.gif)

