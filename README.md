# 4point
A four point image manipulator

## How to use
```four_point_transform(x1, y1, x2, y2, x3, y3, x4, y4, tex, segments*, perspective*, z*)```
- x1, y1 - point 1
- x2, y2 - point 2
- x3, y3 - point 3
- x4, y4 - point 4
- tex - texture, sprite_get_texture(..), surface_get_texture(..) etc.
- segments - the more, the better quality, [optional, default is 5]
- perspective - fake perspective, [optional, default is true]
- z - depth, [optional, default is object's depth]

![sBez názvu](https://user-images.githubusercontent.com/68820052/164703365-83053361-f832-4510-9318-b107d2d4b375.png)
