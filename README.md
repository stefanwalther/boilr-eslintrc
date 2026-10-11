# boilr-eslintrc

> boilr template for an eslintrc file.

> **Retired / archived:** boilr templates predate AI coding tools and no longer make sense. This template is retired and this repository is archived read-only — it will receive no further updates. For new projects, use your AI coding tool to generate the files you need.

---

## Purpose
Default elint configuration for main source + test.

The following files are generated:

```
.
├── .eslintrc.json
└── test
    └── .eslintrc.json

1 directory, 2 files

```

## Installation
Install [boilr](https://github.com/tmrts/boilr) first.

Then use

```
$ boilr download stefanwalther/boilr-eslintrc <template-tag>
```

e.g.
```
$ boilr download stefanwalther/boilr-eslintrc boilr-eslintrc
```

## Usage
### Download the template

```
$ boilr template download stefanwalther/boilr-eslintrc <template-tag>
```

### Fork, modify locally and save it

```
$ git clone stefanwalther/boilr-eslintrc
```

cd into it, then

```
$ boilr template save $(PWD) <template-tag>

# e.g.
$ boilr template save $(PWD) boilr-eslintrc
```

if you have for force the local updates, use

```
$ boilr template save $(PWD) <template-tag> -f
```

### Use it

```
$ boilr template use boilr-eslintrc .
```

### Get all templates

Get a list of all - locally installed - templates:

```
$ boilr template list
```

## About

### Related projects
Some related projects:


### Author
**Stefan Walther**

* [twitter](http://twitter.com/waltherstefan)
* [github.com/stefanwalther](http://github.com/stefanwalther)
* [LinkedIn](https://www.linkedin.com/in/stefanwalther/)
* [qliksite.io](http://qliksite.io)

### License
MIT
