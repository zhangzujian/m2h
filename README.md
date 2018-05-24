# m2h
Command line tool to convert markdown to HTML using redcarpet and rouge

## Usage

```text
m2h [-s <STYLEFILE>...] [-t <PAGETITLE>] [-o <OUTPUTFILE>] <file>
```

Example:

```sh
m2h -s github.css -t "m2h - README" -o README.html README.md 
```
