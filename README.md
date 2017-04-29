<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>IFE JavaScript Task 01</title>
  </head>
<body>

  <label>请输入北京今天空气质量：<input id="aqi-input" type="text"></label>
  <button id="button">确认填写</button>

  <div>您输入的值是：<span id="aqi-display">尚无录入</span></div>

<script type="text/javascript">

(function() {
  /*    
  在注释下方写下代码
  给按钮button绑定一个点击事件
  在事件处理函数中
  获取aqi-input输入的值，并显示在aqi-display中
  */
  
 /* var but=getElementById('button');
  var val=getElementById('aqi-input');
  var xs=getElementById('aqi-display');
  but.onclick=function () {
  	xs.innerHTML=val.value;
  }*/
  
  var inp=document.getElementById('aqi-input');
  var btn=document.getElementById('button');
  var dsp=document.getElementById('aqi-display');
  btn.onclick=function () {
    dsp.innerHTML=inp.value; 
  }
  
  /*var butt=document.getElementById("button");
  var inco=document.getElementById("aqi-input");
  var cont=document.getElementById("aqi-display");
  butt.onclick=function(){
    cont.innerHTML=inco.value;
  };
*/
})();

</script>
</body>
</html>

