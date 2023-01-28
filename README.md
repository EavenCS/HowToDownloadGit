# How do I download git and configure an account?

### All commands must be entered in the CMD

1. First of all, visit the Git website. ```https://git-scm.com/downloads```

1. Download the latest version.

1. Go to the directory where you saved the Git exe file.

1. When in the target directory, click on the file and go through the exe

1. After you have done this, open the command prompt (CMD) and enter the command ```git --version``` to make sure that git has been installed.  

   ![image](https://user-images.githubusercontent.com/104131718/215278438-5b577737-928f-4cd3-b170-406293901f75.png)
   - If the current version is not displayed after the command, restart the PC.
   - After the restart, enter the command again.
   
 6. After you have downloaded Git, we will configure your Git profile, first of all, they set themselves a profile name. <br>
 ``` $ git config --global user.name "UserName" ``` <br>
 ![image](https://user-images.githubusercontent.com/104131718/215278923-9af0e3a9-b3fa-4965-8e2e-4edbf430b8c2.png)
   - With the following command you can check if the UserName would be entered
   - ```git config --global user.name``` <br>
   
7. Last but not least we configure the email address.
``` git config --global user.email johndoe@example.com```

   ![image](https://user-images.githubusercontent.com/104131718/215279470-34e88ff6-c050-48a1-a90d-0f999e2f34ab.png)
   
8. With the command you can check again whether the email address has been set. 
 - ```git config --global user.email```
### Now they have Git fully configured Bye :D


   


