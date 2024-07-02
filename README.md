# rugby-europe
This repository collates results from the top-tier European Rugby Champions Cup (previously known as the Heineken Cup or Heineken Champions Cup).
The repository contains all matches from the tournament's inception in 1995 and many of the headings are self-explanatory.
Information has been gathered from the Wikipedia pages for each season of the tournament.
Datasets are cumulative i.e. the most recent dataset will include all match results from the previous one.


**Defintions**

'Crowds' is a dummy variable indicating whether crowds were present at the fixture. Due to the Covid pandemic this has only recently been an issue.

'Neutral venue' is a dummy variable indicating whether the match took place at neither the Home Team or Away Team. Typically this only includes matches like the season final, but may also have included some matches affected by Covid.

**Limitations**

1) Tries scored per team: this is only available for the first handful of fixtures in 1995, and again since April 2021.
2) Scores after over-time: where a knock-out match finishes as a draw after 80 minutes, an additional 20 minutes is played to determine a winner. This data contains solely the scores after 80 minutes. For instance, the 2024 Final between Toulouse and Leinster (line 2002) finished 15-15 after 80 minutes but 22-31 after extra time. In this dataset it is recorded as 15-15 and a draw.
