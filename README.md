# C shared libray with Golang
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Sample project to generate a C sharid library from a go project. To generate the `header` file and the `.so` just 
execute the task

```sh
$ make build
````

This will generate a folder called `bin` with two files:

```sh
$ ls -la bin/
-rw-r--r--  1 javi  staff     1520  3 jun 16:28 library.h
-rw-r--r--  1 javi  staff  1461064  3 jun 16:28 library.so
```
> These files for default are called `library`

