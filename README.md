**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [bashnotes](#)
		- [Convert a row to column](#)


# bashnotes
Collection of day to day bash procedures 

[TOC]

### Convert a row to column 

```
#assuming the delimiter is tab
sed s/\\t/\\n/g file
```
