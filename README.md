# bl3p-cli
Bl3ep - Dutch Bitonic bitcoin exchange command line interface price viewer written in bash

The bl3p tool connects to the public bl3p API and retrieve the price as an integer, compares with previous value and shows it in green or red color, every dot currently represents 5 seconds.


## How it works 

just run the tool from command line, if you are afraid, as I know you are, just read it to see how simple it is.


```shell
git clone https://github.com/renasboy/bl3p-cli
cd bl3p-cli
cat -e bl3p

```

if you fell confident with what you read, just execute it


```shell
./bl3p

```

it will show a list as

```shell
.....
6500
...............
6499
...................
6459
.
6474
..
6466
..............................
6487
.
6500
.......
6533
.........
6568
..............................................
6528
............
6500
...............................................
6547
.....
6515
..........................
6554
..................................
6590
................
6550
............................
6574
.
6585
...........
6550
.....................
6570
.............................................................................

```
