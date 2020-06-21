---
layout : post
title : second
date : 2020-06-21 19:30:00 +0900
categories: post
---
<head>
    <style type="text/css">
    a:link { color: red; text-decoration: none;}
    a:visited { color: black; text-decoration: none;}
    a:hover { color: blue; text-decoration: underline;}
    </style>
</head>
<body onmouseover="myOver()" onload="setInterval(function(){myTimer()},1000)">
    <div>
        <a id="randomClass2" href="https://wati2.github.io/2020/06/16/2ndProject01.html" style="font-weight:bolder">와티 준비 참조</a>
        <hr>
        <pre style="font-weight:bolder; background-color:#aaaaaa;" id="randomClass">
            오늘 할것  🚩 (시작하기전)
            MongoDB + Express + React + NodeJS 이상...
        </pre>
        <hr>
    </div>
</body>
1. <a href="https://javacpro.tistory.com/65">몽고 디비 참조</a> <br>
- Collection 은 Document 의 그룹이며  RDMS 의 테이블과 비슷하다.
- Document 는 키와 값으로 된 하나의 문서를 말한다. RDMS 의 Row 의 개념과 비슷하다.
- 해당 Collection 에 Document 를 추가하는 명령어 <b>db.user.insert({key:value,key:value})</b> 와 같이 입력
- key 는 이름(name) , 나이(age) , 등등 속성에 관한 내용이며 해당 속성의 값이 value
MongoDB Database Collection Document 이란 무엇인가?



몽고DB는 크로스 플랫폼의 document 지향 데이터베이스입니다.

높은 성능(high perfomence) , 높은 사용성 ( high availability ) , 그리고 쉬운 확장성 (easy scalaility) 을 제공합니다.

몽고DB는 아래와같이 구성됩니다.



Database , Collection, Document



그렇다면 위 3가지의 의미를 알아보도록 하자



1. Database



- 데이터베이스는 컬렉션의 물리적 컨테이너 입니다. 하나의 데이터베이스에는 보통 여러개의 컬렉션을 가지고 있습니다.



2. Collection



- 컬렉션은 몽고DB Document 의 그룹이며 RDBMS 의 예를 들면 Table 과 개념과 유사합니다.

- 컬렉션은 단일 데이터베이스에 존재합니다.

- 컬렉션은 스키마를 강요하지 않습니다. 따라서 컬렉션 내부의 도큐먼트는 서로 다른 필드를 가질수 있습니다.

- 컬렉션 안에 도큐먼트는 일반적으로 서로 유사한 하거나 관련된 목적이 있습니다.



3. Document



- Docuemtn 는 하나의 키(key) 와 값(value)의 집합으로 이루어져 있으며 동적 스키마 입니다.

- 동적 스키마는 동일한 컬랙션 내의 도큐먼트가 동일한 필드 또는 구조를 가지필요 없을을 의미한다.

- 그리고 동일한 필드안에 다른타입의 데이타를 보유할수 있음을 의미합니다.

몽고DB는 크로스 플랫폼의 document 지향 데이터베이스입니다.

높은 성능(high perfomence) , 높은 사용성 ( high availability ) , 그리고 쉬운 확장성 (easy scalaility) 을 제공합니다.

몽고DB는 아래와같이 구성됩니다.

Database , Collection, Document
1. Database
- 데이터베이스는 컬렉션의 물리적 컨테이너 입니다. 하나의 데이터베이스에는 보통 여러개의 컬렉션을 가지고 있습니다.
2. Collection
- 컬렉션은 몽고DB Document 의 그룹이며 RDBMS 의 예를 들면 Table 과 개념과 유사합니다.
- 컬렉션은 단일 데이터베이스에 존재합니다.
- 컬렉션은 스키마를 강요하지 않습니다. 따라서 컬렉션 내부의 도큐먼트는 서로 다른 필드를 가질수 있습니다.
- 컬렉션 안에 도큐먼트는 일반적으로 서로 유사한 하거나 관련된 목적이 있습니다.
3. Document
- Docuemtn 는 하나의 키(key) 와 값(value)의 집합으로 이루어져 있으며 동적 스키마 입니다.
- 동적 스키마는 동일한 컬랙션 내의 도큐먼트가 동일한 필드 또는 구조를 가지필요 없을을 의미한다.
- 그리고 동일한 필드안에 다른타입의 데이타를 보유할수 있음을 의미합니다.

<table><tr><td style="width: 392px; height: 24px; border-width: 1px; border-style: solid; border-color: rgb(204, 204, 204); background-color: rgb(5, 0, 153);"><p style="text-align: center;"><span style="color: rgb(255, 255, 255); font-size: 12pt; font-family: &quot;맑은 고딕&quot;, sans-serif;"><b>&nbsp;RDBMS</b></span></p></td>
<td style="width: 392px; height: 24px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204); border-top: 1px solid rgb(204, 204, 204); background-color: rgb(0, 51, 153);"><p style="text-align: center;"><span style="color: rgb(255, 255, 255); font-size: 12pt; font-family: &quot;맑은 고딕&quot;, sans-serif;"><b>&nbsp;MongoDB</b></span></p></td>
</tr>
<tr><td style="width: 392px; height: 25px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204); border-left: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Database</span></p></td>
<td style="width: 392px; height: 25px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Database</span></p></td>
</tr>
<tr><td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204); border-left: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Table</span></p></td>
<td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Collection</span></p></td>
</tr>
<tr><td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204); border-left: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Tuple/Row</span></p></td>
<td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Document</span></p></td>
</tr>
<tr><td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204); border-left: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Column</span></p></td>
<td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Field</span></p></td>
</tr>
<tr><td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204); border-left: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Table Join</span></p></td>
<td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Embedded Documents</span></p></td>
</tr>
<tr><td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204); border-left: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Primary Key</span></p></td>
<td style="width: 392px; height: 28px; border-bottom: 1px solid rgb(204, 204, 204); border-right: 1px solid rgb(204, 204, 204);"><p style="text-align: center;"><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">&nbsp;Primary Key ( </span><span style="font-size: 11pt; font-family: &quot;맑은 고딕&quot;, sans-serif;">Default _id )</span></p></td>
</tr>
</table>

출처: https://javacpro.tistory.com/66 [버물리의 IT공부]


<hr>
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

