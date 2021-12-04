# !view_email
This command enables users to view their configured email address.
# Location of Code
The implementation for this command is available in [src/email_address.py](https://github.com/chandur626/TeachersPetBot/blob/8813e476d85caaffe034434daecf6461f353a792/src/email_address.py#L58)
# Code Description
## Functions
1. def view_email(ctx): <br>
This function is invoked when !view_email command is entered in the bot. Returns error if there is no active email configured against the user, returns the email address otherwise.

# How to run it? (Small Example)
Let's say that you join the server that has the TeachersPetBot active and online. All you have to do is 
enter the command '$view_email'.
```
!view_email
```
Successful execution of this command will display your email address and reverts with the success message through the bot. 

![!view_email](https://github.com/chandur626/TeachersPetBot/blob/main/data/media/email_address.gif)