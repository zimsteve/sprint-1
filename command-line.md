The command line is like talking directly to your computer using words, commands, prompts and requests, instead of pointing and clicking through the graphical user interface.


cd - "change directory".


cp - "copy a file".

mv - "move a file".


ls - "list files".


exit - "exit the command prompt".


touch - "made for modifying a file, but if the file doesn't exist, it will create it".


md or mkdir - "made a new directory/folder"


cat - "short for “concatenate”, and will output the contents of a file. It is best for smaller file sizes, as it displays the whole fine all at once".


less - "Less is a much better way to view large files on the command line. You’ll get a screen-full of text at a time, but no more. You can move a line up or a line down with the k and j keys respectively, and move a window up or down with b and f key respectively. You can search for a pattern by typing /pattern. When you’re done, hit q to exit the less viewer.


curl - "Enables you to download frameworks libraries, you'll often find yourself downloading these files as you work. e.g. "$ curl -O http://www.domain.com/path/to/download.tar.gz" The -O flag tells curl to write the downloaded content to a file with the same name as the remote file. If you don’t supply this parameter, curl will just display the file in the commmand line (assuming it’s text). Here's a neat tip that uses the shell's bracket expansion: "$ curl -0 http://www.domain.com/{one,two,three}.txt".


chmod - "change mode" - As a web developer you will need to change file permissions. There are three permissions you can set, and there are three classes that can receive those permissions. The permissions are read, write, and execute; the classes are user, group, and others. The user usually the owner of the file, the user that created the file. It’s possible to have groups of users, and the group class determines the permissions for the users in the group that can access the file. Predictably, the others class includes everyone else. Only the user (owner of the file) and the super user can change file permissions.


sudo - "super user do" - isn’t really a command like the others, but it’s one you’ll find a need for as you venture deeper into the command line world. Here’s the scenario: there are some things that regular users just shouldn’t be able to do on the command line; it’s not hard to break stuff. The only user who has the right to do anything he or she wants is the super user, or root user. However, it’s not really safe to be logged in as the super user all the time, because of all that power. Instead, you can use the "sudo" command to give you root permissions for a single command. You’ll be asked for you user account password, and when you’re provided that, the system will execute the command with super user permissions.


man - Most of the commands you’ll use in the command line are pretty flexible, and have a lot of hidden talents. If you suspect a command might do what you want, or you just want to see some general instruction on using a command, it’s time to check the man pages. Just type "man" followed by the command you’re curious about. e.g "man less"