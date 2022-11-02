# How to run this tiddlywiki in the background

Run :

```
nohup /usr/local/bin/tiddlywiki ~/myWiki --listen host=0.0.0.0 password=<> username=<> &
```

# To find the running process

Run:

```
ps -aux | grep tiddly
```

# To kill the process

Run:

```
kill <pid>
```
