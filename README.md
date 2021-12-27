## Splinterlands-Inventory-Bots-v2
Inventory Bot for Splinterlands for multiple account, using python selenium <br>
Bot is taking 3% of DEC and SPS on every transfer <br>

What bot will do are
  1. Claim SPS in all account
  2. Send SPS to Main account
  3. Send DEC to Main account
  4. Transfer cards to Main account

## Built With
This project is built with [Python3.9](https://www.python.org/downloads/)

## Operating System
The tool can be run on the following OS:
  1.  Windows (you can use the PowerShell)

# Installation
## Windows

1. Download and install [Git](https://git-scm.com/) and [Python3.9](https://www.python.org/)
2. Clone the repo: 

      ```sh
      git clone https://github.com/royruzaini/Splinterlands-Inventory-Bots-v2
      ```

3. Go to repo directory
      ```sh
      cd Splinterlands-Inventory-Bots-v2
      ```

4. Install the required libraries by running: 
      ```sh
      pip install -r requirements.txt
      ```

# configuration

Step#1<br>
DEC limit can set in ``.env`` file. <br>
Enter Splinterlands account credentials in the format (one account - one line) in creds.txt: <br>
<ul>
  <li><code>MainAccount,posting_key,active_key</code></li>
  <li><code>Account1,posting_key,active_key</code></li>
  <li><code>Account2,posting_key,active_key</code></li>
   <li><code>...</code></li>
</ul>

Step#2<br>
Download "chrome" driver. <br>
https://chromedriver.chromium.org/ <br>
Copy the <code>chromedriver.exe</code> to the bot folder.

# How to use

Before using, you should always update to the latest available version. You can do so by going into the Splinterlands-Inventory-Bots-v2 directory and executing the following command:

```sh
git pull
```

Go into the Splinterlands-Inventory-Bots-v2 directory and run the command with the file. Examples:

```sh
python InventoryBots.pyc
```

# Discord
<a href="https://discord.gg/53GF7P6BUN">Discord</a>

# Donation
If you enjoyed using the tool, any and all donations are welcome. You can donate through the Splinterlands app.

| Platform | Information |
|:---:|:---:|
| Splinterlands | Username: hikenbot91
