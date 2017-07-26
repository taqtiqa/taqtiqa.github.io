## Welcome to the TAQTIQA GitHub Pages

| Rkt Containers | Metrics                                   |
|----------------|-------------------------------------------|
|Rkt-Base        | [![Github All Rkt-Base Releases][1]]()    |
|Rkt-RRR-Base    | [![Github All Rkt-RRR-Base Releases][2]]()|
|Rkt-RRR-Tidy    | [![Github All Rkt-RRR-Tidy Releases][3]]()|

[1]:https://img.shields.io/github/downloads/taqtiqa/rkt-base/total.svg
[2]:https://img.shields.io/github/downloads/taqtiqa/rkt-rrr-base/total.svg
[3]:https://img.shields.io/github/downloads/taqtiqa/rkt-rrr-tidy/total.svg

## Rkt Base Status

| Code  | Build Status | Downloads |
|-------|--------------|-----------|
| Hardy | [![Travis Status][10a]]() | [![ACI Downloads][10b]]() |

[10a]:https://img.shields.io/travis/taqtiqa/rkt-base/0.0.0-0.svg
[10b]:https://img.shields.io/github/downloads/taqtiqa/rkt-base/0.0.0-0/total.svg

## Rkt Base Versions


## Rkt RRR Versions
The `taqtiqa.io/rkt-rrr-base:3.3.1+2` Rkt image will always rebuild 
with R 3.3.1 and R packages installed from the 2016-10-31 MRAN 
snapshot, corresponding to the last day that version of R was the 
most recent release on CRAN. MRAN snap shots exist from 2014-09-17.

|Rkt Image   | LTS / Branch | R version | M/*CRAN date  | Deb version     | Code     |
|------      |--------      |---------  |--------------|-----------------|----------|
|            |              | 3.4.1     |              | 3.4.1-2         | Angry    |
|            | 17.04        | 3.3.2     | 2017-03-05   | 3.3.2-1         | Zesty    |
|            | 16.10        | 3.3.1     | 2016-10-30   | 3.3.1-1build1   | Yakkety  |
|[![ By Release](https://img.shields.io/github/downloads/taqtiqa/rkt-base/3.4.1/total.svg)]() | 16.04.2 (LTS)| 3.2.3     | 2016-03-09   | 3.2.3-4         | Xenial   |
|            | 15.10        | 3.2.2     | 2015-12-10   | 3.2.2-1         | Wiley    |
|            | 15.04        | 3.1.2     | 2015-03-08   | 3.1.2-2         | Vivid    |
|            | 14.10        | 3.1.1     | 2014-10-30   | 3.1.1-1         | Utopic   |
|            | 14.04.4 (LTS)| 3.0.2     | *2014-03-05  | 3.0.2-1ubuntu1  | Trusty   |
|            | 13.10        | 3.0.1     | *2013-09-24  | 3.0.1-3ubuntu1  | Saucy    |
|            | 13.04        | 2.15.2    | *2013-02-28  | 2.15.2-1ubuntu1 | Raring   |
|            | 12.10        | 2.15.1    | *2012-06-21  | 2.15.1-5ubuntu1 | Quantal  |
|            | 12.04.5 (LTS)| 2.14.1    | *2012-02-28  | 2.14.1-1        | Precise  |
|            | 11.10        | 2.13.1    | *2011-09-29  | 2.13.1-1        | Oneiric  |
|            | 11.04        | 2.12.1    | *2011-02-24  | 2.12.1-1        | Natty    |
|            | 10.10        | 2.11.1    | *2010-10-14  | 2.11.1-2        | Maverick |
|            | 10.04.4 (LTS)| 2.10.1    | *2010-04-21  | 2.10.1-2        | Lucid    |
|            | 9.10         | 2.9.2     | *2009-10-25  | 2.9.2-3ubuntu1  | Karmic   |
|            | 9.04         | 2.8.1     | *2009-04-16  | 2.8.1-1         | Jaunty   |
|            | 8.10         | 2.7.1     | *2008-08-24  | 2.7.1-2         | Intrepid |
| [![ By Release](https://img.shields.io/github/downloads/taqtiqa/rkt-base/0.0.0-0/total.svg)]()           | 8.04.4  (LTS)| 2.6.2     | *2008-04-21  | 2.6.2-2         | Hardy    |
|            | 7.10         | NA        | NA           | NA              | Gutsy    |
|            | 7.04         | NA        | NA           | NA              | Feisty   |
|            | 6.10         | NA        | NA           | NA              | Edgy     |
|            | 6.06.2  (LTS)| NA        | NA           | NA              | Dapper   |
|            | 5.10         | NA        | NA           | NA              | Breezy   |
|            | 5.04         | NA        | NA           | NA              | Hoary    |
|            | 4.10         | NA        | NA           | NA              | Warty    |



Note the **last** release dates were obtained from the canaonical FTP server 
dates for the next version - 1 day. The release dates were given by:
````bash
$ lynx -dump http://cran.r-project.org/src/base/R-{0..3}/ | grep gz | grep -v http
````
The Deb version data comes from https://launchpad.net/r-project/trunk

## Rkt Base Statistics

| Rkt Image | Size | Build Status | Metrics |
|-------    |------|------   |---------     |
|3.4.1+0    |      | [![Travis branch](https://img.shields.io/travis/taqtiqa/rkt-base/3.4.1+0.svg)]()        |              |

