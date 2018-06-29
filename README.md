![logo-trans](https://user-images.githubusercontent.com/16310793/42029324-df117c42-7ad7-11e8-8d3e-9c6cd8822d6c.png)
[![Build Status](https://travis-ci.org/romankh3/image-comparison.svg?branch=master)](https://travis-ci.org/romankh3/image-comparison) [![Coverage Status](https://coveralls.io/repos/github/romankh3/image-comparison/badge.svg?branch=master)](https://coveralls.io/github/romankh3/image-comparison?branch=master) [![BCH compliance](https://bettercodehub.com/edge/badge/romankh3/image-comparison?branch=master)](https://bettercodehub.com/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/romankh3/image-comparison/pulls)

## About
The program in Java that compares any 2 images and shows the differences visually by drawing rectangles.

## Requirements
* Implementation is using only standard core language and platform features, no 3rd party libraries and plagiarized code is permitted.
* Pixels (with the same coordinates in two images) can be visually similar, but have different values of RGB. 2 pixels are considered to be "different" if they differ more than 10% from each other.
* The output of the comparison is a copy of one of the images The differences are outlined with red rectangles as shown below.
* No third party libraries or borrowed code are in usage.

## Getting Started
To run project open `Terminal` and write: 
```
$ git clone https://github.com/romankh3/image-comparison
$ cd image-comparison
$ ./run.sh
```


You will get the result of comparing two images.
The images, which are using:

### Image1

![image1](https://user-images.githubusercontent.com/16310793/28955567-52edeabe-78f0-11e7-8bb2-d435c8df23ff.png)

### Image2

![image2](https://user-images.githubusercontent.com/16310793/28955566-52ead892-78f0-11e7-993c-847350da0bf8.png)

##### Do you see the difference?

### Result

![result](https://user-images.githubusercontent.com/16310793/28955568-52f23e02-78f0-11e7-92c5-07602b6a0887.png)

Also you can get them from:

```
${projectDir}/src/main/resources/image1.png
${projectDir}/src/main/resources/image2.png
```
```
${projectDir}/build/result.png
```

## License:
This project is unlicense - see the [LICENSE](LICENSE) file for details

### Thanks [@dee-y](https://github.com/dee-y) for designing this logo!
