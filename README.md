# world-cup-2022-pool
contain datasets and scripts to track and report world cup pool performance 

With the 2022 World Cup just around the corner, I wanted to apply my learnings from CSE 6040 to a real dataset.My workplace is incredibly invested in Football/Soccer. Every year, we compete in a variety of Fantasy League games which include the English Premier League/EUROS/World Cup and more. This year, I reached out to our pool organizer (the person that collects each participants predictions and 'donations') if I could use the data and run several types of analysis.

After a stakeholder meetings, a few requirements were identified:

  1. Ensuring PII (personally identifiable information) info is encrypted and shared to the right users

  2. Find a data source to extract world cup group standings (trickier than expected)

  3. Calculate each participants group stage
  
  4. Report pool standings

Due to time/resource constraints, this notebook scope is limited to:

  1. Scraping Group Standings

  2. Calculating participant standings based solely on group stage results
