# A World Top 10 Battlesnake in Python

This is a program that interacts with the Battlesnake API to compete in the online programming game/tournament 'Battlesnake', a game similar to snake, but with multiple snakes competing to squeeze the othere out of space, and where every snake is controlled by a program rather than by a human. This snake, Shodan, is hosted on Replit, and is ranked in the global top 10, as well as achieving an elite ranking in the global leaderboards and qualifying to compete for Europe and the UK, reaching the quarter finals of the Caster Cup 2022.  

Link to achievements- https://play.battlesnake.com/u/harrykavna/#achievements  
Link to snake on the website (where you can see stats and games)- https://play.battlesnake.com/u/harrykavna/shodan/

## How it works

The snake uses a DFS floodfill to search for areas with the most food, and a pathfinding algorithm to find the closest food or enemy snake. It evaluates what direction to go in based on its own size compared to other snakes and its health, as well as how many free spaces there are in each direction. When larger than an enemy, it will hunt it down and attack the head of the snake.

## Technologies Used

* [Python3](https://www.python.org/)
* [Flask](https://flask.palletsprojects.com/)


## Quickstart

To make your own snake and compete, the [Quick Start Coding Guide](https://docs.battlesnake.com/guides/getting-started) provides the full set of instructions to customize, register, and create your first games with your Battlesnake! While the guide uses [Replit](https://repl.it) as an example host, the instructions can be modified to work with any hosting provider. You can also find advice on other hosting providers on our [Hosting Suggestions](https://docs.battlesnake.com/references/hosting-suggestions) page.

### Prerequisites

* A free [Battlesnake Account](https://play.battlesnake.com/?utm_source=github&utm_medium=readme&utm_campaign=python_starter&utm_content=homepage)

---
