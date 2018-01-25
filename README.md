polymer-sortablejs
-------------------


### Why Fork?
`polymer-sortablejs` element changed items position in source array when items position is changed.
due to this polymer binding is failed. So one item updates was reflect on different item.


## Release 0.1.4  (2 May, 2017) 
  - If `orderFieldName` is defined then set item's order based on its new position and set updated items model as `items` in event data
  - Set `preventOnFilter` value as false
  - Take new property `forcePolymer` to force `Sortable` js to use Polymer method instead of other library to clone element
	

[![Gitter][gitter-image]][gitter-url]


A Polymer binding to [SortableJS](https://github.com/RubaXa/Sortable/).

Demo: http://rubaxa.github.io/Sortable/

### Usage

```html

<link rel="import" href="bower_components/polymer-sortablejs/polymer-sortablejs.html"/>

<sortable-js>
  <template is="dom-repeat" items={{items}}>
    <div>{{item}}</div>
  </template>
</sortable-js>
```

### Install

```
$ bower install polymer-sortablejs
```

[gitter-image]: http://img.shields.io/badge/+%20GITTER-JOIN%20CHAT%20%E2%86%92-1DCE73.svg?style=flat-square
[gitter-url]: https://gitter.im/sortable-js/polymer-sortablejs
