### Ducket HTML Book
#### Flash, Video, Audio (Chapter 9, pages 201-206)
 - Flash is used for playing audio and video
 - Flash was originally created for animations
 - HTML5 tags of ``<audio>`` and ``<video>`` were created in 2008.

#### Images (Chapter 16, pages 406-427)
 - __float__ is used to have text float around the images on either the left or right side.
 - __background-images__
    - ``background-repeat`` is repeated horizontally and vertically
    - ``repeat-x`` only repeated horizontally
    - ``repeat-y`` only repeated vertically
    - ``no-repeat`` no repeat
    - ``fixed`` imgae stays in the same position
    - ``scroll`` image scrolls with the user


#### Practical Information (Chapter 19, pages 476-492)
 - __SEO__ Search Engine Optimization is when you try to get your website to appear at the top of a search engine
 - the text within your website is what is searched, including image tags
 - linking to other similar sites is also valuable to SEO
 - Google Analytics will track user visits to your site.
 - __Web Hosting__ web sites are uploaded to web servers that are connected to the internet so your website can be viewed.
 - __Disk space__ is the total space needed for your website
 - __Bandwidth__ is the amount of data that is sent to the user
 - __FTP File Transfer Protocol__ is to transfer your files from your computer to the hosting company

#### MDN article on audio and video elements
 - place the entire video and controls in one ``<div>``
 - the ``<video>`` element contains two ``<source>`` elements so that different formats can be loaded depending on the browser
 - ``<button>`` for play/pause, stop, rewing and fast forward
 - ``<visibility>`` and ``<opacity>`` are beneficial to aid in the appearance on the video screen
 - an event listener is required for the play/pause button
    - example: ``play.addEventListener('click', playPauseMedia);``
 - other functionality of stopping the video, seeking back/forth abd updating the elapsed time are used as well.