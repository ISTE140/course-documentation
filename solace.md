# Using Solace as a Secondary Web Server

Even though will continue to use our class web server on Bluehost ([www.iste140.org](https://www.iste140.org/)), we will also use the private, RIT-only web server *Solace*.

## Step 0: SSH into your Solace Account

Today in ISTE-140 we logged into the server: *Solace* using SSH (at a command line).  Then, were were supposed to wait for some automatic scripts to do their thing so we could start using our Solace account to host webpages.  If you haven't already, follow the process (except for using mobaxterm...?) here: [How do I login to ist-solace.main.ad.rit.edu?](http://solace.ist.rit.edu/pages/how2login.html)

## Step 1: FTP into your Solace Account
The automatic process should be quite done by now so when you have a chance do the following:

- Using your FTP software, login with the following credentials

  Protocol: **SFTP** (not plain FTP this time), and port **22**
  Host name (or server name): **ist-solace.main.ad.rit.edu**
  Username: **\<your RIT username>**
  Password: **\<your RIT password>**

*See the attached screen shot from my WinSCP software...*![figure1](media\figure1.png)

Go ahead and save the settings (along with the password if you have that option) and then login.

You should see something like this...![figure2](media\figure2.png)

*Note: I login with faculty privileges, and I have my FTP software set to show hidden files.  You may be using different FTP software, and you may see other files and folders based on your student login.*

## Step 2: Add Webpages to Your "Webroot"

Your "webroot" is the folder where your website starts. (That'll make more sense as we go.)  

Get your **start.html** file from Lab 1 and using your FTP software, copy the file to the Sites folder in your Solace account.

## Step 3: Check Your Work in a Web Browser

Open a web browser tab and go to:

`http://solace.ist.rit.edu/~<ritusername>/start.php`
...where \<ritusername> is your RIT Username
...BTW, notice there is a tilde (~) right before your username! It needs to be there.



<hr>

That's it for now.  I'll check your handiwork later, but if it doesn't work or you have any problems don't hesitate to reach out for help in our #help channel in Slack.