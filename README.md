# tmux_memo
tmux memo

# Install 

tmux by Yum is old; 1.8.
Recommend to install 2.7 latest version trough download tar ball.

Install libevent

```
$ wget https://github.com/downloads/libevent/libevent/libevent-2.0.21-stable.tar.gz

$ tar xvzf libevent-2.0.21-stable.tar.gz

$ cd libevent-2.0.21-stable

$ ./configure

$ make

$ make install
```

Install tmux latest version via github (https://github.com/tmux/tmux).

```
$ wget https://github.com/tmux/tmux/releases/download/2.7/tmux-2.7.tar.gz

$ tar xvzf tmux-2.7.tar.gz

$ cd tmux-2.7

$ ./configure && make

$ sudo make install

$ vi ~./bashrc

alias tmux="LD_LIBRARY_PATH=/usr/local/lib /usr/local/bin/tmux"

$ source  ~./bashrc
```

# Default Commands

start tmux

```
tmux
```

split vertical pain

```
Ctr + b -> %
```

split hirizontal pain

```
Ctr + b -> "
```

move to next pain

```
Ctr + b -> o
```

move to a numbered pain

```
Ctr + b -> q -> <number>  
```

remove a pain

```
Ctr + b -> x
or
exit
```
