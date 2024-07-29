
# Mesh


[Video Link](https://youtu.be/nJ1pHzIryns)


## Inspiration

When you've had a long, stressful week, you might want to go out and have some well-deserved fun. But, it sucks when the one thing that should be lifting your mood at an event is the one thing that can also kill it: music, particularly bad song choices. For our first hackathon, we wanted to tackle an issue that was more lighthearted, fun, but still significantly impactful. This seemed perfect because music reaches everyone!

## What It Does

Mesh takes user input playlists and predicts and creates a playlist that the most people will enjoy.

## How We Built It

First, we had to create a Spotify Developer Account to access the data, the commands, and certain keys. After that, we needed to code a method to extract only the information we needed from the larger data given. Then, we used that information that gave certain variables to create a formula that ranked songs by giving them scores. Finally, we coded a way to take those songs that were ranked and output them in ranked order so that event organizers can make a playlist with them.

## Challenges We Ran Into

Understanding the Spotify API was a steep learning curve for us. However, it was a critical step that allowed us access to a wide data set including streams per song, genre, and even danceability. Another challenge we ran into was the algorithm we used to determine if a song was "good."

## Accomplishments That We're Proud Of

One accomplishment was that we were able to combine two different playlists to give a reasonable prediction of what the two people may be able to enjoy together. Furthermore, being able to prototype and finalize an algorithm to be scalable is a significant achievement.

## What We Learned

We learned how to extract data, access APIs, and perform data analysis of music. We also gained insight into the different factors that Spotify collects.

## What's Next for Mesh

There are a few different possibilities:

1. We can automate the creation of a Spotify playlist for the user that adds a public playlist available to the user on their account.
2. We could ask the user for a certain mood for the output playlist and screen certain factors/requirements.
3. We could create a machine learning algorithm to predict the best song order based on the level of energy for each song and ensure eventgoers do not get tired or bored. We could potentially train this algorithm by pairing this program with an app that asks for the eventgoers' opinions on certain songs in real-time.
