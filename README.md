# PHP-Blind-Command-Injection
One project from me to learn ethical hacking. Its considered as a easy challenge to spot a blind command injection.

The idea behind this challenge, if you dont want to find it on your own:

The user data (username and password) you type in gets saved on a text file, named with the username.
When you type something in two times, you get a message, that these data allready exists in the text file.
So, we know a) the data gets saved in a text file and b) its a windows machine through the output formation.
So there is maybe a command that gets executed, to save a file on the backsystem with these data, maybe this can get manipulated.

One Solution: username: anything & ping google
              password: .com
              
In the textfile, the output gets saved from this command.
