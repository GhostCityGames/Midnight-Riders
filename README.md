# Midnight Riders: A Role-Playing Game of Bikers & Beasts

Ghost City Games

![Screenshot](https://github.com/GhostCityGames/Midnight-Riders/blob/master/source/_static/mr-cover.png?raw=true "Midnight Riders Cover")

Midnight Riders is a pen and paper Role-Playing Game (RPG) that can be played with 3 to 6 players.

Support the developers of Midnight Riders by purchasing a copy of the book at [DriveThruRPG](http://www.drivethrurpg.com/product/225714/Midnight-Riders)
or developing with us on [Github](https://github.com/GhostCityGames/Midnight-Riders).

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br>Copyright © Ghost City Games 2017.  Except where otherwise specified, the text on <a href="https://github.com/GhostCityGames/Midnight-Riders">Midnight Riders</a> by Ghost City Games is licensed under the <a href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike License 4.0 (International) (CC-BY-SA 4.0)</a>.

Art © 2017 Nicole Dutram. Used with permission.

Contact the artist via e-mail: dutram.nd@gmail.com.

# Contributing to Midnight Riders

We would love to hear from you!  Create [New Issues](https://github.com/GhostCityGames/Midnight-Riders/issues/new)
with questions, problems, or solutions.

See the [CONTRIBUTING.md file](https://github.com/GhostCityGames/Midnight-Riders/blob/master/CONTRIBUTING.md)
for ways to make contributions.

Also, check out [DMS](https://github.com/GhostCityGames/dice-mechanic-sim), a simulator that playtests the game mechanics of Midnight Riders.

# Building Midnight Riders

If you would just like to download Midnight Riders without building, check out [DriveThruRPG](https://www.drivethrurpg.com/)
or our [releases page](https://github.com/GhostCityGames/Midnight-Riders/releases).

If you would like to build a custom copy of Midnight Riders, you will need [Python](https://www.python.org/),
[Sphinx](http://www.sphinx-doc.org/en/stable/), and [Calibre](https://calibre-ebook.com/).

* [Directions for installing Sphinx](http://www.sphinx-doc.org/en/stable/install.html)

* Open a terminal.

* Clone this project.

```git clone https://github.com/GhostCityGames/Midnight-Riders```

* Edit [Midnight-Riders/source/index.rst](https://github.com/GhostCityGames/Midnight-Riders/blob/master/source/index.rst)

* Build the epub file.

```sphinx-build -b epub source build```

* Convert epub to mobi.

```ebook-convert build/MidnightRiders.epub build/MidnightRiders.mobi```

* Open the resulting [epub file](https://github.com/GhostCityGames/Midnight-Riders/blob/master/build/MidnightRiders.epub)
with calibre.

```ebook-viewer build/MidnightRiders.epub```
