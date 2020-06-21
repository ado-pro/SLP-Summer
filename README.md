# SLP-Summer

For this assigment, I went into the cumoja1/3320/ directory and copied over My Hunger Games.txt file into my submissions directory in /home/ado9/Submissions using the "cp My\ Hunger\ Games.txt /home/ado9/Submissions" command.
After successfully copying over the file, I went into my submissions folder and used the command "vi My\ Hunger\ Games.txt" inside the directory to start editing.
I searched up the character I wanted to replace and used the command ":%s/Gale/Austin/g" to replace all instances of Gale with Austin. I then saved the txt file by using :x command within the editor.

Also, as stated by the professor, we do not have the permissions to change permissions of certain groups and files so commands that I could have done to do this was:

chmod -R 750 /home/ado9/Submissions where groups is: 
eg-aff-faculty@gsuad.gsu.edu
*I can change the group of this directory by using:
chgrp -R eg-aff-faculty@gsuad.gsu.edu /home/ado9/Submissions

Changing owners:
chown -R cumoja1 /home/ado9/Submissions

