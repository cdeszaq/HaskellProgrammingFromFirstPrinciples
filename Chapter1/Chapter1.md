Chapter 1
=========

Exercises
---------

### Combinators

1. `λx.xxx`: Combinator
2. `λxy.zx`: Not Combinator (z free)
3. `λxyz.xy(zx)`: Combinator
4. `λxyz.xy(zxy)`:Combinator
5. `λxy.xy(zxy)`: Not Combinator (z free)

### Beta Reduce Exercises

1. `λ(abc.cba)zz(λwv.w)`  
   `λ(bc.cbz)z(λwv.w)`  
   `λ(c.czz)(λwv.w)`  
   `(λwv.w)zz`  
   `(λv.z)z`  
   `z`  

2. `(λx.λy.xyy)(λa.a)b`  
   `(λy.(λa.a)yy)b`  
   `(λa.a)bb`  
   `bb`  

3. `(λy.y)(λx.xx)(λz.zq)`  
   `(λx.xx)(λz.zq)`  
   `(λz.zq)(λz.zq)`  
   `(λz.zq)q`  
   `qq`  

4. `(λz.z)(λz.zz)(λz.zy)`  
   `(λz.zz)(λz.zy)`  
   `(λz.zy)(λz.zy)`  
   `(λz.zy)y`  
   `yy`  

5. `(λx.λy.xyy)(λy.y)y`  
   `(λy.(λy.y)yy)y`  
   `(λy.y)yy`  
   `yy`  

6. `(λa.aa)(λb.ba)c`
   `(λb.ba)(λb.ba)c`  
   `(λb.ba)ac`  
   `aac`  

7. `(λxyz.xz(yz))(λx.z)(λx.a)`  
   `(λyz1.(λx.z)z1(yz1))(λx.a)`  
   `(λz1.(λx.z)z1((λx.a)z1))`  
   `(λz1.z((λx.a)z1))`  
   `(λz1.za)`  
