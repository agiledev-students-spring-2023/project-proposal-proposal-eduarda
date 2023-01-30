# randomRGB

# Project Proposal - Web App

## Collaboration

TBA

### What and why?

randomRGB is a game that pairs up two random individuals- they're each then given some number of random color on the color wheel. For each color, the individual closest to guessing the red, green, and blue values wins a point for that color. Once both players have guessed for all colors, the player that has the most points wins. I would imagine that there would be a leaderboard for all players, that can be sorted or updated as people play and win points.

Knowing the RGB values for colors may be a useless skill, but it's definitely an interesting party trick. Even just getting close to knowing the RGB values is impressive to those who care. Like 2048, Snake, or other browser games, randomRGB would be a great way to pass time while challenging others and working on your RGB skills.

### For whom?

I'd imagine people familiar with development or design enough to want to play something like randomRGB competitively- like designers and developers. Or even just competitive people who like to play browser games like 2048 to pass time. This suggests that the design should be clean, since I imagine most of the players would be people who have a keen eye for implementation and design. It should also be reflective of the spaces and circumstances these individuals would be playing this game– calm, clear, and relaxing.

### How?

A description of what the system will do from an end-user's perspective. Be as complete as necessary to fully explain the system, but do not worry about technical implementation - this will be developed in subsequent work.

From the end-user's perspective: you can either chose to log in or not login. There would likely be some clear consequences for not logging in- perhaps you can't save your stats, and they can't show up on the leaderboard.

Once this decision is made, the user can either 1. find a player to challenge or 2. challenge a random player.

The user decides who to challenge, then they're given a colors, one at a time. For each color, they guess the RGB values, and after all colors are complete, they get their stats.

Then, the other player would see this challenge when they login. Then, they can play the player back.

The score is tallied and the winner is chosen. The win is logged for the winner, and the loss is logged for the loser. The leaderboard will be updated to reflect this.

### Scope

Some of the more complicated web-development related aspects of the projects can be fully ommitted, depending on the group members understanding of these aspects. Since no sensitive information is stored, I don't find it necessary to implement authentication beyond a username and a hashed password. If this part of the project is too ambitious, with many consequences, implications, and considerations, then even the signin/signup features can be fully ommitted- with more of an emphasis on the meat of the web app.

The meat of the project is the game interface and leaderboard, not its login features. The game interface (front-end) would require attention to detail, planning, and feedback from multiple group members. I'd also imagine we'd need a backend to interact with MongoDB and update the leaderboard and each player's wins/losses as games are played. Further, I think we could use TheColorAPI on the backend in order to generate random colors and their RGB values.

If not ambitious enough, then the signin/signup features and their consequences can be implemented. If still not ambitious, there are many ways to add features onto the meat of the game– leaving messages for your opponents, challenge your opponents with a specific color, or leaving messages for others to see (if your top 3 on the leaderboard).
