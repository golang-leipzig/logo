# Logo for the Cloud-Native and Golang Leipzig Meetup

![cloud-native and golang leipzig meetup logo](./cloud-native-and-golang-leipzig-preview.png)

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Convert SVG to PNG

The following instructions assumes that [ImageMagick](https://www.imagemagick.org/) is available:

```bash
$ convert -background none cloud-native-and-golang-leipzig.{svg,png}
```

## Variant 1 for [meetup.com group](https://www.meetup.com/de-DE/Leipzig-Golang-and-Cloud/)

```bash
$ convert -resize 800x -background none cloud-native-and-golang-leipzig.{svg,png}
$ convert cloud-native-and-golang-leipzig.png -gravity east -extent 1200x800 cloud-native-and-golang-leipzig-meetup.png
```
