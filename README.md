# 2k

2048 in 2048 bytes. I'm only counting the index.html, not the readme or .editorconfig since they are not actually served.

For proof, run `curl https://patrickstephansen.github.io/2k/ | wc -c`.

## goals

* make the source 2048 bytes at all costs - done
* make the source 2048 bytes when auto-formatted by [prettier](https://prettier.io/) - done
* make the page work on mobile devices (detect swipes as well as arrow keys) - done
* display the player's score on the page
