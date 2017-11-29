Backend CLI application allowing user to type in commands to access the Twitter, Spotify, or OMDB APIs.

Technologies Used:

JavaScript, Node.js, fs, request, npm packages, APIs

APIs:

Twitter, Spotify, OMDB

Walkthroughs:

General:

In the command line run 'npm install' to install all of the required npm packages in the package.json file.
liri-bonus.js file is adds an extra feature where the results are logged in a log.txt file.

Twitter:

In the command line, type in 'node liri.js my-tweets' to display the last 20 tweets of a specifid Twitter account in set in the liri.js file.

Spotify:

In the command line, type in 'node liri.js spotify-this-song [insert song title here]' to display 10 relevant results of your requested song. If no song is entered, it defaults to 'My Hero'

OMDB:

In the command line, type in 'node liri.js movie-this [insert movie title here]' to display a single result of your requested movie.

Extra feature:

In the command line, type in 'node liri.js do-what-it-says' to run a preset command set in the random.txt file.
