  # ngraph.path

This is the fork of the great and fery fast [pathFinder](https://github.com/anvaka/ngraph.path) by anvaka.

The only difference is that **aStar** method from it returns an object with distance field.
That affects it's usage a bit:
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
