# erlToy
An OTP application, a simple game demo

# Build & Run
* get rebar3 and put it into woker dir
```shell
$ wget https://s3.amazonaws.com/rebar3/rebar3 && chmod +x rebar3
$ mv rebar3 $DIR/
$ cd $DIR
```

* change script permissions
```shell
$ chmod +x gamectl && chmod +x apps/game/script/*.*
```
* build
```shell
$ make
```
* run
```
$ ./gamectl start
```
* run robot
```shell
$ ./gamectl robot
```
then
```erlang
(robot@127.0.0.1)1> robot_ctl:command({do_robot, 1}).
(robot@127.0.0.1)1> robot_ctl:command({do_robot_n, 10}).
```
