# A static site generator

Takes md files and images and transforms them into html files. 

Utilises Python HTTP server, set to run on port 8888 by default.

Contains unit test coverage which can be run with `tests.sh`

## How to run:
1. place md files in /content
2. place images in /static/images
3. run `run.sh`
4. go to http://localhost:8888 (or whatever port you set)

_Note: The public directory is cleaned on every run_
