---
layout : post
title : second
date : 2020-06-21 19:30:00 +0900
categories: post
---


<body onmouseover="myFunction()">
    <div>
    <pre onload="Onload()" id="randomClass">
    <a style="color:black" href="https://wati2.github.io/2020/06/16/2ndProject01.html"> 와티 준비 참조</a>
        <hr>
        오늘 할것  🚩 (시작하기전)
        MongoDB + Express + React + NodeJS 이상...
        <hr>
    </pre>
    </div>
</body>

<script type="text/javascript">
    function myFunction(){
        var colorCode = "#" + Math.round(Math.random() * 0xffffff).toString(16);

        document.getElementById("randomClass").style.color = colorCode;
    }
</script>

