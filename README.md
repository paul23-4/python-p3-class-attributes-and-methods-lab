# python-p3-class-attributes-and-methods-lab

## Song Class

The Song class represents individual songs. Each song has a name, an artist, and a genre. The class provides functionality to keep track of the number of songs created, as well as the artists and genres associated with those songs.

## Usage

### Creating a Song

To create a new song, instantiate the `Song` class with the name, artist, and genre parameters:

song = Song("Song Name", "Artist Name", "Genre")
Accessing Song Attributes
You can access the attributes of a song using dot notation:


print(song.name)    # Output: "Song Name"
print(song.artist)  # Output: "Artist Name"
print(song.genre)   # Output: "Genre"

## Class Attributes ##
The Song class maintains several class-level attributes to track song data:

count: The total number of songs created.
genres: A list of unique genres.
artists: A list of unique artists.
genre_count: A dictionary mapping genres to the number of songs in each genre.
artist_count: A dictionary mapping artists to the number of songs by each artist.

You can access these attributes directly from the Song class:

print(Song.count)        # Total number of songs created
print(Song.genres)       # List of unique genres
print(Song.artists)      # List of unique artists
print(Song.genre_count)  # Dictionary of genre counts
print(Song.artist_count) # Dictionary of artist counts

Example

# Create songs
song1 = Song("Song 1", "Artist A", "Genre X")
song2 = Song("Song 2", "Artist B", "Genre Y")
song3 = Song("Song 3", "Artist A", "Genre Z")

### Access class attributes

print(Song.count)        # Output: 3
print(Song.genres)       # Output: ['Genre X', 'Genre Y', 'Genre Z']
print(Song.artists)      # Output: ['Artist A', 'Artist B']
print(Song.genre_count)  # Output: {'Genre X': 1, 'Genre Y': 1, 'Genre Z': 1}
print(Song.artist_count) # Output: {'Artist A': 2, 'Artist B': 1}
