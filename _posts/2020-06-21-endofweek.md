---
layout : post
title : second
date : 2020-06-21 19:30:00 +0900
categories: post
---


<body onmouseover="myOver()" onload="setInterval(function(){myTimer()},1000)">
    <div>
    <pre style="font-weight:bolder" id="randomClass">
    <a id="randomClass2" href="https://wati2.github.io/2020/06/16/2ndProject01.html" style="font-weight:bolder">와티 준비 참조</a>
        <hr>
        오늘 할것  🚩 (시작하기전)
        MongoDB + Express + React + NodeJS 이상...
        <hr>
    </pre>
    </div>
</body>

<script type="text/javascript">
    function myOver(){
        var colorCode = "#" + Math.round(Math.random() * 0xffffff).toString(16);

        document.getElementById("randomClass").style.color = colorCode;
    }
        function myTimer()
    {
        var colorCode = "#" + Math.round(Math.random() * 0xffffff).toString(16);

        document.getElementById("randomClass2").style.color = colorCode;
    }
</script>

