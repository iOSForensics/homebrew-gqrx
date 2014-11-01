This is an effort to setup a homebrew formula for http://gqrx.dk. *It probably
does NOT work (yet!)*. Feel free to file an issue or fork the repo to help me out.

It is NOT a "gnuradio and friends" repo. It will only include gqrx and will rely on other Formula for GNURadio and other dependancies.

I plan to use [metacollin/homebrew-gnuradio](https://github.com/metacollin/homebrew-gnuradio) to satisfy the GNURadio dependancy.

I want to thank [titanous](https://github.com/titanous/homebrew-gnuradio), [robotastic](https://github.com/robotastic/homebrew-hackrf), [0x90](https://github.com/0x90/homebrew-megarf), and [metacollin](https://github.com/metacollin/homebrew-gnuradio) for their development and inspiration.

I invite each of them and all of their collaborators to help me get pull requests of gnuradio, gqrx, and other related formula into Homebrew.

More (most) importantly, I want to thank [csete](https://github.com/csete/gqrx) for his excellent GQRX software.

INSTALL
=======
First, visit [metacollin/homebrew-gnuradio](https://github.com/metacollin/homebrew-gnuradio) and carefully follow all of his instructions to tap the repo and install gnuradio.

Then, tap this gqrx repo and install gqrx:

```sh
brew tap chleggett/gqrx
brew install gqrx
```
