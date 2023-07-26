<div style="color:#AAFFFF">

<h1>Fork and Update to Walter-o's Original Code</h1>

<p>The purpose of this project is to scrape and download cartridges (p8.png) from the Lexaloffle BBS for PICO-8 games. The primary goal is to preserve the games available on the BBS.</p>

<p>Special thanks to Walter-o for creating this code!</p>

<h2>Update to the original code:</h2>
<p>I have fixed the <code>downloadUrl</code> to accommodate recent changes on lexaloffle.com BBS. Additionally, while scraping for the cart's URL, I now also retrieve the <code>&lt;TITLE&gt;</code> tag and append it to the beginning of the file name. This proves especially useful for carts with names like "4233454.p8.png."</p>
<p>Moreover, I have added verbose logging to a text file to capture errors and track the last downloaded cartID.</p>

<h2>Upcoming Addition:</h2>
<p>I plan to implement a "resume" function that will start the download process from the last cartID downloaded, allowing for seamless continuation.</p>

<h2>Installation Process:</h2>
<ol>
  <li>Ensure that Python and pip are installed.</li>
  <li>(Optional) Create and activate a virtual environment.</li>
  <li>Run the command <code>pip install -r requirements.txt</code> to install necessary dependencies.</li>
  <li>Customize <code>start.py</code> according to your requirements.</li>
  <li>Execute <code>python3 start.py</code> to begin the process.</li>
</ol>
