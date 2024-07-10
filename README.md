# Cordova-Slideshow

## Build Docker

```bash
docker -t build slideshow
```

## Build Application

```bash
# Add Android Platform
docker run -v .:/opt/src --rm Android-HTML-Slides-Show cordova platform add android

# Build
docker run -v .:/opt/src --rm Android-HTML-Slides-Show cordova build
```