Organization
 has many players

League
 has many teams
 has many players
 
Bar
 has many teams
  string - name
  contact info

Team
 has many players
 belongs to league
 has a home bar
  string - name

Players
 has many leagues
 has many teams
 has many organizations
 has many games
  contact info (name, address, phone, email, etc)
  
Lineup
 date
 players
 
Games
 Has one player as winner
 Has one player as loser
  int - Loser Score

Match
 Has one home team
 Has one away team
 has home lineup
 has away lineup
 Has many games (16)
  round scores
