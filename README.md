# dry
dry is wizardry with three.js

```
script(src="https://gnjo.github.io/dry/three.js")
script(src="https://gnjo.github.io/dry/dry.fn.js")
//fn.xyz
script(src="https://gnjo.github.io/dry/dry.js")
//dry(mac)

```
```
three.util.js
let w=320,h=240,fps=20,boxsize=10
let {camera,scene,light,renderer,ui,mesh,helper}=threeq(canvas,w,h,fps)
fps((time)=>{
 renderer.clear()
 renderer(camera,scene)
 draw(time,hud.ctx)
 renderer(hud.camera,hud.scene)
},20)
;

//mesh(forms,type,url or color,wire or edge)
let plane=mesh('p','basic','#00ff00',0)
let plane2=helper(plane)
scene.add(plane)
scene.add(plane2)

ui((time,ctx)=>{

});

```
```
//迷宮の生成方式
//１マスの大きさを決める。あらゆるものは、これを基準とする。
var boxsize=10
//座標を初期化した物体を生成する。初期化した座標は F00X00Y00.N
zeropos(geo,mat)

```
