<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
    margin: 0 auto;
    max-width: 800px;
    padding: 0 20px;
}

.container {
    border: 2px solid #dedede;
    background-color: #f1f1f1;
    border-radius: 5px;
    padding: 10px;
    margin: 10px 0;
}

.darker {
    border-color: #ccc;
    background-color: #ddd;
}

.container::after {
    content: "";
    clear: both;
    display: table;
}

.container img {
    float: left;
    max-width: 60px;
    width: 100%;
    margin-right: 20px;
    border-radius: 50%;
}

.container img.right {
    float: right;
    margin-left: 20px;
    margin-right: 0;
}

.time-right {
    float: right;
    color: #aaa;
}

.time-left {
    float: left;
    color: #999;
}
</style>
</head>
<body>

<h2>Chat</h2>

<div class="container">
    <img src="/w3imges/bandmember.jpg" alt="Avatar" style="width:100%;">
    <p> kin khao lah war?</p>
    <span class="time-right">80:00</span>
</div>

<div class="container darker">
    <img src="/w3images/avatar_g2.jpg" alt="Avatar" class="right" style="width:100%">
    <p>Doi ph de kin lah !</p>
    <span class="time-left">08:01</span>
</div>

<div class="container">
    <img src="/w3imges/bandmember.jpg" alt="Avatar" style="width:100%;">
    <p>pai lin sh br mue laeng?</p>
    <span class="time-right">80:02</span>
</div>

<div class="container darker">
    <img src="/w3images/avatar_g2.jpg" alt="Avatar" class="right" style="width:100%">
    <p>war c pai ng lin.pai nam kh br?</p>
    <span class="time-left">08:05</span>
</div>

</body>
</html>
