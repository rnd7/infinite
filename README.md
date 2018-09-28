# Lux & Lucid Infinite
Electron Application written for a video installation in 2017. It is basically a infinite zoom realized programmatically. The App picks random images from the assets directory changes the colors a bit and animates them towards the viewer. You can change some parameters during runtime. The App features rudimentary projection mapping capabilities. It's a quick and dirty solution just for one show, so don't expect too much.

## Installation
You need node and npm installed on your machine. It should work on all platforms electron supports. I only tested in on a linux machine.

```
npm install
```

## Run

```
npm start
```
## Screenshot

![slides](https://raw.githubusercontent.com/rnd7/infinite/master/doc/screenshot.png)

## Known issues
While images are loaded the animation might lag. This only happens, when a image is loaded for the first time.

## License

The images within the assets directory are all copyright by rnd7 and licensed under a Creative Commons Attribution-NonCommercial 4.0 International License. [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/) 
![Creative Commons License](http://creativecommons.org/licenses/by-nc/4.0/)

See the [LICENSE](LICENSE.md) file for software license rights and limitations (GPL-v3).
