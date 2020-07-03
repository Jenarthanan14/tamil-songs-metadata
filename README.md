# Tamil Songs Metadata

## Dataset :notes: 
```tamil_songs_corpus.csv```

The album of tamil track, collect from [tamilpaa.com](https://www.tamilpaa.com/), is Tamil-Songs-Corpus. Nearly **2000+** Tamil songs are available from over **500 films**. On the Colab website, I have been using a python script for the selection of Tamil songs in the ``` BeautifulSoup ``` library. Originally, I saved the CSV file containing the film JSON and every film object holds the Song object list. Then I preprocessed it for flat CSV songs to translate the same field into Tamil purity. The collection of the final song is given below.

* year: Year of Movie released.
* movie: Name of the movie featured in the song.
* song_title: Song Title in Tamil and English.
* song_music: Music director of the Song.
* song_lyrics: Song lyrics writer of the songs.
* song_singers: Comma Separated Song Singers of the songs.
* song_fulllyrics: Full Lyrics of the Songs In Tamil.
* music: 	Music director of the movie.
* actors: Comma Separated Actors Names.
* movie_url: Movie URL in the TamilPaa website.
* movie_image: Image_URL in TamilPaa website.
* movie_name_tamil: Name of the movie in Tamil featured in the song.
* movie_name_eng: Name of the movie in English featured in the song.
* rating: The rating of the song from the TamilPaa website.

## Stopwords :no_entry_sign:
```stopwords_ta.txt```

Use Stopwords When Indexing Content. Most written text has a lot of functional words, like ```“முதல்”, “என்ன”, “இருந்து” and “சில”``` which are important to the person reading the content as they help it flow cohesively, but aren't necessarily as important to someone searching the content of our site.

## Synonyms: 
```synonyms.txt```

This feature helps to enhance user experience in the data context by recognizing different uses for a term. To achieve this functionality, Solr ships with a filter factory named SynonymFilterFactory. It also includes a file called **synonyms.txt**, for instance to add our synonyms

```
*லாரன்ஸ், லோரன்ஸ்
*ஆண்டனி, அண்டனி
*ஷரத்தா, ஷ்ரத்தா
*இம்மான் , இமான் 
*ஜி.வி.பிரகாஷ், ஜீ.வி.பிரகாஷ்
```
