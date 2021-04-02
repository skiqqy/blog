# Blog ~ A simple static blog generator.

## Usage

```
$ blog -h
```

## Skup Markup

The skup langauge (standing for skiqqy markup) is rather simple, and it is used
to type set the blog posts, below you will find the basic syntax for skup.

Please note this is constantly being updated.

### Title
To set the tile for a post simply write `TITLE. <your title>`

### Blocks
To wrap text in a block do the following,
```
SBLOCK. <Block Title>
This text will be placed inside a block.
EBLOCK
```
Note that all other skup commands work inside blocks (except for nesting
blocks).

### Links/Pictures
To create a hyperlink:
```
a/skiqqy.xyz/my website/
```

To create a picture link:
```
p/path/to/picture//Backup Name/
```

### Misc commands
These are simple commands that dont need an entire section dedicated to them.

* `\\` Force a newline.
