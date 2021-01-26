# Investigating Fandango Movie Ratings

In October 2015, a data journalist named Walt Hickey analyzed movie ratings data and found evidence that suggests Fandango's rating system was biased and dishonest. He found a significant discrepancy between the number of stars displayed to users and the actual rating;

- The actual rating was almost always rounded up to the nearest half-star, a 4.1 rated movie would be rounded off to 4.5 stars and not rounded down to 4.
- In 8% of the ratings analyzed, the rounding up was done to the nearest whole star, so a 4.5 rated movie would be rounded up to 5 stars.
- One movie analyzed was rated 4 stars and rounded up to 5 stars.
- No movie was rated 2 stars or below.

Fandango officals replied saying that the rounding off was caused by a bug in their system rather than biased rounding, in this project we'll analyze more recent movie ratings data to determine whether there has been any change in the rating system after Walt Hickey's analysis.
