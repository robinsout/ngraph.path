  # ngraph.path

This is the fork of the great and fery fast [pathFinder](https://github.com/anvaka/ngraph.path) by anvaka.

The only difference is that **aStar** method from it returns an object with distance field.
This a bit affects it's usage:
``` js
pathFinder.find(fromNodeId, toNodeId)
```
returns an object:
``` js
{
  path,
  distance,
}
```
