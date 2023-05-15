# When Was the Golden Age of Video Games

Video games are big business: the global gaming market is projected to be worth more than $300 billion by 2027 according to Mordor Intelligence. With so much money at stake, the major game publishers are hugely incentivized to create the next big hit. But are games getting better, or has the golden age of video games already passed?

In this project, we'll explore the top 400 best-selling video games created between 1977 and 2020. We'll compare a dataset on game sales with critic and user reviews to determine whether or not video games have improved as the gaming market has grown.

Our database contains two tables. We've limited each table to 400 rows for this project, but you can find the complete dataset with over 13,000 games on Kaggle.

game_sales
column	type	meaning
game	varchar	Name of the video game
platform	varchar	Gaming platform
publisher	varchar	Game publisher
developer	varchar	Game developer
games_sold	float	Number of copies sold (millions)
year	int	Release year
reviews
column	type	meaning
game	varchar	Name of the video game
critic_score	float	Critic score according to Metacritic
user_score	float	User score according to Metacritic
Let's begin by looking at some of the top selling video games of all time!

Project Tasks
1. The ten best-selling video games
2. Missing review scores
3. Years that video game critics loved
4. Was 1982 really that great?
5. Years that dropped off the critics' favorites list
6. Years video game players loved
7. Years that both players and critics loved
8. Sales in the best video game years
