# LB-Get-Twitch-Chatters-List &middot; [![follow us!](https://img.shields.io/twitch/status/sexyguchitv?color=blueviolet&label=twitch.com%2Fsexyguchitv&logo=twitch&logoColor=white&style=for-the-badge)](https://twitch.tv/sexyguchitv) [![buy me something!](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?hosted_button_id=YT3SGBZ8NP6TL) 
A plugin to get the chatters names on your twitch channel.

### How to Install
- :exclamation::exclamation::exclamation: **Download [this file](https://drive.google.com/file/d/1Q0aMc29CVsIJw1rQ0ki69BA9NEo4bjCL).**
- Move it to your LioranBoard `extension` folder.
- Start your `LioranBoard receiver`.
- Click on `Install Extension`.
- Select `GetTwitchChattersList` and your `tsl_transmitter`.
- Done :tada:

### Parameters
This extension currently have the following parameters:

- `channel_name`: the channel name of twitch live stream that you want to fetch the data.

All those data are sent to a stack called `TwitchChattersList` on `LioranBoard`.

### Caveat
- If you want to clear the stack before pulling it again, you need to add a `command` to clear the stack before pulling the data.
- A chatter isn't a viewer. You can check more on this at this [reddit post](https://www.reddit.com/r/Twitch/comments/757e6t/chatter_count_vs_viewer_count/).
- Twitch endpoint isn't update in real time, usually it takes between 3~5 minutes to update the data, so you'll probaly see some users that could have left your channel or you can not see some people that jsut joined your channel.

### Demo Deck
You can build a simple deck like this:
![image](https://user-images.githubusercontent.com/29884217/108074708-47d48b80-7048-11eb-9dee-215bcfa8e675.png)

That will populate your `TwitchChattersList` stack inside `LioranBoard`.

![image](https://user-images.githubusercontent.com/29884217/108074897-78b4c080-7048-11eb-8388-e0e1dbacf29f.png)
