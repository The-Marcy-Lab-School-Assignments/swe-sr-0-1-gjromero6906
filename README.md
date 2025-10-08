# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

A good technical explanation often uses a metaphor to help others understand a complex concept. Choose a metaphor to represent a Git commit. 

In a few brief paragraphs, use your chosen metaphor to explain:
* What a commit is
* How a commit is created (include the command-line syntax)
* Why commits are useful in version control.
* Why it is important to write descriptive clear messages in team settings.

### Response 1
In my own words, a commit is like a bookmark for changes made within the code, and when it was made, like in a lecture, a 'snapshot'. So code can be accessed at any bookmark in a way we go back inside a book to remember a specific name, place, or even chapters we deemed important.

A commit is made like this 
git status <-- checks if we are aligned with our branch, so it compares the original code in the repository with the current code.
git add -A <-- tells us we want to save all the changes we made in this bookmark (stages) 
git commit -m "message"<-- makes the bookmark with its discription(why its a book mark ,finished adding another fuction,debbug a certain method and so on)
git push <-- saves and publishes said bookmark (it is saved in the repository)

Commits are used for version control because we can go back 'in time', for example, if code is not working as intended, we can go back to a bookmark where it was working and compare what changed to see what is missing or what was added that caused that break in the code.

Commit messages should be clear in a team setting because not everyone will be working at the same time, and not everyone will know where updates, debugging, or maintenance need to be directed. For example if the message is just 'finish debugging' and you have 5 .js files and 4 other files the team wont know which file was debugged or if you added new files and the message was "add jumpstart " where was it added why was it added is it a variable a fuction array, the more a commit is clear the less confustion there will be.
    