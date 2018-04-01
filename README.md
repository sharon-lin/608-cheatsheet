# 608-cheatsheet
Shortcuts for MIT 6.08

## Inspiration

I was a bit tired of looking through the 6.08 website for instructions on how to do repetitive things, so I decided to log them all here. 

## REST API calls

Refer to [this gist.](https://gist.github.com/sharon-lin/78e2972794ff3ef3db80417a84833e45) 

## SFTP Calls

Run 

```
$sftp USERNAME@iesc-s1.mit.edu
```

Then type in your password.

## Transferring Files

Make sure the local directory you were in prior to SFTP contains the file you want to transfer (otherwise, you'll need to specify a path.) In your sftp console, enter the following. We'll use testo.py as our file name.

```
$put testo.py
```

You should receive the following

```
Uploading  to /home/USERNAME/DIRECTORY/testo.py
testo.py
```

You will be able to find your file at:
http://iesc-s1.mit.edu/608dev/sandbox/USERNAME/DIRECTORY/testo.py

Note that DIRECTORY corresponds to the directory you created within your remote directory (if you did). If you're in your remote root directory, it should just be:
http://iesc-s1.mit.edu/608dev/sandbox/USERNAME/testo.py

