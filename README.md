# custom-typing-practice
 Practice typing the characters you choose, randomly. A minimalist bare-bones web application.

# Introduction
This is an application that runs in the web browser. It is very simple written in HTML and Vanilla Javascript. I currently run it in Firefox v84.0.2. It works fine for me. I decided to share it in case it helps others learn Javascript or practice typing.

It is not very user friendly, nor is it well designed from the perspective of the user, but it has two features that some other online alternatives did not have.

# Background
I often type using keyboard layouts using dead-keys. This is because I often need characters in languages other than English, and also because I experiment with keyboard layouts somewhat. 

Some alternatives that I came across that allowed you to submit custom text had the following issues for me:
  - they ignored dead-keys. This made practicing typing with dead keys impossible with their web application.
  - they severely limited the character set to only Latin characters. This made it impossible to use their web application to practice typing in some other scripts.

Therefore, I made this web application to suit my needs. 

# How is the application able to handle dead keys?
It does not check every character typed in. It simply compares the text contents of two text areas. If they are similar up to a point, your input is correct, and it doesn't check the last two characters you typed, because often when typing a dead-key the current character you type has to be wrong before it can be right (i.e. before you finished the dead key combination).

