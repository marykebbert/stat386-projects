---
layout: post
title: A Look Into Taylor Swift's Record Smashing Charts over the Eras
date: 2022-12-07
author: Mary Curtis
description: As I wrap up this project, come see what I found out!
image: /assets/images/eras-tour.jpeg
---

Growing up, I had heard about Taylor Swift, but I don't think I became a true Swiftie until about a year ago when I started listening to my husband's playlists. In the past year, I feel that I have been watching unprecedented developments in her career. Just this October, her album 'Midnights' broke several chart records, and her Eras tour sold out almost immediately. Thus, I began this project with the following question: "How has Swift's popularity changed over the years, and how might this have contributed to the record-breaking success of 'Midnights'?

## Data Collection
This question has taken me down many paths. I initially wanted to use Spotify's API to find the success of her albums and songs over the years and take advantage of the track features it offers to see how her music may have changed. However, after retrieving the data, I realized there was not enough data for me to see the progression of her career. Next, I turned to the Billboard Hot 100. I assumed I could answer this question by seeing how her tracks have performed over the years. In many instances, I could. In my last post, I found her most popular songs and got an idea of how well each album performed. However, after hours of trying to make this data more presentable, I realized that the simplest way to find the answer to my question would be to use a different Billboard, the Billboard 200. This record chart ranks the most popular 200 albums every week. Almost immediately after retrieving this data (see this repository for the code), I plotted a simple line graph, and voila! It was very messy, but I could finally see the performance of her albums over the years. (Note: I wanted to use the Artist 100 Billboard, but this only started in 2014 and thus did not go back far enough for my needs) 

## Final Graph and Story
![Plot](https://raw.githubusercontent.com/marykebbert/stat386-projects/main/assets/figures/my_plot.png)

As this plot shows, Taylor Swift has an impressive 16-year career. Beginning in 2006, her first album, 'Taylor Swift,' met with almost immediate success. It peaked at #5 on the Billboard 200 and stayed on the charts for five years! Her next album, 'Fearless,' did even better. It debuted as #1 and remained in the top 10 for over a year! In fact, all of her following albums debuted as #1. Her subsequent two albums, 'Speak Now' and 'Red,' performed well, although they were not as popular as 'Fearless.' However, '1989', her first official pop album, took the world by storm and marked Swift's flawless pivot from country star to pop star. '1989' stayed in the top 10 for nearly 1.5 years and has practically stayed on the charts ever since!

After a year hiatus from the public, Swift released 'Reputation.' It performed well, despite being much edgier than her previous albums. It did not last as long in the top 10 as '1989', but I think it helped rekindle interest in Swift's work after a long time of radio silence. 'Lover' soon followed suit but has stayed in the top 100 until now, showing that it has remained a fan favorite for over three years. The surprise releases of the indie-folk albums, 'Folklore' and 'Evermore' less than five months later, performed well, although 'Evermore' quickly dropped beneath 'Folklore.' Her re-recorded albums of 'Fearless' and 'Red' sparked considerable interest. 

![Eras](https://raw.githubusercontent.com/marykebbert/stat386-projects/main/assets/images/eras.jpeg)

By the time Midnights was released, eight albums were on the charts! It seems as if the release of 5 albums over a little more than two years builds the momentum for this album's success. Within days of its release, this album breaks billboard records, including making history as the first artist to occupy all top 10 spots of the Billboard Hot 100.

In short, at 32, Swift shows no signs of slowing. Over the eras, she has won over fans with country, pop, electronic, and indie-folk music. With a uniquely creative, authentic voice, she continues to take the music industry by storm. 

*As always, please comment below with any suggestions on what to explore next!*