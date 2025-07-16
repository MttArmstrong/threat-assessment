---
title: 'Workshop 1: Agile Security Game'
---

## Introduction

It’s often difficult for developers to grasp what makes software security important, and how best to start addressing it.
Many experts agree that the best approach is to use a game.
The Developer Security Essentials package uses this game: The Agile App Security Game.
Teams of developers find it both fun and motivating as a way to start considering their own projects’ security and privacy requirements.


### Preparation in Advance - Face-to-Face

1. Calculate how many players you’ll have, and so how many teams of 3-6 players you’ll need.
2. Print the two side GamePlayerInstructionsPrinted.pdf sheet, one per player, preferably 2-sided.
3. Print from CardsFourToPage.pdf a set of task cards for each team, on A4 paper, one sided and ideally on light card (black and white is fine, colour better). Then cut them out, preferably with a guillotine (or see below).
4. Sort out cards in advance into individual mini-packs of a set of each (A, B, C, or D), according to the letters in the top right corner. Each pack has an additional ‘cover’ card. A packs have 8 cards; B, C, and D have 4 cards.
5. Optionally, you might like to get large flipchart sheets of paper for the teams to use as Kanban boards on the table, or arrange for a whiteboard for each team with blu-
tack to stick the cards there.

### Setup on the Day

6. Arrange the room with separate tables with 2-6 chairs around each table. Make there’s a piece of blank paper and pen for each team.
7. Set up a projector/display visible to all the players, showing the *DeveloperSecurityEssentials.pptx* presentation. Note that if no projector/display screen is available, you could use the option of reading out the content of the slides instead.
8. Sort out cards in advance into individual mini-packs of a set of each (A, B, C, or D), with cover. A packs have 8 cards; B, C, and D have 4 cards.

## Running the Workshop
The workshop has an introduction, up to four rounds, or ‘sprints’, and a wrap-up session.
Timings are approximate. Adjust them according to how the teams are getting on in each step.

TABLE 1: WHEN TO GIVE OUT CARDS

Tell the participants that they are taking the role of agile product managers for the MoneyZoom product; their role is to decide on the stories for the development team to tackle each sprint.
In the first couple of sprints each team will be able to complete 11 story points, using the Kanban board on their shared board.
Stories chosen from previous sprints will remain part of the product and available to mitigate attacks. Stories not chosen in a given sprint will remain on the backlog as candidates to be chosen in later sprints.
Optionally you might use the first PowerPoint slide.

Face-to-face: Organise the players into teams of 2-6 people, each team sitting at chairs around a table, as shown in Figure 1. 
Give each player a set of Player Instructions.

The workshop then proceeds in ‘sprints’. Each sprint is as follows.

### Sprints 1-4 (10-25 minutes each)

1. Copy/place new ‘cards’ as shown in Table 1 to each team’s table in the backlog area if possible (there may be more one set of cards to hand out). Note that you don’t take cards away at any point – cards that haven’t been used remain in the ‘backlog’ for future sprints.
2. **Online:** Send the participants into their breakout rooms
3. Have them then select their tasks to carry out by moving the selected cards to the ‘this sprint’ column on their table or otherwise choosing a set of cards.
4. Allow the players time to discuss and decide. Typical timings are as in Table 2, but depend on the teams. Remember the point of the game is to learn from discussion, not to win; if there’s a good deal of discussion taking place and time permits, allow
the teams longer.
5. **Online:** Then bring them back to a plenary session or
6. **Face-to-face:** Gain their attention.
7. Show the attacks for the corresponding sprint using the presentation (or read them out from the Attacks and Mitigations document). The teams see which attacks succeeded on them.

Teams sometimes ‘negotiate’ on whether their chosen mitigations would actually have prevented the events. 
We suggest you enter into the spirit of it, and accept anything reasonable.

### Wrap-Up (10 min)

Ask the teams to discuss what they feel they learned from the game.
Then either get a representative to report back for each, or (larger group) use an ‘open ended’ question on Menti.com to gather and share feedback (this can work even face-to-face).
You may like to explain some less obvious learning points (with the appropriate slide):
- The password tasks (EP – Complex Passwords, and CC – Credential Changes) conflict
with recent UK National Cyber Security Centre guidance, and have no benefit.
- Detecting Jailbroken devices (DJ) doesn’t really help with app security – few apps do it nowadays. Similarly Review of Server Code (RS) is rarely used.

### Some Notes about the Game

In a real world situation obviously one wouldn’t get feedback and lists of attacks before the start of the next agile sprint. 
If this worries you or the players, say that the ‘security enhancement’ sprints we’re doing here would actually be interspersed with a number of functionality sprints, allowing plenty of time for feedback before the next sprint.
Observe in the attack descriptions that in some cases the mitigations are alternatives: the first attack could be mitigated by either BS or PT. 
But in other cases the teams must have completed all of a collection of tasks to mitigate the attack.