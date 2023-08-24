# Notes Bot 🤖📝

![Untitled-1](https://github.com/mishalshanavas/notes-bot/assets/70484516/4b57f440-e2ed-4614-9e1c-99463edeeb9d)


## Description

The **Notes Bot** project is an automated tool written in Python designed to enhance user engagement on Instagram by delivering personalized notification messages to a designated Instagram account at regular intervals. The bot generates notifications that incorporate the current time using clock emojis 🕐🕒 and prompts followers with thought-provoking questions, fostering interaction and audience engagement.

## Key Features 🚀

1. **Automated Engagement:** The Notes Bot streamlines user engagement on Instagram by delivering tailored notification messages to followers.

2. **Dynamic Time Display:** The bot composes notification messages that dynamically showcase the current time using clock emojis 🕒🕘, adding visual appeal to the content.

3. **Consistent Intervals:** Operating on a predefined time interval ⏱️, configurable via the `BASE_MINUTE_INTERVAL` constant, ensures followers receive notifications at uniform and predictable times.

4. **Interactive Questions:** Notification messages include stimulating questions ❓, creating a conversational tone that encourages followers to participate and engage with the content.

5. **Authentication Handling:** The project employs the `instagrapi` library to manage Instagram authentication. It automatically generates and stores authentication cookies 🍪, ensuring smooth login and interaction with the account.

6. **Customization Potential:** The project's modular structure facilitates easy customization of the bot's behavior, messaging strategy, and notification frequency to cater to specific project requirements.

7. **Countdown Timer:** To sustain anticipation, the bot showcases a countdown timer ⏳ that informs users when the next note📝 will be dispatched.

## Usage 🛠️
0. **Clone the Repo** `git clone https://github.com/mishalshanavas/notes-bot `

1. **Account Configuration:** Provide Instagram credentials (username and password) within the `USERNAME` and `PASSWORD` constants in `main.py`

2. **Customization:** Tailor the bot's messaging approach, interval timings, and notification content by modifying the relevant constants and functions.

3. **Execution:** Upon executing the script, the bot verifies the presence of existing authentication cookies 🍪. If absent, it creates cookies through the login procedure.  Use `python main.py` to start the script
    
4. **Note Dispatch:** The bot operates within an infinite loop ♾️, continuously monitoring the current time. It sends Note featuring updated content based on the current time and the defined interval.

5. **User Engagement:** Followers receive captivating messages that showcase the current time with clock emojis 🕓🕘 and incorporate interactive questions ❓. This fosters user engagement and interactions with the account.

**Note:** The Notes Bot project serves as a foundational code structure that necessitates further refinement and adaptation to ensure compatibility with potential updates to the Instagram API or the `instagrapi` library.
