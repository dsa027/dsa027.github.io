---
layout: post
title: BlocJams-Angular
thumbnail-path: assets/img/posts/bloc_jams_logo_thumb.png
short-description: A Web-based, SPA song player written in AngularJS
summary: A Web-based, SPA song player written in AngularJS
featured-img: bloc_jams_logo
---
<a href="https://bloc-jams-angular-dsa027.herokuapp.com/">
  <img src="{{site.url}}/assets/img/posts/bloc_jams_logo_thumb.png"/>
</a>

![]( {{site.url}}/assets/img/GitHub-Mark-32px.png "GitHub")
[GitHub](https://github.com/dsa027/Bloc-Jams-AngularJS)
{:.center}

{% highlight javascript%}
{% endhighlight %}

# Summary

  A music player written with CDN-Hosted AngularJS.

# Explanation

  Streams, via [Buzz audio](http://buzz.jaysalvat.com/), songs located on the site. There are five songs in total, but they are called random names and contained within 12 randomly named albums. Albums are shown in the Collections tab.

  Songs, Albums, and Artists may be searched for at the top-right of any page. Tap on one of the results in the dynamic list to visit the album.

  Add to a playlist, or create a new one, by selecting a song in the Album view. Playlists are viewed in the Playlist tab. This tab allows you to play a playlist, delete a playlist, and delete a song from a playlist.

  The application is generally broken down by
  - [Home](https://bloc-jams-angular-dsa027.herokuapp.com/) - home page with hero, marketing info, and navigation.
  + [Collection](https://bloc-jams-angular-dsa027.herokuapp.com/collection) - this is where albums are all kept.
  + Album - head into the Collection tab and choose from 12 albums.
  + [Playlists](https://bloc-jams-angular-dsa027.herokuapp.com/playlists) - Lets the user make their own collections of songs.
  + Search - located in the upper-right corner of every page, search albums by Song name, Album name or Artist.
  + PlayerBar - song controls: play, pause, seek, next, previous

# Problem

  This application, with less functionality, was originally written in JavaScript and JQuery and then again in React. This project was done with minimal instruction and included writing it in Angular while adding playlist and search functionality.

# Solution

  This project shows the practical application of several technologies:
  - Angular
    - The entire application is written in Angular. Controllers, Services, Directives and Filters are used.
    Buzz Player
  - Node.js
  - JavaScript
  - HTML/CSS
  - Ion Icons
  - Heroku
  - GitHub

# Results

  This iteration of BlocJams fulfilled all requirement plus a few more bells and whistles. There are minor bugs to still fix and some enhancements would make the app even better.

# Conclusion
  JavaScript and Angular are two of my favorites. It was fun writing and I think it's one of my better applications.

  ToDos
  - Stream from other source
  - Database of songs
