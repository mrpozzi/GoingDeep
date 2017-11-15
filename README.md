# GoingDeep
Deep Learning Play-Ground



## AWS Commands

### t2

```
aws-get-t2
aws-ip
aws-start
aws-ssh
aws-stop

```


http://52.27.251.111:8888/


`dl_course`

### p2

```
aws-get-p2

```




## tmux Cheatsheet


`tmux new -s myname`

`tmux a -t myname          #by name `
`tmux a 4                  #by number (in this case 4)`

`tmux ls`


`tmux kill-session -t myname`


```
Panes

 %                          vertical split
 "                          horizontal split
 d                          detach from session  (it keeps running in the background)
 x                          kill pane
 Up/Down/Left/Right         move between panes
 : + resize-pane -D         Resizes the current pane down
 : + resize-pane -U         Resizes the current pane upward
 : + resize-pane -L         Resizes the current pane left
 : + resize-pane -R         Resizes the current pane right
 : + resize-pane -D 20      Resizes the current pane down by 20 cells
Windows

 c     create window
 w     list windows     #you can also use this to select windows
 n     next window
 p     previous window
 &     kill window
 ,     rename window

1. `Ctrl+b "` - split pane horizontally.
2. `Ctrl+b %` - split pane vertically.
3. `Ctrl+b arrow key` - switch pane.
4. `Hold Ctrl+b , don't release it and hold one of the arrow keys` - resize pane.
5. `Ctrl+b c` - (c)reate a new window.
6. `Ctrl+b n` - move to the (n)ext window.
```


## Kaggle CLI

`pip install kaggle-cli`


* `dogs-vs-cats-redux-kernels-edition`
* `noaa-fisheries-steller-sea-lion-population-count`
* `digit-recognizer`

```
kg config -g -u mrpozzi -c competition -p password 
kg download
kg submit 'submission1.csv' -c 'dogs-vs-cats-redux-kernels-edition'
```
