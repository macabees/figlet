# Figlet
Generates text banners, in a variety of typefaces, composed of conglomerations of smaller ASCII characters. 

## Figlet (Project Info)
[Website](https://en.wikipedia.org/wiki/FIGlet)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/figlet/)

## Build image
`$ docker build -t macabees/figlet:latest .`

## Docker Push
`$ docker push -t macabees/figlet:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm macabees/figlet "Hello World!"`
