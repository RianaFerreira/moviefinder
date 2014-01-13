# Movie Finder
**name** Riana
**github** rianaferreira
**heroku** rf-moviefinder.heroku.com

Movie Finder allows you to search for any movie title. A server side JSON object will store movie information retrieve via HTTPrequest using the OMDB api. Successful searches will be written to a file so that a search history is built up, this file can be cleared.

## Technologies
* Sinatra framework
* Ruby
* HTTPrequest and JSON object
* File create, read and update

## References
* css3-github-buttons by Nicolas Gallagher https://github.com/necolas/css3-github-buttons
* MDN CSS https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
* HTML5 Doctor http://html5doctor.com/
* One Extra Pixel http://gallery.onextrapixel.com/

## Wishlist
1 Use AWS to store copies of the poster images.
Hotlinking blocked by IMDB from Heroku application, but works from local server. Poster mages are not being rendered for the movie search. http://stackoverflow.com/questions/11044010/imdb-poster-url-returns-referral-denied
