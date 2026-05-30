# Teamfight Manager 2 Better Database

### What is this?

This is a Data Set that will make your game feel more realistic, with Teams having their iconic players, and legendary players having stats that more accurately represent their skillset.

Because of the drastic region imbalance in the League of Legends pro scene, the concept of this Data Set is an alternate reality where this game is the main  Esport that every major Esports Org participates in (eg. Europe gains their Counter-Strike players, North America and Japan gain their Fighting Game players)

Because SEA is missing in the game and Japan has the least major Esports teams of the provided regions, SEA and Japan were combined.

### Why github?

As Teamfight Manager 2 is updated and new features are added to the database editor, I will continue to update this data base to increase accuracy and balance where possible. You will be able to easily find and download the latest version of my database in the releases tab of this repository. 

### How are Players assigned to Orgs?

Because the game begins in 2026, Player ages and current team assignments are accurate to May 2026. Because most regions include more Orgs than are in the League of Legends circuit (eg. Spirit being in the EU Div 1) and the nature of Academy teams being that Orgs can easily promote Academy players to their Div 1 roster (eg. Smash on T1 in 2025), Orgs include their main and academy rosters, while Div 2 includes lower tier modern Orgs and high tier disbanded Orgs.
Retired players are usually assigned based on their last active Org, however some Orgs get players from their most iconic roster.
Some really old school players are assigned as coaches/analysts when applicable (eg. BoxeR on T1)
This will cause some Orgs to be naturally stronger, however if you play out the trading period, it should balance things out more. This imbalance is also inherent to the current version of Teamfight Manager 2, with your starting Region and Team acting as a secondary difficulty setting.
Of course, you can always create your own custom team to replace any of the default teams.

### Will the database be updated to match the eSports landscape 2027 and beyond?

There will be branches in the future that are up to date with the spring of each year. The official database will still be the 2026 version, with Org assignments and Player ages remaining unchanged. Alternate versions will be labeled 2027, 2028, 2029 etc. 

If interest is shown, I may also create retro branches to hilight the forgotten stars of metas that have passed.

### How is Player strength calculated?

In general, MOBA prowess is valued highest for a balanced skill set. Fighting Game and RTS players have high technical speed and skill, but low Team synergy stats, while FPS players have high team synergy and aim, but low game knowledge.

League of Legends players were compared to all other players in their role in a giant spreadsheet.
Monster Kills was calculated using CS/min and CS advantage at 15 minutes.
Skill Hit was calculated using DMG/min.
Roaming was calculated using Kill Participation.
Aggression was calculated using first death of the game %.

Region and Division were factored in through the following multipliers:
Korea Div 1 100%
China Div 1 95%
Europe/NA Div 1 90%
Korea/China Div 2 85%
SA/Japan/SEA Div 1 80%
Europe/NA Div 2 70%
SA/Japan/SEA Div 2 60%
Players that were in multiple regions/divisions for a significant amount of time used the average (eg. Nemesis 80%, Poby 87.5%)
This multiplier is also the default for each players Judgement stat, with specific exceptions for players who perform above their regions expectation (eg. Caps, Inspired, Levi).

Some stats like Ego are very hard to accurately judge, but I tried to include as much lore as I could (eg. TheShy famously disobeying his coach)
Some stats were also manually set based on lore as well (eg. Rekkles having a min Aggression score, Hylissang having a max Aggression score)

### Why doesn't Faker have the max score in every stat?

I am judging stats based on overall career, and current opinion of the community when stats aren't available. A player like Faker is considered the GOAT of LoL, but is more of a Jack of All trades especially at this point in his career. His greatest strength is resilience, with T1 consistently performing above expectation under pressure. Because of this, I set his Focus, Mental and Judgement to max, while allowing players like Chovy, s1mple, and SonicFox to outshine him in stats that represent their respective dominance in specific skills. Of course, you can always edit values you disagree with, these are just the stats I gave the players based on my limited knowledge.

### How is a non-MOBA player's role assigned?

Vibes :)
Fighting Game players are often Top laners because it is the most like a 1v1.
FPS players are often Bot laners if they're known for their accuracy and 1v5 clutches, Mid laners if their known for being an IGL, or Supports if they're known for Util usage or playing dangerous positions that give the team info.
Happy is a Jungler because Warcraft III is all about creep camps.
For some players I had a specific champion in mind (eg. HungryBox is a Jungler because Ghost chomps, and is round and floaty).

### How is Team wealth, popularity and performance level calculated?

Because you are not allowed popularity or performance level, these were assigned to the best of my ability, factoring MOBA performance highest, but Orgs like Vitality and Furia who have good MOBA teams and some of the Strongest CS2 teams are rated much higher than middle of the pack Orgs that only have a LoL team.
Team wealth is mostly based on real life success of Orgs, however some liberties were taken for balance and logistics. Teams with high player counts need a higher Salary Budget, but if they have a large amount of strong players on the starting roster, their Transfer Budget was significantly nerfed so that they will need to trade away some of their strong players to recruit new players.
In each region the ranges of wealth is
Div 1 KR/CN/NA/EU = Wealthy - Stable
Div 1 JP/SA, Div 2 KR/CN/NA/EU = Wealthy - Unstable
Div 2 JP/SA - Unstable - Poor

### Why are Player salaries innaccurate?

The current version of Teamfight Manager 2 does not me to directly edit player salaries, and adding new players seems to have a limit of 120k salary. I have tried to assign high earning and highly valued players the highest salaries on each base roster, but for rosters with many legendary players, it is impossible to give them all accurate salaries. 

This issue will be resolved and
