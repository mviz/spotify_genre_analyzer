# Spotify Genre Analyzer

I used the [Spotify API]() to download six playlists: two rock, two rap, two country. Then I applied logistic regression on each combination of pairs to determine the predictability of the differences between the genres.

Perhaps as expected, my classifiers had more success differentiating rap than it did between rock and country.

Here's my full blog post about it.

## Using the code / data

There are two main iypython notebooks:
*   playlist_downloader
*   playlist_analyzer

If you want to see how I got the playlist data, or change up the data, you can modify `playlist_analyzer` . I used the [spotipy]() github project to access the data.

The analysis is done, surprisingly, in `playlist_analyzer`. In that file I perform some assumption checks, the logistic regression, visualizations, and more.

## Extensions

Here are some follow-up projects:  
*   Use multi-class logistic regression to compare multiple genres
*   Download some different genres to see how they compare
*   Use a more sophisticated method of classification, like LDA.
