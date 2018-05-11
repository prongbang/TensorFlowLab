# TensorFlow Lab

## Installing TensorFlow for Go
[https://www.tensorflow.org/install/install_go](https://www.tensorflow.org/install/install_go)

## Installing with Virtualenv
Install pip and Virtualenv by issuing the following commands:
```
 $ sudo easy_install pip
 $ pip install --upgrade virtualenv
```
Create a Virtualenv environment by issuing a command of one of the following formats:
```
 $ virtualenv --system-site-packages ~/tensorflow # for Python 2.7
 $ virtualenv --system-site-packages -p python3 ~/tensorflow # for Python 3.n
```

Activate the Virtualenv environment by issuing one of the following commands:
```

```

## Installing with Docker
Launch a Docker container that contains one of the TensorFlow binary images.
```
$ docker run -it -p 8888:8888 tensorflow/tensorflow
```

## Download the appropriate packages and their dependencies:
```
$ go get github.com/tensorflow/tensorflow/tensorflow/go
```

## Invoke `go test` as follows to validate the TensorFlow for Go installation:
```
$ go test github.com/tensorflow/tensorflow/tensorflow/go
```

## package tensorflow
[https://godoc.org/github.com/tensorflow/tensorflow/tensorflow/go#ex-package](https://godoc.org/github.com/tensorflow/tensorflow/tensorflow/go#ex-package)

## TensorFlow in Go
[https://github.com/tensorflow/tensorflow/blob/master/tensorflow/go/README.md](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/go/README.md)

## Run `hello_tf.go` by invoking the following command:
```
$ go run hello_tf.go
```

## Error
```
ld: library not found for -ltensorflow
clang: error: linker command failed with exit code 1 (use -v to see invocation)
```


## Reference
- [https://github.com/tensorflow/tensorflow/blob/master/tensorflow/go/README.md](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/go/README.md)

