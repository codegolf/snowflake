# snowflake

A random snowflake generator using < 200 bytes of HTML and JavaScript.

Demo:  https://codegolf.github.io/snowflake

![image](https://cloud.githubusercontent.com/assets/1521/12111399/4189b37e-b395-11e5-9190-2af5a3b1b363.png)

### Source

```html
<canvas id=b><svg onload='with(Math)
for(I=Y=0;Y++<(n=70);I=random()-1.9&
I+1)for(i=12;i--;C(-X))j=i>5&&I,C=(X
)=>b.getContext("2d").fillRect(n+X,s
*j+c*Y+n,1,1),C(X=(c=cos(a=PI/3*i))*
j-(s=sin(a))*Y)'>
```
