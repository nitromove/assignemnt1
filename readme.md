I used vagrant ssh to get into the linux vm terminal so I can run linux scripts, I also elevated user priviledeges using "su" command.
![Alt text](<elevate priviledge.PNG>)
I used Chage -E expiredate username to set the user to expire in two weeks.
![Alt text](<set expiry date.PNG>)
I used chage -d 0 username to prompt the user to change password on login
![Alt text](<prompt new password.PNG>)
I used useradd -G group username to add the user to a group
![Alt text](<add user to group.PNG>)
I created another that doesn't have home directory using useradd -M username
![Alt text](<-M user.PNG>)