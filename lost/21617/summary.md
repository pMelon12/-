昨天用canvas画了五角星和rgby。
###画五角星
canvas W200 H200 iDwjx

var a=document.getElementById('wjx').getContext('2d');
//content F Context T
a.moveTo(0,50);
a.lineTo(200,50);
a.lineTo(40,200);
a.lineTo(100,0);
a.lineTo(160,200);
a.lineTo(0,50);
a.stroke();

###画rgby
//a.style='red';
a.fillStyle='red';
//a.rect
a.fillRect(0,0,100,100);
a.fillStyle='blue';
a.fillRect(100,0,200,100);
a.fillStyle='green';
a.fillRect(0,100,100,200);
a.fillStyle='yellow';
a.fillRect(100,100,200,200);
//四个矩形面积一样
a.fill()
//在红方块里画一个黄圆圈;若是画黄实心圆不用设置storke线条颜色，它的填充颜色是画笔最后的颜色

////以下代码不生效
a.beginPath();
a.arc(50,50,50,2*Math.PI);
a.storke.style="yellow"
a.storke();
