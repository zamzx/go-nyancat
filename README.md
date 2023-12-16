### ZAMZX WANTED NYAN CAT, SO ZAMZX FIXES

the command line arguments for mpg -l did not work, so I took it out. Add -Z if you want it to loop forever until pid death...lmk if you know the correct args for clean shutdown. 

![nyancat](http://i.imgur.com/4YSU5J6.gif)

## Installation

```sh
git clone https://github.com/zamzx/go-nyancat.git
cd go-nyancat && go build
```

Install [mpg123](http://www.mpg123.de/) for audio support.

On Mac OS X using Homebrew: `brew install mpg123`

## Usage

Run:

```sh
./go-nyancat
```

Options:

```
  -m    Don't play audio
  -n    Don't show the time nyaned
```

## Resources

- [Nyancat CLI](https://github.com/klange/nyancat)
- [Ruby port of Nyancat CLI](https://github.com/andatche/ruby_nyancat)
- [NyanCat Song](http://momolabo.lolipop.jp/nyancatsong/Nyan/Nyanyanyanyanyanyanya%21.html)

## License

Released under the BSD 2-clause license. See LICENSE.txt for details.
