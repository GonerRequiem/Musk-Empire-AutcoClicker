[sadsad](https://github.com/)
# Musk Empire AutoClicker

![vs](https://github.com/user-attachments/assets/2d34c258-7c96-458c-9267-ebd0f559b3eb)




## Functionality
| Feature                               | Supported  |
|---------------------------------------|:----------:|
| Multithreading                        |     ✅     |
| Binding a proxy to a session          |     ✅     |
| Sleep before run each session         |     ✅     |
| Claim daily grant                     |     ✅     |
| Claim reward for friends              |     ✅     |
| Claim reward for completed quests     |     ✅     |
| Claim offline bonus                   |     ✅     |
| Automatic taps                        |     ✅     |
| PvP negotiations                      |     ✅     |
| Daily quiz and rebus solution         |     ✅     |
| Investing in funds (combo for profit) |     ✅     |
| Docker                                |     ✅     |


| Option                  | Description                                                       |
|-------------------------|-------------------------------------------------------------------|
| **API_ID / API_HASH**   | Platform data for launching a Telegram session                    |
| **TAPS_ENABLED**        | Taps enabled (True / False)                                       |
| **TAPS_PER_SECOND**     | Random number of taps per second (e.g. [20,30], max. 30)          |
| **PVP_ENABLED**         | PvP negotiations enabled (True / False)                           |
| **PVP_LEAGUE**          | League in negotiations (e.g. bronze)                              |
| **PVP_STRATEGY**        | Strategy in negotiations (e.g. random)                            |
| **PVP_COUNT**           | Number of negotiations per cycle (e.g. 10)                        |
| **INVEST_AMOUNT**       | Amount to invest in funds (e.g. 1400000)                          |
| **SLEEP_BETWEEN_START** | Sleep before start each session (e.g. [20, 360])                  |
| **ERRORS_BEFORE_STOP**  | The number of failed requests after which the bot will stop       |
| **USE_PROXY_FROM_FILE** | Whether to use proxy from the `proxies.txt` file (True / False)   |

You can obtain the **API_ID** and **API_HASH** after creating an application at [my.telegram.org/apps](https://my.telegram.org/apps)

**PvP negotiations** are disabled by default. Enable at your own risk. Upgrade your negotiation and ethics skills to win in case of a tie. The default strategy is randomly selected for each negotiation. If you wish, you can specify your own strategy, which will be used **in all** negotiations. League names for the **PVP_LEAGUE** parameter: `bronze`, `silver`, `gold`, `platina`, `diamond`. Strategy names for the **PVP_STRATEGY** parameter: `aggressive`, `flexible`, `protective`. The **PVP_COUNT** parameter determines the number of negotiations the bot will conduct in one cycle (the bot performs all actions, then sleeps for an hour, which is the recurring cycle).

The answer to the **daily quiz** and the list of funds with guaranteed profits for **investing** are loaded from a [json file](https://alexell.ru/crypto/musk-empire/data.json) on my website. I will try to update the data daily so that all your deployed bots can perform these actions and earn additional profit. When investing, the bet amount will always be the maximum, as the profit is guaranteed. If there is not enough money for the maximum bet, the bet amount will be reduced.

