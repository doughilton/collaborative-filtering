Collaborative Filtering:

Basic Process:

User submit playlist

Songs are missing from user playlist

What songs are missing

Playlists which most closely match user playlist

What songs are on matching playlists



Basic Details:

User submits 10 song playlist

Generate all playlists with at least one song in common

Score how well each matching playlist compares to user playlist

List of all songs on matching playlists not on user playlist

Score songs on how many matching playlists they appear

Score songs on how well the matching playlist matched the user playlist



Completed Work:

Turn all this work into a function


Current Work:

Penalize playlists for their length
  Divide by cube root of length of playlist
  Play with this number, test with different playlists and results
  Common artists, rare artists, artists across genres
  Does this penalization value rely on other future scoring changes?



Future Work:

Return how much each user song contributed to final score

Penalize songs for how many playlists they appear on
Helps to find hidden gems

Both penalizations to be calculated before user submits list

Do we do anything if a user submitted song is heavily penalized?
What is a user submitted song is a hidden gem?

Match playlists on artists not just songs

Turn all this work into a function
Additional parameter to change how the algorithm works?
	Hidden gem, how rare do we want the resulting songs to be?



Cleanup Work and Data Questions:

Why are so many records skipped when importing data

Is there a better data source?

Find and handle NULL values

Make everything lowercase, remove uncommon characters

Are there any smaller artists?

