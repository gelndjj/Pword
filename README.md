[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z6KMSBT)

# PWORD
_Pword is an Encrypted Password Generator written in Python._

```
 ____                               __     
/\  _`\                            /\ \    
\ \ \L\ \__  __  __    ___   _ __  \_\ \   
 \ \ ,__/\ \/\ \/\ \  / __`\/\`'__\/'_` \  
  \ \ \/\ \ \_/ \_/ \/\ \L\ \ \ \//\ \L\ \ 
   \ \_\ \ \___x___/'\ \____/\ \_\\ \___,_\
    \/_/  \/__//__/   \/___/  \/_/ \/__,_ /
```
### SUMMARY
Pword generates passwords and Encrypt/Decrypt them using the Fernet module.
### SCREENSHOTS

![Screenshot](https://github.com/gelndjj/Pword/blob/main/img/main.png)

![Screenshot](https://github.com/gelndjj/Pword/blob/main/img/main2.png)

### HOW IT WORKS 

####  GENERATE AND ENCRYPT
##### By default, a password (lenght 12) is generated, you can generate another lenght by changing the value or write your own password.
###### Once the password is generated click on **Encrypt**, Pword then creates three files, one is a text file containing the encrypted password, the second is the *.key that is a crucial file to decrypt the encrypted password and the last one is a zip file containing both files previously quoted. The two files (.key and .txt) will be available in the combobox fields (as well as inside the directory where the script is launched) above the Decrypt button.

![Screenshot](https://github.com/gelndjj/Pword/blob/main/img/files.png)

#### DECRYPT
##### When you encrypted a password, the generated .key and .txt files are named by the current time (YYY-MM-DD-HHMMSS) **from when you clicked on the Encrypt button**.
###### Select the same .key and .txt (same name) and click on **Decrypt**. The password will be shown in the first field. The password is automatically copied to the clipboard by clicking anywhere in the text field.

![Screenshot](https://github.com/gelndjj/Pword/blob/main/img/decrypt.png)

#### SEND ENCRYPTED PASSWORD BY EMAIL
###### Clicking on the **Send button** will open a filedialog where you can choose a zip file (that contains both key and text files), then the application MAIL (OSX) will be launched with the zip file attached to a new email. Write the mail of the person you want to send to and click on send.

![Screenshot](https://github.com/gelndjj/Pword/blob/main/img/send.png)

### REQUIREMENTS INSTALLATION
```
pip install -r requirements.txt
```
### CLONE REPO
```
git clone https://github.com/gelndjj/Pword.git
```

