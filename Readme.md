# Netflix Movies and TV-Shows Analysis

This project focused on analyzing over 8000 entries of both movies and TV-Shows added to Netflix from 2008 to 2021.



## Features Description

* show_id - refers to the unique identifier of the movie or tv-show
* type - inicates whether the show is a movie or a TV-Show
* title - refers tot he movie or tv-show title
* director - refer to the individual who directed the movie or tv-show
* cast - a list of the actors or actresses in the movie or tv-show
* country - refers to the country of origin of the movie or tv-show
* date_added - indicates when the movie or tv-show was released/aired on Netflix
* rating - indicates the maturity ratings of the movies or tv-shows which tells the group of audience they are suitable for
* duration - refers to how long the movie or tv-show was. This coulb be hours or seasons long
* listed_in - refers to the various genres under which the movie or tv-show is placed
description - gives a blurb (short summary) about the movie or tv-show



## Data Wrangling

The dataset was visually and programmatically assesed, nulls were dropped or replaced with suitable values where neccessary.

An additional feature `year_added` was created to aid the generationof insigts



## Overview of Insights

The analysis revealed that:

> Majority of the programmes added are for Mature Audiences and may not be suitable for ages 17 and under.

> For ratings suitable for kids (i.e. TV-Y and TV-7) without parental guidance of any sort,most of these were TV-shows

> 69.7 %, approximately 6127 of all added title were that of movies and 30.3 % corresponding to 2663 were that of 
TV-Shows

> Generally, movie additions have increased over the years more than TV-Shows.

> Both saw little to no increase from 2008 till 2014 when TV-Shows pick up gradually whiles movies took a quick jump.

> Movie addition started declining again from 2019 wherease TV-Shows in 2019 to 2020 plateaued befor declining from 2020
to 2021.

> More TV-Shows than Movies were added with unknown coutries of origin from 2016 till 2019. The opposite was realized for 2020 and 2021.



Finally a wordcloud of the titles was generated