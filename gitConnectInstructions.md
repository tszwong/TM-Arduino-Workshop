# Brief guide: connect computer to your github repo<br>
## Step 1:<br>
cd into the .ssh directory on your computer with the following command:<br>
- cd ~/.ssh && ssh-keygen
<br>

## Step 2:<br>
- When prompted with "Enter file in which..." just hit enter<br>
- Enter "y" to overwrite<br>
- Hit enter when asked for passphrase
- Hit enter again
<br>

## Step 3:<br>
copy the newly created key to your clipboard with the following command:<br>
- cat id_rsa.pub | pbcopy
<br>

## Step 4:<br>
setting up git config info
1. git config --global user.name "REPLACE WITH YOUR GITHUB USERNAME"
2. git config --global user.email REPLACE WITH YOUR GITHUB EMAIL

check if info is correct
- git config user.name
- git confit user.email

if info was entered incorrect redo the commands 1 and/or 2
<br><br>

## Step 5:<br>
- create a repo in github
- under green code button copy the SSH
- use command git clone followed by the SSH you just copied
