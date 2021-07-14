# What this do?
This builds a cron script and keysend script based on the options you choose. The resulting script will automatically send sats on a recurring basis to a node of your choice.

No sats are sent until you run the generated script or add it to your crontab. 

# How do?

* Clone this repository on your node: 
  
```git clone https://github.com/m00ninite/recurring_donations.git .```
* Run:
  
  ```
  cd recurring_donations 
  ./blitz.recurringpayment.sh
  ```
* Follow on-screen instructions

# Why no work on my node?
Bug @m00ninite on Telegram in https://t.me/raspiblitz and maybe we can work out why it's broke. I only have a Raspiblitz to test on, so if you are able to test on another node package, please help me out!
