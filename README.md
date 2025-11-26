<img src="src/main/resources/static/img/logo.png" alt="Airplane Logo" width="75" style="border: 1px solid black; border-radius: 10px;"/>

## 1. Project Description

**LLTactics** is a medieval fantasy web game inspired by the autochess model. In it, players compete for victory by strategically buying and upgrading characters and items. [Video](https://youtu.be/YKqZMBXW_r0)

This is a full-stack Java project that leverages Spring Boot, CSS, and JavaScript to create an interactive multiplayer gaming platform. Using socket-based communication, the application allows users to connect in real-time, play games, and experience seamless interaction between the client and server. The project demonstrates both back-end and front-end development skills, including real-time data handling, user interface design, and integration of modern web technologies.

Matches are played in two alternating phases:

- **Purchase Phase**: Players can spend stars to acquire units and items, refresh the shop, assign items to their units, or remove elements from their inventory (via double click).
- **Battle Phase**: Teams automatically fight until only one side has surviving units. The losing player of the round loses health points. The game continues until one of the players reaches zero (or fewer) health points.

LLTactics features an automatic matchmaking system. Additionally, matches include an integrated chat system so players can communicate in real time, as well as a report button to denounce inappropriate behavior and maintain a healthy community.

Players can also access different informational and social views:

- **Item and Hero Gallery**: Shows all heroes (sorted by factions) and items available in the game, along with their stats and detailed descriptions.
- **Ranking**: Displays the top players on the server, including their most notable statistics. This view is dynamic and allows clicking on each player to access their profile.
- **Rules**: Clearly summarizes the game rules to help both new and veteran players understand its mechanics.
- **User Profile**: Shows personalized information such as the player’s favorite faction, most used character, mastery points, and win/loss percentages.

Administrators have exclusive views and tools for managing the game environment:

- **Match and User Management**: Allows reviewing ongoing or finished matches, banning users in case of misconduct, and unbanning them.
- **Game Constants Modification**: Ability to adjust initial match parameters such as economy, base health, or other key factors.
- **Content Management**: A dedicated view to add, modify, or remove heroes and items available in the game, maintaining balance.



## 2. How to Use

On the home screen, credentials can be entered to log in as:

- **Test Administrator**:

User: <code>a</code>

Password: <code>aa</code>

- **Test User**:

User: <code>b</code>

Password: <code>aa</code>

**Note** - We were unable to perform match-related tests because Karate does not support two drivers simultaneously. Nevertheless, we conducted external tests for all other functionality.


## 3. Credits

**DEVELOPERS**

- Samuel Carrillo
- David Cendejas
- Sandra Sanz
- Iván Toribio
- Javier Martín

**ART**
- The unit and item images come from the game [Battle for Wesnoth](https://github.com/wesnoth/wesnoth/tree/master), which are licensed under the GNU General Public License (GPL).
- The remaining decorative images were generated with ChatGPT and later adapted.
- The fonts used in the titles were obtained from Google Fonts.
- The icons come from the Bootstrap Icons set, under the MIT license.
