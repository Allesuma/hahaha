<!DOCTYPE html>
<html>
	<head>
		<script>
			i = 0;
			x = [ "http://1.bp.blogspot.com/-xdHGOG59LCI/UjawN7V-deI/AAAAAAAABb8/v3dHRriJkjo/s1600/EUCL%E4%B8%8A%E5%8F%B0%E9%A0%98%E7%8D%8E01.jpg",
				  "http://4.bp.blogspot.com/-UKB9Pburh8I/Ujawb7t3wGI/AAAAAAAABcE/2h3OMM1sb-0/s1600/Frocius+Android%E4%B8%8A%E5%8F%B0%E9%A0%98%E7%8D%8E01.jpg",
				  "http://4.bp.blogspot.com/-p-YNGTeHwM0/UjawjF1fwoI/AAAAAAAABcM/YrenoO-Mcg8/s1600/devabchb%E4%B8%8A%E5%8F%B0%E9%A0%98%E7%8D%8E01.jpg",
				  "http://2.bp.blogspot.com/-xPreUlrSYv8/UjayQmzNzPI/AAAAAAAABcY/AxJVYPKmVxI/s1600/A+Team%E5%B1%95%E7%A4%BA%E6%94%A4%E4%BD%8D01.jpg" ]
			function f(y)
			{
				i = i + y;
				if(i>3)
				{document.getElementById("demo").innerHTML = "這是最後一張了喔 O口O!!!"; i=3}
				else if(i<0)
				{document.getElementById("demo").innerHTML = "前面沒東西了喔 哭哭TAT"; i=0}
				else
				{document.getElementById("demo").innerHTML = "<img src='" + x[i] + "' width='100%'>" }
			}
		</script>
	</head>

<body>

<div id="demo">
	<img src='http://1.bp.blogspot.com/-xdHGOG59LCI/UjawN7V-deI/AAAAAAAABb8/v3dHRriJkjo/s1600/EUCL%E4%B8%8A%E5%8F%B0%E9%A0%98%E7%8D%8E01.jpg' width='100%'>
</div>
<a href="javascript:f(-1);">上一張</a>
<a href="javascript:f(1);">下一張</a>

</body>
</html>
