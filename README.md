box2dweb-commonjs
=================

CommonJS version of Box2dWeb both for npm and component(1)  
The patch to support Node.js was prepared by [Christoph Schulz](http://code.google.com/p/box2dweb/issues/detail?id=22)

Usage
------------

Both in component(1) or node.js just
```javascript
var box2d = require('box2dweb-commonjs');
var world = new box2d.b2World(....)
```

Add Repo Joint
------------

To use it just..
```javascript
var box2d = require('box2dweb-commonjs');
var world = new box2d.b2World(....)
var b2RopeJointDef = box2d.Dynamics.Joints.b2RopeJointDef;

var jd = new b2RopeJointDef();
jd.Initialize(obj1, obj2, pos1, pos2, maxLangth);
world.CreateJoint(jd);
```
