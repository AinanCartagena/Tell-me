# Tell-me
<html>
<head>
<title></title>

<script type="text/javascript">
flag=1
function f1()
{
    alert("YEY THANK U LOVE U >_<")
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1>Do you love me?</h1>
<img src="https://i.gifer.com/origin/e9/e9a505d1d8604f350e9df5b33b551493_w200.gif" height="200" />
<h1 style=""></h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" YES " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" NO " onMouseOver="f()" />
</div>

</body>
</html>
