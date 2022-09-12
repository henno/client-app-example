Example project on how to create a client app for a REST API

Pivotal Tracker: https://www.pivotaltracker.com/n/projects/2594006

This project is a client application for reqres.in REST API and is meant to demonstrate how to develop client 
applications for REST APIs from the scratch.


How to:
1. Create a project in Pivotal Tracker
2. Create a repo in version control system (Github, Bitbucket, Gitlab)
3. Integrate Pivotal Tracker with version control system, so that whenever you commit, there will be a link to the commit under the story that the commit is linked to.
4. Create your first story to Pivotal Tracker: "As a user I can see a list of <item type>" where <item type> is the type of items your API is about.
5. Add tasks under the Pivotal story. Each task represents a criterion which all must be fulfilled in order to say that the story is "done".
6. Mark the story as started
7. Read the first task and only do the minimum required amount of coding in order to be able to mark the task as completed. Then mark the task as completed and move on to the next task until there are no more tasks. 
8. If it turns out that a step/criterion was not originally written down, add it to Pivotal before coding it.
9. In case you can't finish your user story before the end of the day, create a branch with the ID number of the user history as its name.
10. If you managed to code all in one go, commit your work using either the story title as the commit message and adding a link to the story at the end. (example: "As a user I can see a list of cars [Delivers #123456]" where the part in brackets is for automatically marking the story as delivered in Pivotal tracker and adding a link to the commit as a comment).
11. If you did not manage to code all in one go and you have to finish for the day, while being in the feature branch, commit using whatever you want that helps you to remember what it is that you will have to do next as the commit message
11. In case you commited to a feature branch, continue working and commiting using temporary commit messages until you finish the story. Then make a final commit to the feature branch (a good way to end the feature is to write "DONE" or something similar as the message of the final commit), switch back to the main branch and commit the feature branch changes as a single commit to the main branch.
12. Check Pivotal tracker that the story status has been changed to delivered and that the story has a comment with a link to the version control system.
13. Create the next story and repeat the steps from step 4.
14. Once you have covered all 4 operations (Create, Read, Update, Delete), you have completed this exercise.
 