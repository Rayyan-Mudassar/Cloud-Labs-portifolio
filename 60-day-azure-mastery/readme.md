## Day 1:
I learned about Entra-ID and role assignments, the most important thing is to assign the roles directly to groups, I created a user and then I created a group, I added the user into the group and then assigned the reader role to the group, then I tried to create a resoruce through the user account and got this error:
![Error Message](images/access-error.png)
To solve this error I went back to my orignal account where I am the owner and assigned the Contributor role to the group, the roles inherited to the user and again I tried to create a resource and then it was successful:
![Deployment Successful](images/error-fix.jpeg)

