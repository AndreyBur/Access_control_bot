# How to run Access control bot

## 👋 Introduction

This bot will help you set up access to your group via NFT.

## 🤖 creating a bot

Create a bot in [BotFather](https://t.me/BotFather), then take the token and paste it into the appropriate field in the file [config.py](https://github.com/AndreyBur/Access_control_bot/blob/master/config_example.py) and also insert your bot's id in the corresponding field.

### ⚙️ Setting up the bot

Set up in [BotFather](https://t.me/BotFather) > `Edit Bot` > `Edit Commands` and we write this:

`add_admin` - add an admin to manage NFT
`remove_admin` - remove admin
`add_nft` - add an NFT for access to the group
`remove_nft` - remove NFT
`show_nft` - show all the NFT for access to this group
`help` - my telegram contacts if you have any problems with bot

## 🖥 Running Access control bot

1.  Before launching this bot, you need to clone the repository:

```bash
git clone https://github.com/AndreyBur/Access_control_bot
```

2.  Then download all the necessary libraries:

```bash
pip install -r requiments.txt
```

3.  Сreate a group and add a bot there and promote him to admin.

#### That's all, you can run the bot.

## 📌 References

- Author: [Andrew Burnosov](https://github.com/AndreyBur) (TG: [@AndrewBurnosov](https://t.me/AndreyBurnosov))

Developed for footsteps Developed for footsteps [#215](https://github.com/ton-society/ton-footsteps/issues/215) from TON Footsteps.
