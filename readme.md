
# 🤖 Fortune Tiger Bot

Ready to raise your stakes and maximize your winnings on Fortune Tiger? Our exclusive signal bot is your key to success! With real-time analysis, accurate tips, and tested strategies, you'll have everything you need to play with confidence.

#### Don’t waste any more time!

Join us and turn your bets into wins. Click the link below and start your journey to success on Fortune Tiger!

#### 👉 Start now!
##
## 🧠 Features

**Real-time Signals:** Get instant notifications with the best betting opportunities.

**Detailed Analyses:** Understand the reasons behind our recommendations and make informed choices.

All time settings and intervals can be customized, and messages can be personalized!

- ▶️ Telegram Integration
- ⚠️ Signal Alert
- 🚨 Signal Received
- ⏰ Opportunity Window
- ✅ Win Confirmation
- 🤑 Target Alert
- ⛔️ Loss Confirmation
- ✋ Bankroll Control
- 📈 Partial Report throughout the day
- 📊 Daily Report
- 🚀 Win Rate
- 🔥 Winning Streak
##
## 📦Installation

To run this project, you'll need to install **Python3.10** or higher.

After installing Python, you will need to set up a **Virtual Environment** on your operating system:


### Configuring CMD

Navigate to the project directory:
```
cd /path/to/your/project
```

Install the Virtual Environment (virtualenv):
```
python3 -m venv env
```

Activate the virtual environment:
```
env\Scripts\Activate.bat
```

Install the project dependencies:
```
python3 -m pip install -r requirements.txt
```
##
## ⚙️ Setting Up Environment Variables

To run the bot correctly, you need to configure some environment variables to ensure proper communication with Telegram. To access the values, look for the file ``` config.py ```.

Read the tables below to find the values to be filled in:

#### Telegram Settings

| Parameter   | Type       | Description                           |
| :---------- | :--------- | :---------------------------------- |
| `TELEFONE` | `string` | Phone number with country code (DDI) |
| `API_ID` | `int` | Telegram API key |
| `API_HASH` | `string` | Telegram API hash |
| `CHAT_ID` | `int` | Channel ID for sending messages |

#### Bot Settings

| Parameter   | Type       | Description                                   |
| :---------- | :--------- | :------------------------------------------ |
| `TAXA_DE_SINAL` | `float` | Signal sending percentage. **(0.0 - 1.0)** |
| `ESPERA_CONFIRMACAO`| `tuple` | Delay values in **seconds** **(min, max)**  |
| `FREQUENCIA_SINAL` | `list` | List of seconds to wait for the signal. **[20,40]**  |
| `TEMPO_SINAL`| `int` | Time in **minutes** for the betting window |
| `TAXA_DE_VITORIA`| `float` | Probability of winning. **(0.0 - 1.0)**|
| `MIN_SUPER_GANHO`| `int` | Minimum consecutive wins for the **Super Win** message |
| `MIN_JOGADAS`| `int` | Minimum plays in a round. |
| `MAX_JOGADAS`| `int` | Maximum plays in a round. |
| `FREQUENCIA_RELATORIO`| `int` | Time in **minutes** for the partial report |


##
## 👣 How to Use

First, create a channel that will serve as the communication and signal delivery medium on Telegram.

### Getting the Channel Code
Before running the bot, you need to obtain the channel code (chat ID) from Telegram. With the virtual environment active, execute the following command to list all active chats in Telegram:

```
python3 main.py "listChat"
```

## First Time Setup
When you run the project for the **first time**  in the terminal, you'll need to follow these steps:

#### Step 1:
- Enter your Telegram phone number in the format: ``` +55 99 90000-0000 ```
- Note: This must match the number in the ```config.py``` file.

#### Step 2:
- Enter the confirmation code sent to you via Telegram in the terminal.

Once you execute the command to list the active chats in Telegram, you will receive a list of chat names and their corresponding IDs:

#### Example:
```
Name: Jhon Doe
ID: 987654

Name: Signal Channel
ID: -123456

Name: chat4
ID: 654987
```
Copy the chat ID that will be used and insert it into the **```TELEFONE```** parameter found in the ``` config.py ``` (**⚙️ Configuration of Variables** ).

# 🚀 Finally
Run the bot using the appropriate command for your environment. Wait for real-time signal notifications to arrive directly in your Telegram chat!

```
python3 main.py
```


##
## 📞 Support

If you have any questions or need assistance, feel free to contact our team.

#### 🤝 Contributions

Contributions are always welcome! If you have any ideas for the project, don’t hesitate to reach out to us through our communication channel.