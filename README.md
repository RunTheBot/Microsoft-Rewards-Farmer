<pre align="center">
███╗   ███╗███████╗    ███████╗ █████╗ ██████╗ ███╗   ███╗███████╗██████╗ 
████╗ ████║██╔════╝    ██╔════╝██╔══██╗██╔══██╗████╗ ████║██╔════╝██╔══██╗
██╔████╔██║███████╗    █████╗  ███████║██████╔╝██╔████╔██║█████╗  ██████╔╝
██║╚██╔╝██║╚════██║    ██╔══╝  ██╔══██║██╔══██╗██║╚██╔╝██║██╔══╝  ██╔══██╗
██║ ╚═╝ ██║███████║    ██║     ██║  ██║██║  ██║██║ ╚═╝ ██║███████╗██║  ██║
╚═╝     ╚═╝╚══════╝    ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝╚═╝  ╚═╝
      Created by  Charles Bel (@charlesbel)  Updated by Alex V (@Alexy_Galaxy)   version 3.0
</pre>
<h3 align="center">

~ Use at your own risk, Microsoft may ban your account (and I would not be responsible for it) ~

</h3>
<h2 align="center">How to avoid getting banned</h2>

```
Do not run more than one account at a time.
Do not use more than one phone number per 5 accounts.
Do not Redeem more than one reward per day.
```

<h2 align="center">How to Install:</h2>

-Install zip from GitHub: https://github.com/AlexyGalaxy/Microsoft-Rewards-Farmer

-Install Python https://www.python.org/downloads/
	Select custom installation, change nothing hit yes until installed. 

```
-Open Microsoft-Rewards-Farmer-master, move requirements.txt to C:\Users\YOURNAMEHERE

-Open command prompt. win + R>CMD
type (without quotes and with a space after): 'cd ' 
drag the folder that contains requirements.txt into cmd
hit enter
type (without quotes): 'pip install -r requirements.txt'
Press enter

-Install Google Chrome.
```
-Windows
```
-Install ChromeDriver from https://chromedriver.chromium.org/downloads
	Place the file in X:\Windows (X as your Windows disk letter)
```
-MacOS or Linux :
```
apt install chromium-chromedriver
```
-or if you have brew :
```
brew cask install chromedriver
```

-Edit the accounts.json.sample with your accounts credentials and rename it by removing .sample at the end of the file name


-If you want to add more than one account, the syntax is the following:
```
[
    {
        "username": "Your Email",
        "password": "Your Password"
    },
    {
        "username": "Your Email",
        "password": "Your Password"
    }
]
```


-How to enable ErrLogger to obtain details on any Error that occurs
```
On line 20 delete the # from infront of rewardsErr and change YourNameHere to your pc's Username
To find your pc's user's name go to C:\Users
```


-How to enable Rewards logger to create a txt file when you have more than 6500 points for a $5 gift card.
```
On line 21 delete the # from infront of rewardsLog and change YourNameHere to your pc's Username
To find your pc's user's name go to C:\Users
```


-How to Disable Headless mode to watch the script work:

Set HEADLESSOFF = True
or
Comment out line 65 and 66 by placing a # in front of each line.
```
#if headless_mode : #comment out to disable headless mode (makes window visable)
#options.add_argument("--headless")
```

<h2 align="center">How to run Script:</h2>

	Double click on ms_rewards_farmer.py

<h2 align="center">How to make Script automatically close:</h2>

-Comment out the second to last line of code by placing a # at the start of the line

(If you do this you will not know if there was any errors)
```
#input()
```
