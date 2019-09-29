# murphy-website
2016 handmade website for Murphy &amp; the Giant.

## License
This software is fully free and open source (FOSS) and is permissively licensed, with the exception of whatever Font Awesome and modernizr libraries are.

## Details

### Purpose
We needed a website to host our calendar, music, link to social media and the like -- as well as sharing file drops (audio and video). I enjoy making artistic websites, and had a little extra time on a Friday, so I took it upon myself.

### Design
I decided to go with black-and-white images from [The Troubles](https://en.wikipedia.org/wiki/The_Troubles). 

I wanted to keep it lightweight, but something visually interesting. I was considering a one-page parallax, but hated all the janky JS implementations. While looking for inspiration, I stumbled across [this CSS3 background slideshow tutorial from Codrops](https://tympanus.net/codrops/2012/01/02/fullscreen-background-image-slideshow-with-css3/). I liked it, so I hand-crafted some media queries based on their example. I also liked the bold Bebas Neue font, and as it was free for commercial use, I included that.

### Utility

An important bit was our Google calendar integration, as it allowed us to coordinate for booking shows or when we had conflicts. Coded up a (really bad) html http-equiv redirect, to share the calendar openly with our friends and followers.

Finally, I added OpenGraph integration, font-awesome for our social media logos, etc.

Also, we needed a place to drop files, so I created a hidden directory named "thepub" (short for public, but also an Irish bar) which was just an Apache directory listing with subfolders for music, videos of rehearsals, etc.

