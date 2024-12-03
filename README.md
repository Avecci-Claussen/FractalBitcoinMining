# FractalBitcoinMining
 Created on 03/12/2024 18:19 A telegram bot for mining Fractal Bitcoin Sats


# The LonelyBit Mining Bot

<p align="center"> 
  <img src="https://thelonelybit.org/images/TLB-Icon-TransBG.png" alt="The LonelyBit Logo" width="200"/>
</p>

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [User Interaction](#user-interaction)
  - [Getting Started](#getting-started)
  - [Main Menu](#main-menu)
  - [Mining Process](#mining-process)
  - [Balance and Earnings](#balance-and-earnings)
  - [Daily Bonus](#daily-bonus)
  - [Referral System](#referral-system)
  - [Withdrawals](#withdrawals)
- [Administrative Functions](#administrative-functions)
  - [Pending Withdrawals](#pending-withdrawals)
  - [Approving or Declining Withdrawals](#approving-or-declining-withdrawals)
  - [Broadcasting Messages](#broadcasting-messages)
  - [Viewing User Data](#viewing-user-data)
- [Data Storage and Management](#data-storage-and-management)
- [Security Measures](#security-measures)
  - [Anti-Bot Captchas](#anti-bot-captchas)
  - [Command Cooldowns](#command-cooldowns)
  - [Data Privacy](#data-privacy)
- [Limitations and Policies](#limitations-and-policies)
- [How to Use the Bot](#how-to-use-the-bot)
- [Conclusion](#conclusion)

---

## Introduction

The **LonelyBit Mining Bot** is a Telegram bot designed to simulate cryptocurrency mining. Users can mine virtual tokens, participate in daily bonuses, refer friends, and withdraw their earnings. The bot ensures fair play with anti-bot measures and provides robust administrative functionalities.

---

## Features

- **Mining Simulation**: Interactive virtual token mining.
- **Captcha Verification**: Ensure human interaction.
- **Balance Management**: View your token balance.
- **Daily Bonus**: Claim daily rewards for consecutive participation.
- **Referral System**: Earn rewards by inviting friends.
- **Leaderboard**: Track top miners.
- **Withdrawal Requests**: Request token withdrawals securely.
- **Admin Controls**: Manage user interactions and withdrawals.
- **Command Cooldowns**: Prevent command spamming.
- **Data Security**: Persistent and secure data storage.

---

## User Interaction

### Getting Started

- **Register**: Send `/start` to register and receive a welcome message.
- **Referral Code**: Use a referral code to earn a bonus for you and your referrer.

### Main Menu

The interactive menu includes:
- ⛏️ **Start Mining**: Begin a mining session (requires captcha verification).
- 📈 **Mining Status**: View your progress and statistics.
- 💰 **Check Balance**: Check your mined tokens balance.
- 🎁 **Daily Bonus**: Claim your daily reward.
- 🏆 **Leaderboard**: See the top miners.
- 🔗 **Referral Link**: Generate your referral link.
- 💰 **Withdraw**: Request a token withdrawal.
- 📖 **Help**: Access bot usage information.
- 🔗 **Buy TLB**: Purchase The LonelyBit token.

### Mining Process

1. **Captcha Verification**: Solve a captcha to start mining.
2. **Mining Session**: Sessions last up to 2 hours.
3. **Mining Rate**: Your rate increases with daily activity.
4. **Session Completion**: Earn tokens and improve your mining rate.

### Balance and Earnings

- Check your balance using the 💰 **Check Balance** option.
- View your total mined tokens.

### Daily Bonus

- Claim once every 24 hours.
- **Bonus Streak**: Increases with consecutive claims.
- **Missed Day**: Resets your streak.

### Referral System

- Share your referral link.
- Both you and your referrals earn bonuses.

### Withdrawals

- Use `/withdraw <amount> <your_fractal_bitcoin_address>` to request a withdrawal.
- Minimum withdrawal limits apply.
- Cooldown: One withdrawal every 24 hours.

---

## Administrative Functions

### Pending Withdrawals

- **View Requests**: Administrators can review pending withdrawals.
- **Details**: User ID, amount, and receiving address.

### Approving or Declining Withdrawals

- **Approve**: Confirm and process withdrawals.
- **Decline**: Notify the user and revert the balance.

### Broadcasting Messages

- Send announcements or updates to users.

### Viewing User Data

- **User List**: View all users with balances and statistics.
- **Admin Dashboard**: Comprehensive overview of activity.

---

## Data Storage and Management

- **SQLite Database**: Securely stores user data.
- **Tables**: Includes user info and withdrawal history.
- **Data Integrity**: Ensures reliable data handling.

---

## Security Measures

### Anti-Bot Captchas

- Solve captchas to start mining.
- Multiple failures may result in temporary locks.

### Command Cooldowns

- Prevents spamming by enforcing a cooldown period.

### Data Privacy

- User data is confidential and securely managed.

---

## Limitations and Policies

- **Mining Time**: Capped daily mining time.
- **Withdrawal Limits**: Minimum amounts and cooldowns.
- **Fair Use**: Suspicious activity may lead to restrictions.

---

## How to Use the Bot

1. **Register**: Send `/start` to register.
2. **Mine Tokens**: Use ⛏️ **Start Mining** to begin.
3. **Check Balance**: Monitor your earnings with 💰 **Check Balance**.
4. **Claim Bonuses**: Access 🎁 **Daily Bonus**.
5. **Refer Friends**: Share your referral link.
6. **Withdraw Earnings**: Use `/withdraw` for token withdrawals.
7. **Need Help?**: Use 📖 **Help** for guidance.

---

## Conclusion

The LonelyBit Mining Bot is your gateway to simulated cryptocurrency mining in Telegram. Engage with the community, earn rewards, and explore the bot's features for a fun and interactive experience. 🚀
