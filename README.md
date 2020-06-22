# Spark Workshop

## Setup

- You need Scala and a Scala development environment of your choice.
- Clone this repository
- Download Spark from https://spark.apache.org/downloads.html. The latest version (3.0.0) and default package type is fine.
- Unpack the Spark archive in the top-level directory where you cloned this repository
- Change into that directory in your shell and run 

  ```bash
  ./bin/spark-shell --master local[2]
  ```
  
  If you see a Spark banner everything is correctly setup.


## Data

In the `data` directory:

- `disposable-income.tsv`: UK equivalised disposable income 1977-2012/13 in 2012/13 prices. Source: Office for National Statistics licensed under the Open Government Licence.

- `AUPERTH.txt` and `UKLONDON.txt`: Temperature data taken from the "all sites" data set at http://academic.udayton.edu/kissock/http/Weather/default.htm
