# What would I sing in the shower?

1. [Parsing the data](#parsing)
2. [A few visualizations](#visualizing)
3. [Generating the lyrics of my "shower song"](#perfectsong)

As I like to spend the bulk of my days with some sort of music in the background, I decided to look a little closer at what I had saved as my "favorite" music on Spotify.

I realized that I listened to many different types of music and was wondering what the similarities/differences could be between them.

Music is so prevalent in my daily life and it can shape meaningfully my mood at any given moment. So, I wondered: would it say anything about my personality?

Finally, all the while I learned about Natural Language Processing and digged deeper in the songs, I thought it would be interesting to try to get an introduction to LTSM neural networks and try to generate lyrics of a hypothetical "personal song" even though my corpus was relatively limited.

## Creating the Dataset <a name="parsing"></a>

I started by downloading the data from Spotify and leveraging Spotipy (https://spotipy.readthedocs.io/en/latest/) and the Spotify Web API. After authenticating, I stored the data related to what I listened to in a dataframe.

Later, I used this dataframe to find the song on Last.FM and to return the listening count (as Spotify does not let us parse the latter stat). I also used it to download the lyrics from http://azlyrics.com with Selenium and parse the text for each song when available.

## What do I actually listen to? <a name="visualizing"></a>

I have to admit... I had to think hard before publishing this repo on GitHub as I am not necessarily the proudest regarding my musical tastes. I did (and still do) consider myself a "Musical omnivore" (more on this concept <a href="http://www.oxfordbibliographies.com/view/document/obo-9780199756384/obo-9780199756384-0134.xml">here</a>).



## Generating Lyrics from my Songs <a name="perfectsong"></a>
