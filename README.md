AutoTornAdd
===========

Bash script for adding users to Tornado SVN

Made for use at work, with purpose of speeding up the process.

What it's supposed to do is open folder containig various files which represent
different projects, and hold usernames and their hashed passwords, then prints the list of those
files on screen with numbers assigned to them, and prompts the user to select the project to edit.
Then asks for new username, checks if it doesn't already exist in selected project, then
generates random (urandom) password, and using htpassword generates hash and writes it to te project file,
so the user can now login with newly created credentials.

That's in theory :)