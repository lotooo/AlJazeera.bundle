AlJazeera.bundle
================

Channel to watch Al Jazeera live from Plex

Manual Installation: with git
=============================
* Open a Terminal
* Execute the following commands:

```bash
  # mkdir github
  # cd github
  # git clone https://github.com/lotooo/AlJazeera.bundle.git
  # cd
  # rm -fr $PLEX_FOLDER/Plug-ins/AlJazeera.bundle
  # ln -s ~/github/AlJazeera.bundle/ $PLEX_FOLDER/Plug-ins/AlJazeera.bundle
```

* Close the Terminal program

To update the plugin:
* Open a Terminal
* Execute the following commands:

```bash
  # cd github/AlJazeera.bundle
  # git pull
```

* Close the Terminal program

Manual installation : without git
================================
* Download zip file from here: https://github.com/lotooo/AlJazeera.bundle/archive/master.zip
* Unzip the file
* Move the unzipped folder to your home directory into a folder called github and rename the unzipped folder to AlJazeera.bundle (removing the -master suffix)
* Open a Terminal
* Execute the following commands

```bash
  # rm -fr $PLEX_FOLDER/Plug-ins/AlJazeera.bundle
  # ln -s ~/github/AlJazeera.bundle/ $PLEX_FOLDER/Plug-ins/AlJazeera.bundle
```

To update the plugin.
Redownload the zip file and replace the .bundle file found here: github/AlJazeera.bundle
