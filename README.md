# FractalBitcoinMining
 Created on 03/12/2024 A telegram bot for mining Fractal Bitcoin Sats

The LonelyBit Mining Bot Documentation
<p align="center"> <img src="logo.png" alt="The LonelyBit Logo" width="200"/> </p>
Table of Contents
Introduction
Features
User Interaction
Getting Started
Main Menu
Mining Process
Balance and Earnings
Daily Bonus
Referral System
Withdrawals
Administrative Functions
Pending Withdrawals
Approving or Declining Withdrawals
Broadcasting Messages
Viewing User Data
Data Storage and Management
Security Measures
Anti-Bot Captchas
Command Cooldowns
Data Privacy
Limitations and Policies
How to Use the Bot
Conclusion
Introduction
The LonelyBit Mining Bot is a Telegram bot designed to simulate cryptocurrency mining within the Telegram platform. Users can mine virtual tokens, participate in daily bonuses, refer friends, and withdraw their earnings. The bot incorporates anti-bot measures to ensure fair play and provides administrative functionalities for managing user interactions and withdrawals.

Features
Mining Simulation: Start mining virtual tokens by interacting with the bot.
Captcha Verification: Anti-bot captchas ensure only human users can initiate mining sessions.
Balance Management: Check your current balance of mined tokens.
Mining Status: View your mining progress and statistics.
Daily Bonus: Claim daily rewards to boost your earnings.
Referral System: Invite friends using a unique referral link and earn bonuses.
Leaderboard: See the top miners in the community.
Withdrawal Requests: Request withdrawals of your virtual tokens.
Admin Controls: Administrators can manage withdrawal requests and broadcast messages.
Cooldown Mechanism: Prevents command spamming with a cooldown period.
Data Persistence: User data is securely stored using a SQLite database.
User Interaction
Getting Started
Registration: Send the /start command to the bot to register and receive a welcome message with navigation options.
Referral: If you have a referral code, include it when starting to receive a bonus for you and your referrer.
Main Menu
The bot provides an interactive menu with the following options:

⛏️ Start Mining: Begin a mining session after passing captcha verification.
📈 Mining Status: Check your current mining progress.
💰 Check Balance: View your balance of mined tokens.
🎁 Daily Bonus: Claim your daily bonus.
🏆 Leaderboard: View the top miners.
🔗 Referral Link: Get your unique referral link to invite friends.
💰 Withdraw: Request a withdrawal of your tokens.
📖 Help: Get assistance and information on using the bot.
🔗 Buy TLB: Visit the link to purchase the LonelyBit token.
Mining Process
Anti-Bot Captcha: Before starting, solve a captcha to verify you're human.
Mining Session: Upon successful verification, your mining session begins.
Duration: Each session lasts up to 2 hours.
Mining Rate: Starts at a default rate and can increase with consecutive mining days.
Mining Status: Check your mining progress at any time.
Session Completion: After the session, receive mined tokens, and possibly an increased mining rate based on activity.
Balance and Earnings
Checking Balance: Use the "💰 Check Balance" option to view your current balance.
Total Mined: The bot tracks the total tokens you've mined.
Daily Bonus
Claim a daily bonus once every 24 hours.
Bonus Streak: Increases with consecutive daily claims.
Missed Day: Missing a day resets your bonus streak.
Referral System
Invite Friends: Share your unique referral link.
Earn Bonuses: Both you and your referrals receive bonuses upon successful registration.
Community Growth: Encourages expanding the bot's user base.
Withdrawals
Requesting Withdrawal: Use the /withdraw command with the amount and your receiving address.
php
Copy code
/withdraw <amount> <your_fractal_bitcoin_address>
Minimum Amount: Ensure you meet the minimum withdrawal amount.
Approval Process: Withdrawal requests are sent to an administrator for approval.
Status Updates: Check the status of your withdrawal request.
Cooldown: Withdrawals can be requested once every 24 hours.
Administrative Functions
Pending Withdrawals
View Requests: Administrators can see all pending withdrawal requests.
Details: Includes user ID, amount, and receiving address.
Approving or Declining Withdrawals
Approval: Confirms the withdrawal, updates user balance, and records the transaction.
Declination: Notifies the user and returns the requested amount to their balance.
Broadcasting Messages
Communicate: Send messages to all users or specific users.
Usage: Ideal for announcements or important updates.
Viewing User Data
User List: View all users with their balances and total mined tokens.
Admin Dashboard: Provides an overview of total users, balances, and mined tokens.
Data Storage and Management
SQLite Database: Securely stores user data, including balances and withdrawal history.
User Table: Contains user information like ID, balance, mining rate, and timestamps.
Withdrawal History Table: Records all approved withdrawals.
Data Integrity: Ensures accurate and secure data handling.
Security Measures
Anti-Bot Captchas
Verification: Users must solve captchas before mining.
Timeouts: Captchas expire after a period, and multiple failures can lock the user temporarily.
Command Cooldowns
Prevention: Stops users from spamming commands.
Fair Use: Ensures equal opportunity for all users.
Data Privacy
Confidentiality: User data is kept private and secure.
Secure Handling: Sensitive information is managed responsibly.
Limitations and Policies
Mining Time: Daily mining time is capped to ensure fairness.
Withdrawal Limits: Minimum amounts and cooldowns apply.
Consecutive Days: Incentives for daily mining, with caps on bonuses.
Fair Use: Suspicious activities may result in restrictions.
How to Use the Bot
Start: Send /start to register.
Navigate: Use the interactive menu buttons.
Mine Tokens: Begin mining by solving the captcha.
Check Status: Monitor mining and balance.
Claim Bonuses: Use "🎁 Daily Bonus" daily.
Invite Friends: Share your referral link.
Withdraw Earnings: Use /withdraw when ready.
Need Help?: Press "📖 Help" for assistance.
