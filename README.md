# GenRandom
[![travis build](https://img.shields.io/travis/jwright04/genrandom.svg?style=flat-square)](https://travis-ci.org/jwright04/genrandom/builds)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://en.wikipedia.org/wiki/MIT_License)


## Description

A custom random number generator.

### Installation

```
npm install genrandom --save
```


### Import
```
import { rNumber, rNumChar } from 'genrandom'
```

### Usage Examples
#### Return a random number n characters long
```
rNumber(10) // <= 8210706073
```

```
type of rNumber(10) // <= number
```

#### Return a string of random numbers with multiple segments
```
rNumber(3, 3, 10) // <= 615-807-8046602819
```

```
type of rNumber(3, 3, 10) // <= string
```
#### Return a string containing numbers and characters
```
rNumChar(10) // <= wUDMJd1BRH
```

```
type of rNumChar(10) // <= string
```

#### Return a string containing numbers and characters with multiple segments
```
rNumChar(10, 2, 3) // <= mW13MGs4Vh-pq-Itb
```

```
type of rNumChar(10, 2, 3) // <= string
```


### Improvements and Bugs
If you find any issues or see something that can be improved? 
<https://github.com/jwright04/genrandom/issues>


### License
ISC