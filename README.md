# Database Management Project 2
# Project 2: Create database for MuzifyMe, a music streaming subscription service.
Capabilities my database design must support include:
> 1.	Users 
	a.	Name
	b.	Email
	c.	Payment information
	d.	Subscription level (paid and free)
> 2.	Song genres. Songs can belong to more than 1 genre.
> 3.	Song
	a.	Name
	b.	Album
	c.	Artist/Performer (one or more)
	d.	Genre (one or more)
	e.	An artist/performer may have performed a song more than once for different albums or in more than 1 band.
> 4.	User created playlists of songs.
	a.	Sharing playlists with other users
> 5.	Performing groups (bands)
	a.	Band group members (primary ones)
> 6.	Record label
	a.	Name
	b.	Payments 
> 7.	Payments 
	a.	From users
	b.	To record labels (who distribute it to artists/performers).
> 8.	Play counts (for payment to artists). We need to be able to count the number of times a song has been played each month for each artist.
> 9.	Play counts, to let users know their most/least listened songs. We need to be able to count how many times a user has played each song in a month.
