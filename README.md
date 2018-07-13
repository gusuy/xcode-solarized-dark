# Solarized Dark Themes for Xcode

My own renditions of the Solarized Dark theme as a port for Xcode.

[Solarized Project Page](http://ethanschoonover.com/solarized)  
[Solarized Git Repo](https://github.com/altercation/solarized)

The Solarized Dark theme follows the official color scheme.

The Solarized Dark Higher Contrast theme deviates from the official color specs. I kept the background colors the same, but lightened all text fonts for slightly more contrast.

## Screenshots

#### Solarized Dark
![Solarized Dark](/img/solarized-dark.png?raw=true)
![Solarized Dark Settings](/img/solarized-dark-settings.png?raw=true)

#### Solarized Dark Higher Contrast
![Solarized Dark Higher Contrast](/img/solarized-dark-higher-contrast.png?raw=true)
![Solarized Dark Higher Contrast Settings](/img/solarized-dark-higher-contrast-settings.png?raw=true)

## Prerequisites

* Xcode 8 or 9  
.xccolortheme files aren't compatible with older versions of Xcode.

## Installation

#### Step 1

* Run the installation script

    ```
    ./install.sh
    ```

    **OR**

* Copy the desired .xccolortheme files into the following directory. Create the directory if it doesn't exist.

    ```
    ~/Library/Developer/Xcode/UserData/FontAndColorThemes
    ```

#### Step 2
* Restart Xcode

#### Step 3
* Select theme from Xcode Preferences -> Fonts & Colors


## Acknowledgments

* Other Solarized Xcode ports:
    * [stackia](https://github.com/stackia/solarized-xcode)
    * [ArtSabintsev](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode)
    * [hdoria](https://github.com/hdoria/xcode-themes)
* Higher contrast theme inspired by an iTerm2 port made by [heisters](https://gist.github.com/heisters/1015503).
