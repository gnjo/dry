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
threeq.js
let w=320,h=240,fps=20,boxsize=10,canvas=document.querySelector('canvas')
let {camera,scene,light,ui,mesh,helper}=threeq(canvas,w,h,fps,boxsize)
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
;(function(root){
 function entry(canvas,w,h,fps,boxsize){
  let o={}
 
  o.fpsf
  return init(),o
 }
 root.threeq=entry
}(this);

```

```
//迷宮の生成方式
//１マスの大きさを決める。あらゆるものは、これを基準とする。
var boxsize=10
//座標を初期化した物体を生成する。初期化した座標は F00X00Y00.N
zeropos(geo,mat)

```

```

let scene,camera,light,cbox
let boxsize=10
//charser(position0,rotation0,movesize,cameraoffset) //cameraoffset
let c=chaser([0,0,0],[0,0,0],boxsize,[0,0,boxsize*-0.49]) 
c.czero //axis
cbox=c.cbox
light=c.light
camera=c.camera
scene=c.scene
;
c.addr
c.footsteps //addrary
c.zeropos//
c.zerorot// 
c.cameraoffset//
c.moving
c.move(order,time)  //^v<> ud lr or F00X00Y00.N
o.update//

if(c.moving)
 c.update()//chase recalc


```










