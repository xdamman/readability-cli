# readability-cli

Read any web page from the command line using readability.js

## Install

    npm install -g readability-cli


## Usage

    readability http://techcrunch.com/2014/02/12/marc-andreessen-tech-is-still-recovering-from-a-depression

## Options

    -c, --color         use colors in the terminal to highlight title and subtitles
    -f, --format html   return the text of the page in html format (default is plain text)

    E.g. readability url --color
         readability url --format html
