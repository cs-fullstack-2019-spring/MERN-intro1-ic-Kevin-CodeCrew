## MERN Intro1 Practice

### Exercise 1:
#### Create a Node/Express backend
* Add an endpoint for ```/fantasyff/seeddata``` that will accept 3 parameters and create a new ```ffplayer``` object in the Mongo collection called ```FantasyFootballPlayer```. Add (at least) 3 player records. 
* Each ```FantasyFootballPlayer``` record should have the following properties ```ffp_position```, ```ffp_name```, and ```ffp_points```.
* Add an endpoint ```/fantasyff/players``` that will return all of the players from the database (NOTE: Displaying the raw JSON results you get back is sufficient)

#### Example Fantasy football positions and how many of each are allowed on a Fantasy Roster:
```
1 Quarterback (QB)
2 Running Backs (RB)
2 Wide Receivers (WR)
1 Flex RB/WR/TEs (RB/WR/TE)
1 Tight End (TE)
1 Placekicker (K)
1 Team Defense/Special Teams (D/ST)
6 Bench (BN)
```
