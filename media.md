Here are some ideas on how to embed media to SooC pages.

# Aporee
Both projects and individual maps work.
```html
<iframe width="100%" height="666" src="https://aporee.org/maps/work/projects.php?project=soocroeselare"></iframe>
```

## to create a map of the current Location, copy the following code to your webpage: (preview)

content_copy
```html
<iframe width="100%" height="100%" src="https://aporee.org/maps/work/export/?loc=54724&m=satellite"></iframe>
```

## to create a link to the current location, copy the following code to your webpage:

content_copy
```html
<a href='https://aporee.org/maps/?loc=54724&m=satellite'>radio aporee ::: maps - Kaaistraat 5, 8800 Roeselare, Belgium</a>
```

# Bandcamp
```html
<iframe style="border: 0; width: 100%; height: 472px;" src="https://bandcamp.com/EmbeddedPlayer/album=1186956079/size=large/bgcol=ffffff/linkcol=0687f5/artwork=small/transparent=true/" seamless><a href="https://heariam1.bandcamp.com/album/hear-i-am">Hear I am</a></iframe>
```

# Dropbox
Video embed works but it is slower than YouTube, consider transfering the video? 
```html
<iframe width="100%" height="500" src="https://www.dropbox.com/s/85yuhsf6c435fzp/MANOEUVRES-5-TIN-CAN.mp4?raw=1"></iframe>
```
# Issuu

Works only with paid accounts, for free accounts, it is best to download the pdf and link.

The general format:

https://issuu.com/{username}/docs/{documentname}
https://issuu.com/nataliadomingueztorres/docs/final_transound_publicationnewlink

```html
<iframe allowfullscreen allow="fullscreen" style="border:none;width:100%;height:326px;" src="//e.issuu.com/embed.html?backgroundColor=%23ebb88a&backgroundColorFullscreen=%23ebb88a&d=final_transound_publicationnewlink&hideIssuuLogo=truee&hideShareButton=true&pageNumber=0&u=nataliadomingueztorres"></iframe>
```

# Pluggy
Current experimentation: 3D sound with Earpods
```html
<iframe width="100%" height="450" src="https://beta.pluggy.eu/exhibitions/plugin/5ca1e3cbf0adadd7c66b31e8/5fd225713f3bc48e5750299b"></iframe>
```

# Soundcloud

Works nicely, remeber to disable the autoplay and enable 'hide_related'
```html
<iframe width="100%" height="133" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1158594169&color=%23ff5500&auto_play=false&hide_related=true&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/soocities" title="SooC" target="_blank" style="color: #cccccc; text-decoration: none;">SooC</a> · <a href="https://soundcloud.com/soocities/podcast-cotorradio" title="Podcast COTORRADIO." target="_blank" style="color: #cccccc; text-decoration: none;">Podcast COTORRADIO.</a></div>
```

# YouTube
You tube works much faster
## Direct link

[Video](https://youtu.be/SiLQofd-Tzw)

## iframe
```html
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/SiLQofd-Tzw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
```

# Vimeo

```html
<iframe src="https://player.vimeo.com/video/641631399?h=2314ed16f4&color=f28628" width="100%" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<p><a href="https://vimeo.com/641631399">Watch "To plant a flying garden (2021)"</a> from <a href="https://vimeo.com/user16473305">Mart&iacute; Madaula Esquirol</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
```
