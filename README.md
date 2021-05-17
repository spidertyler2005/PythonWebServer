![Version](https://img.shields.io/badge/Version-0.1.2-green)
# Python WebServer

This is a very basic  webserver that can only handle `GET` requests as of now.

## Suported Files

|File Type|Into|
|-|-|
|.png|image/webp|
|.ico|image/webp|
|.jpg|image/webp|
|.html|text/html;charset=utf-8|
|.txt|plain;charset=utf-8|
|.css|text/html;charset=utf-8|

## How-to

You must put all files in `PageSrc/`. Then run `Main.py` in your terminal.

Lastly, go to whatever page you want by going to `localhost:1300/PAGENAME.EXTENSION`

## Redirections

Currently the only redirect redirects `/` -> `/index.html` but you can add as many as you want within the code.

## Config

You can edit the config by going into `/config/globalConfiguration.json`

## Custom 404
You need to create the file  `PageSrc/404Page.html` and fill it with the content of your 404 page.