# Flappy Bird Wii
This is really just a fun experiment for me since I've never made a Wii app before. It's a flappy bird clone for Wii, although only the flapping part. There's no way to lose, you just press A to flap the bird up and watch it fall down. Still fun though.

<blockquote class="twitter-tweet" lang="en"><p lang="en" dir="ltr">I made a flappy bird clone for Wii! <a href="http://t.co/lvg7FY6xgz">pic.twitter.com/lvg7FY6xgz</a></p>&mdash; Thomas Finch (@tomf64) <a href="https://twitter.com/tomf64/status/609124107838488576">June 11, 2015</a></blockquote> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

If you want to compile this yourself, download [Dev Kit Pro](http://devkitpro.org) and set the $DEVKITPPC environment variable. Then just clone this repo and run `make` inside it (you may need to `make clean` first). To deploy to a Wii, first make sure it's homebrewed, then connect to the internet on it and open the homebrew channel. Set your wii's IP address by running `export WIILOAD=tcp:<Wii IP>`, then just run `./wiiload` while on the same network as your wii to automatically download and run it.
