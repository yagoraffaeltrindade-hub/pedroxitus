<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Painel Gamer</title>
<style>
body{
    background:#0d0d0d;
    font-family:Arial;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    color:white;
}
.login, .panel{
    background:#111;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 20px red;
    width:300px;
}
input{
    width:100%;
    padding:8px;
    margin:10px 0;
    border:none;
    border-radius:5px;
}
button{
    width:100%;
    padding:10px;
    background:red;
    border:none;
    color:white;
    border-radius:5px;
    cursor:pointer;
}
.tabs button{
    width:23%;
    margin:2px;
}
.section{
    display:none;
    margin-top:10px;
}
.active{
    display:block;
}
.toggle{
    display:flex;
    justify-content:space-between;
    margin:5px 0;
}
</style>
</head>
<body>

<div class="login" id="login">
<h3>Digite a Key</h3>
<input type="password" id="keyInput" placeholder="Key">
<button onclick="checkKey()">Entrar</b
