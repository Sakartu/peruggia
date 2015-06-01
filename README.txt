
Installation:

 - Open the "conf.php" and supply your...
    - database details, (ie... host, username, password)
    - Peruggia root directory
 - Near the botom under "Vulnerabilities" set up what you want Peruggia to be vulnerable to.
   - Please note that these are REAL vulnerabilities and do have the potential to leave your
     system vulnerable to attack.  Be very careful what you enable, taking into consideration
     the cost of something being compromised.  If you can do it, so can a cracker
 - Start up your favorite web browser and run "install.php".
   - Please note that Internet Explorer doesn't display Peruggia very well.  I will work on
     this in future versions, but spening time to help Microsofts pitiful products work right
     is not really high on my agenda.
 - Log in and upload some pictures if you want a little more realistic feel.
   - The default username and password is, of course, Username:'admin' Password:'password'
   - You can add more users and change the default password under the "Account" tab.


Use:

 - None of the vulnerabilities in Peruggia are indexed in an attempt to make your experiance
   a little more realistic and prevent cheating.  ;)  However... Should you like to know
   what the attack vectors are, feel free to open up the source code and look for places 
   where there is a check on one of the 'enable/disable' vulnerability options.  These are
   likely locations.
 - SPECIAL NOTE: for several of these vulnerabilities to be exploitable, you may need to 
   edit your "php.ini" file to, say... turn off magic quotes (SQLi), or allow url includes (RFI).
   If you start getting error messages this would be something to consider.


Get Involved:

 - If you are interested in joining my project, please contact me through sourceforge and let me
   know how you can help.  I would love to expand the project.
 - If you find a vulnerability I didn't catch, (not able to be disabled), CONGRATULATIONS!
   Please let me know about it, you will recive full credit for the find in the next version.
 - If you know of more educational material that you think should be added to the "Learn" section,
   tell me and I will consider adding it in.


Greetz:

 - Slappywag
 - Doomchip
 - Bolo


Hope you enjoy Peruggia!
Andrew

