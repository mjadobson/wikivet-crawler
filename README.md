WikiVet Crawler
===============

Intro
-----

This is a simple CLI that crawls wikivet for quizzes and lumps them in a JSON file.

Also bundled is a script that converts the generated JSON file into moodle xml files.

Install
-------

`npm install -g wikivet-crawler`

Usage
-----

```
  Usage: wvc [options] [command]

  Commands:

    crawl                  Crawl WikiVet for quizzes
    convert                Convert JSON to moodle XML
    help [cmd]             display help for [cmd]

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```

```
  Usage: wvc-crawl [options]

  Options:

    -h, --help          output usage information
    -o, --output <out>  Destination for quizzes. Default: quizzes.json
    -nl, --nolog        Don't log
```

```
  Usage: wvc-convert [options]

  Options:

    -h, --help          output usage information
    -i, --input <in>    Source JSON file
    -o, --output <out>  Destination dir for 'moodle_xml' dir. Default: current working dir
```

Author
------

Matthew Dobson (mjadobson@gmail.com)
