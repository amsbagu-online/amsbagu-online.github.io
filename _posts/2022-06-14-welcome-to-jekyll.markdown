---
layout: post
title:  "Welcome to my ideas!"
date:   2022-06-14 21:24:47 -0300
categories: html css
---
<style> 
  .fullcard{
    border: 1px solid #ccc;
    width: 400px;
    height: 210px;
    /* background-color: ; */
    font-family: 'EB Garamond', serif;
  }
  .topoesq{
    padding: 10px;
    margin: 5px 0px 0px 5px;
    /*background-color: pink;
    border: 1px solid #ccc;*/
    position: relative;
    float: left;
  }
  .topodir{
    padding: 10px;
    margin: 5px 5px 0px 0px;
  /* background-color: pink;
    border: 1px solid #ccc;*/
    position: relative;
    float: right;
    font-size: 13px;
  }
  .merg{
    font-size: 7.5px;
  }
  .centro{
    position: relative;
    top: 40%;
    width: 100%;
    text-align: center;
  }
  .cap{
    font-size: 15px;
  }
  .vp{
    margin: 3px;
    font-size: 11px;
  }
  .rodape{
    position: relative;
    width: 390px;
    height: 20px;
    margin: 140px 0px 0px 5px;
    /*background-color: pink;*/
    font-size: 11px;
    text-align: center;
  }
  .child{
    position: relative;
    height: 200px;
  }
  .parent {
    display: flex;
    align-items: center;
    justify-content: center;
  }
 /* .texto {
    width: 700px;
    display: block;
    margin-left: 23%;
}*/
</style>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=EB+Garamond&display=swap" rel="stylesheet"> 
<p class="texto"> Here I tried to recreate Bateman's business card using only HTML and CSS. I really enjoyed the movie and just finished reading the book. It's my humble tribute to such a great movie. I will probably watch it again but wouldn't do the same to the book though. Too graphic. Too pornographic. Very bizarre. </p>
<div class="parent">
<div class="child">
<div class="fullcard">
  <div class="topoesq">
    212 555 6342
  </div>
  <div class="topodir">
    PIERCE &PIERCE 
    <div class="merg">MERGERS AND AQUISITIONS</div>
  </div>
  <div class="centro">Patrick BATEMAN <br>
    <div class="vp"><span class="cap">V</span>ICE <span class="cap">P</span>RESIDENT</div></div>
  <div class="rodape">358 EXCHANGE PLACE NEW YORK, N.Y. 10099 FAX 212 555 6390 TELEX 10 4534</div>
</div>
</div>
