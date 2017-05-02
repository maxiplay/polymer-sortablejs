polymer-sortablejs
-------------------


### Why Fork?
`polymer-sortablejs` element changed items position in source array when items position is changed.
due to this polymer binding is failed. So one item updates was reflect on different item.


## Release 0.1.4  (2 May, 2017) 
  - If `orderFieldName` is defined then set item's order based on its new position and set updated items model as `items` in event data
  - Set `preventOnFilter` value as false
  - Take new property `forcePolymer` to force `Sortable` js to use Polymer method instead of other library to clone element