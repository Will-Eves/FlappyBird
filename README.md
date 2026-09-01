# About

The **index.html** file contains the entire game of flappy bird... In only **333 bytes**.

I made [this video](https://youtu.be/YWVgBLknHcg?si=EdNDEJZQziDPvCmL) on the development and how the code works.

# The Code

The code structure is relatively simple. It is written in HTML and JavaScript. There is just a canvas, and a script.

```html
<canvas width=600 height=450 id=b></canvas>
<script>
y=j=50,v=0,p=[],f=h=99,c=b.getContext`2d`,r=c.fillRect.bind(c),onclick=e=>v=-15,setInterval(`for(o of(b.width+=0,r(j,y,j,j),y+=v+=v<8,f++%h||p.push([200*Math.random()+h,600]),p))n=o[1]-=3,m=o[0],r(n,m-950,h,900),r(n,m+150,h,900),n<h&n>-j&(y<m-j||y>m+h)&&(p=[],f=y=v=0)`,25)
</script>
```
