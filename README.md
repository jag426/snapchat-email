# snapchat-email
Snapchat bot that forwards every snap it receives as an email attachment.

Depends on [SnapchatBot](https://github.com/agermanidis/SnapchatBot). 

#####Usage
If you're sending from Gmail's SMTP server:

<code>python2 snapchat-email.py -u snapchatusername -p snapchatpassword -eu googleaccount@gmail.com -ep googlepassword -t recipient@email </code>

If not, you can specify a server with <code>-s serveraddress</code> and a sender address with <code>-f sender@email</code>.

###Coming Soon
Sending snaps via email
