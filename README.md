# HOW-TO-SYNC-MSVS-WITH-GIT-

Open the solution in Visual Studio 2013
Select File | Add to Source Control
Select the Microsoft Git Provider
That creates a local GIT repository

Surf to GitHub
Create a new repository DO NOT SELECT Initialize this repository with a README
That creates an empty repository with no Master branch

Once created open the repository and copy the URL (it's on the right of the screen in the current version)
Go back to Visual Studio
Make sure you have the Microsoft Git Provider selected under Tools/Options/Source Control/Plug-in Selection
Open Team Explorer
Select Home | Unsynced Commits
Enter the GitHub URL into the yellow box (use HTTPS URL, not the default shown SSH one)
Click Publish
Select Home | Changes
Add a Commit comment
Select Commit and Push from the drop down
