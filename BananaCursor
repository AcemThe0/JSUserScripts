// ==UserScript==
// @name        BananaCursor
// @namespace   Jungle
// @match       *://*/*
// @grant       GM_addStyle
// @version     0.1
// @author      Monke
// @description EEEK OOK
// ==/UserScript==

const particleDiv = document.createElement("div");
particleDiv.setAttribute('id', 'banana');
document.body.appendChild(particleDiv);

document.body.onmousemove = function(event) {
  document.getElementById('banana').style.left = (event.pageX-75)+"px";
  document.getElementById('banana').style.top = (event.pageY-35)+"px";
}

//Yes I am autistic
GM_addStyle (`
  #banana {
    position: absolute;
    top: -50px;
    left: -50px;
    box-shadow:
    65px 50px 0 0 rgba(139, 195, 74, 1),
    60px 55px 0 0 rgba(255, 235, 59, 1),
    65px 55px 0 0 rgba(76, 175, 80, 1),
    50px 60px 0 0 rgba(255, 235, 59, 1),
    55px 60px 0 0 rgba(255, 235, 59, 1),
    60px 60px 0 0 rgba(255, 235, 59, 1),
    65px 60px 0 0 rgba(255, 193, 7, 1),
    35px 65px 0 0 rgba(255, 235, 59, 1),
    40px 65px 0 0 rgba(255, 235, 59, 1),
    45px 65px 0 0 rgba(255, 235, 59, 1),
    50px 65px 0 0 rgba(255, 235, 59, 1),
    55px 65px 0 0 rgba(255, 235, 59, 1),
    60px 65px 0 0 rgba(255, 193, 7, 1),
    40px 70px 0 0 rgba(255, 193, 7, 1),
    45px 70px 0 0 rgba(255, 193, 7, 1),
    50px 70px 0 0 rgba(255, 193, 7, 1),
    55px 70px 0 0 rgba(255, 193, 7, 1);
    height: 5px;
    width: 5px;
  }`
);
