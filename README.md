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

Make everything lowercase, remove uncommon characters

Match playlists on artists not just songs
  Heavily weights playlists which are only one artist too much

Penalize Playlists for their diversity
  Heavily penalizes playlists which are just discographies
  Bubbles songs up belonging to many playlists with large diversity of artists

Penalize songs for how many playlists they appear on
  Helps to find hidden gems
  Works very well in conjunction with Playlist Diversity Penalization



Current Work:



Future Work:

Return how much each user song contributed to final score

Both penalizations to be calculated before user submits list

Do we do anything if a user submitted song is heavily penalized?
What is a user submitted song is a hidden gem?

Turn all this work into a function
Additional parameter to change how the algorithm works?
	Hidden gem, how rare do we want the resulting songs to be?



Cleanup Work and Data Questions:

Why are so many records skipped when importing data

Is there a better data source?

Find and handle NULL values

Are there any smaller artists?

