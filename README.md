# imdbGo
Nothing too fancy. Simple package for looking up IMDB movie data by title.

Just save your API key in local envs (OMDBKEY) and import away to your project!

USE: imdbGo.Movies("blade runner") -> []byte

Output: Marshaled JSON []byte. Parse the way you'd like.

This is using the Open Movie Database API, an unofficial API for data available at IMDB.
Unfortunately, the folks over at OMDB are using HTTP, so there's that. 

Feel free to check it out: http://www.omdbapi.com
