# **Spotify Streaming Trends** 
by Ollie Downs, Michael Steckler, Chelsea Shu, and Emma Russon

This is the final project for UC Berkeley's Data Visualization class, taught by John Alexis Guerra Gómez, for the MIDS program. Click on the following links to view our video demo and website.


[Video]()


[Website](http://people.ischool.berkeley.edu/~erusson/spotifystreams/index.html)



![](spotify_gif.gif)



The Spotify Streaming Trends site is a website that allows Spotify executives to understand and analyze trends to promote informed business decisions. We use the dataset that includes the top 200 songs per day in 2017. 

The **Sex, Drugs, and Rock'n'Roll** page was created by Ollie Downs. They found that classic topics in music allow us to draw several important conclusions about the state of music in 2017.


The **Weekly and Monthly Trends** page was created by Michael Steckler. His main finding is that ad slots can be priced  dynamically according to genre- and temporal-specific listening trends.


The **Sentiment Analysis and NLP Algorithm** page was created by Chelsea Shu. She uncovered that the NLP algorithm used to calculate song and lyric sentiment fails to capture the sentiment of foreign languages, and therefore needs to be improved. The NLP algorithm can be found [here](https://towardsdatascience.com/sentiment-analysis-of-all-billboard-hot-100-songs-over-time-1958-2019-3329439e7c1a).


The **Gender in Streams** page was created by Emma Russon. She found that different metrics for popularity lead to different actionable insights, while shining light on the gender disparities in the music industry.


To view this website locally on your server, use the following commands. 

Open up the command line and create a new directory.
```mkdir spotify
cd spotify```


Clone this repository.
```git clone https://github.com/chelseashu/spotifystreams.git```

Run the following command.
```python -m http.server```

Open up your browser and tyoe the following into your search bar. 
```localhost:8000```



