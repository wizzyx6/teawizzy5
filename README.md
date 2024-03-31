this is sniper bot for friendtech

Now you have 2 modes to run 
1) npm run manualSnipe => This is for manual sniping. You provide a user's address (from a monitor, check my github for the monitor setup), how many keys you want to snipe, and a delay time (in milliseconds) and the bot will start running and attempt to buy a user's key until it reaches max retries or the script is stopped by the user
2) npm run autoSnipe => This creates an in-house monitor that actively watches for new users, checks their Twitter metrics, and begins a snipe if it thinks its solid from a simple algo. Sends Discord notification when snipes starts, so you can cancel out if you want to. Everything is automated, but you should customize the code to your liking. You also run chmod +x restartScript.sh and then start the script with ./restartScript.sh if you want it to continuously run (24/7).

I understand the code/setup is not exactly new user friendly and pretty complicated, so if there is enough interest, I can make this very user friendly or answer any questions/bugs anyone has if I have time. The software worked very well for me, open-sourcing becuase I have to go back to work on other things and competition is high. Feel free to reach out to me @ imstefanstoll@gmail.com if you have any questions.

Disclaimer: Please interact with the software at your own risk, I am not responsible for any financial loss or any downside caused by it. I cannot guarantee any results from it. The software is not an offering from me. I share no responsibility for the usage and outcome of this now open-sourced software.
"# teawizzy5" 
