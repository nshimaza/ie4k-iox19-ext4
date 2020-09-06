# ie4k-iox19-ext4
Testing IOx 1.9.0 on IE 4000.

## Build

On Linux with Docker, install ioxclient.  Do following.

```shell-sessions
$ cd dockerfile
$ sudo docker build -t ext4test .
...
$ cd ../app
$ sudo ioxclient docker package -p ext4 -r 10 ext4test .
```
