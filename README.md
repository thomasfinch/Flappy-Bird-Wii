# Flappy Bird Wii
This is really just a fun experiment for me since I've never made a Wii app before. It's a flappy bird clone for Wii, although only the flapping part. There's no way to lose, you just press A to flap the bird up and watch it fall down. Still fun though.

If you want to compile this yourself, download [Dev Kit Pro](http://devkitpro.org) and set the $DEVKITPPC environment variable. Then just clone this repo and run `make` inside it (you may need to `make clean` first). To deploy to a Wii, first make sure it's homebrewed, then connect to the internet on it and open the homebrew channel. Set your wii's IP address by running `export WIILOAD=tcp:<Wii IP>`, then just run `./wiiload` while on the same network as your wii to automatically download and run it.
