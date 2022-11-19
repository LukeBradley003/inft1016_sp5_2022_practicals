# Assignment 3 Webpage: Artifical intellegence in Transportaion

Name: Luke Bradley

Student ID: 110385890

Email ID: Bralc003

## Website contents:
This webpage is based off the first and second asssignment for this course which I had done on AI in transport. In the page you will find contents of mainly the second assignment in a article form with content simplified to make a quicker reading experience.  

## Functionality:
This webpage utilizes javascript to do 3 things toggle theme, set and save username, and change images

### Toggle Theme:
When the webpage is opened the javascript will check the the local storage for the last used theme and use it. If the toggle theme button is pressed a function will check the current theme and change it to the opposite one and then store into the local storage. If it's the users first time using the page the theme will be light by default.
### username set and save:
When the webpage loads the javascript will check querystring at the point where "user_name=" is and if there is a new username it will display it to the page. When a username is entered the above text updates to say "Hello username" without needing to exit and re enter the webpage. The last entered username before closing the webpage will also be saved to the local storage and will be displayed upon opening. 
### Change images:
Five different buttons can be found next to the headings on the page to be presssed and display different images and their photographers. This is done by using a function that reads a list of links and photographers to be accessed depending on which button is pressed.