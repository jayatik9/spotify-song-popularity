# spotify-song-popularity
As we know Spotify is one of the most popular audio streaming platforms around the globe. Here we are trying to predict the popularity of the song based on different features available. Dataset was available on Kaggle.
On the technical side, Spotify provides an interesting look into their listening data. Not just the popularity of tracks, but also features of the tracks they have in their library.<br>

## Project Context
To predict the popularity of songs based on the various audio features of each track in the selected dataset. 

## Business Problem
How can different features impact the popularity of the songs irrespective of the artist the songs were sung by. Some of the features like danceability, loudness, acousticness etc which are difficult to understand but are still capable of finding out weather the song added to the spotify database will be popular or not. 

## Goal
The question we’ll be looking at is - Can we predict a track’s popularity from key features about the song? This will be helpful for editors of the song if based on the analysis any of features that can be edited before releasing it on spotify.


## Data Exploration and Preprocessing

The selected dataset contains below features - 

**Artist_name** : Name of the the artist.<br>
**Track_id** : Uniques ID of the track.<br>
**Track_name** : Name of the track.<br>
**Duration_ms** : Duration of the track in milli-second.<br>
**Acousticness** : A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.<br>
**Danceability** : Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.<br>
**Energy** : Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.<br>
**Liveness** : Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides a strong likelihood that the track is live.<br>
**Loudness** : the overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db. <br>
**Speechiness** : Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audiobook, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.<br>
**Valence** : A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).<br>
**Tempo** : The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.<br>
