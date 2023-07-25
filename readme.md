<div style="color:#AAFFFF">
Fork and update to Walter-o's original code.

This will scrape and download cartriges (p8.png) from the lexaloffle BBS for PICO-8 games.

This is strickly to preserve the games that are available on the BBS.

Thanks to Walter-o for putting this together!

Update to the original code:
Fixed the downloadUrl to reflect the recent changes to the lexaloffle.com BBS.
During the scrapping process to look for the URL for the cart, I also have it grabbing rhe <TITLE> and apending it
to the begining of the file name. This really helped with the carts with 4233454.p8.png as a name.
Added verbose logging to a text file to catch errors and to see the last cartID downloaded.

To add:
I want to add a "resume" function so it will start with the last cartID it downloaded and continue on.
  

Install Process:

Step 1: Have python and pip installed<br>
Step 2 (optional): open a virtual environment<br>
Step 3: <code>pip install requirements.txt</code><br>
Step 4: Edit <code>start.py</code> to your needs<br>
Step 5: <code>python3 start.py</code><br><br>
