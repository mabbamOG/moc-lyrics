# moc-lyrics
moc-lyrics is a simple bash script that fetches the lyrics of current song playing in MOC (music on console) music player.

*This version of `moc-lyrics` has been adapted from the original script, which is itself a minor adjustment of the original documentation for [makeitpersonal]. Feel free to check out the original version of this project [here][original-project].*


### Dependencies :
- Python (v. 3+) - [python] is an interpreted, interactive, object-oriented programming language. It is available on most linux distributions and can be easily installed via the package manager. Be careful to install version 3, as version 2.7 is still quite popular.
- curl - [curl] is a command line tool and library for transferring data with URL syntax. curl is available in repositories of almost every Linux distribution so you can install curl easily via your package manager.
- vim - [vim] is a highly configurable text editor built to enable efficient text editing. It is an improved version of the vi editor distributed with most UNIX systems. It is available for every unix platform, if you don't want to use it just replace the `vim -` string with `less`, like so:
```sh
$ sed -i -e 's/vim -/less/' moc-lyrics
```


### Installation :
Very easy.
Clone the project:
``` sh
$ git clone https://github.com/mabbamOG/moc-lyrics.git
```
Next copy the bash script to your executables' directory:
 ```sh
$ sudo cp moc-lyrics/moc-lyrics /usr/local/bin/
```
And make it executable:
```sh
$ sudo chmod a+x /usr/local/bin/moc-lyrics
```
Done :)


### Usage :
Run moc-lyrics and it will fetch and print lyrics of the song currently playing in [MOC] music player.


### Credits :
[Federico Builes] - moc-lyrics wouldn't have been possible without wonderful [makeitpersonal] created by Federico.


### License :
[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">moc-lyrics</span>, by [<span property="dct:title">mabbamOG</span>](https://github.com/mabbamOG/moc-lyrics)), identified by [<span property="dct:title">mabbamOG</span>](https://github.com/mabbamOG), is free of known copyright restrictions.

[original-project]:https://github.com/hakerdefo/moc-lyrics
[python]:https://python.org
[curl]:https://curl.haxx.se
[vim]:https://www.vim.org
[MOC]:https://moc.daper.net
[Federico Builes]:https://github.com/febuiles
[makeitpersonal]:https://github.com/febuiles/makeitpersonal
