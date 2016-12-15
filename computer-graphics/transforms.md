# Transforms
> 2016-12-15

## Introduction

- Transforms are used to scale, translate, reflect, shear and rotate 2D and 3D
  objects.
- `P(x,y)` is transformed into `P'(x',y')` using
```
x'=ax+by+e
y'=cx+dy+f
```
- `P(x,y,z)` is transformed into `P'(x',y',z')` using
```
x'=ax+by+cz+k
y'=dx+ey+fz+l
z'=gx+hy+jz+m
```
- It is convenient to express transforms as matrices.

## 2D Transforms

### Translation

-