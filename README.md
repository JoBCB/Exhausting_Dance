# Exhausting_Dance

< !--   ON GOOGLE SEARCH

  var el = document.querySelector('.a4bIc');
  
  var newEl = document.createElement('p');
  
  newEl.innerHTML = '<marquee style="font-size=22pt" direction="left" width="430" height="25" scrolldelay="180">Inventing Rest. It is not an interruption. It is not the stop. It is continuity. The Movement continues to the Rest that continues. For the Movement that continues to rest that continues still towards the Movement. Inventing motion at rest, inventing rest in the movement.</marquee>';
  
  el.parentNode.replaceChild(newEl, el); 
  
  // Invention poem by Gonçalo M. Tavares 
  // Code &amp Translation by Joana Chicau

-- >

// <title> Act 1: the dance of exhaution (all the movements) </title>


function Warning() {
    alert("Always remember to continue breathing, in and out.");
}

//myVar = setTimeout(40000, 40050)


function Enter_the_stage (){
  document.getElementById("first").style.color = "black";
};

function Eliminate_or_minimize (x) {
  x.style.fontSize = parseInt(x.style.fontSize) / 2 + 'pt'
};

/*x = document.querySelector("#first");
x.style.fontSize = "10000pt";
y = document.querySelector("#second");
y.style.fontSize = "10000pt";*/

function Remove (y) {
  y.style.fontSize = parseInt(y.style.fontSize) / 2 + 'pt'
};

/*
in the console: x.style.fontSize = parseInt(x.style.fontSize) * 2 + 'pt'
setInterval (function () {half(x)}, 2000)

or in the terminal::::
x.style.fontSize = getComputedStyle(x).fontSize
"666.667px"
x.style.fontSize = ( parseInt(x.style.fontSize) / 2 ) + 'pt'   
"333pt"
*/


var delay="10"; //how many seconds
var count='0';
var Texts=new Array();
Texts[0]="Choreography";
Texts[1]="is a language,";
Texts[2]="for space-time";
Texts[3]="imposing flow";
Texts[4]="continuously";
Texts[5]="moving";
Texts[6]="repeating";


function New_Sequence() {
document.querySelector('.logo').innerHTML=Texts[count];
count++;
if(count==Texts.length){count='0';}
setTimeout("New_Sequence()",delay*1000);


document.querySelector(".logo").style.width="1000px"
document.querySelector(".logo").style.fontSize="14pt"
}

//onload= function() { New_Sequence();}


var textarray = [
"Ritualistic, repetitive",
"Simultaneously",
"An exhausting dance.",
"Breathing until its enough.",
"Substitution.",
"A supermposition of rhythms",
"(variation)",
"exhausting and exhausted",
"No time for breathing." 
];


function Elements_of_Chance(n) {

var rannum= Math.floor(Math.random()*textarray.length);
// document.querySelector(".st").innerHTML=textarray2[rannum];
var r =document.querySelector(".g:nth-child("+n+")"),
  r = r.querySelector(".r");
r.innerHTML=textarray[rannum];
r.style.fontSize="24pt"
};


var textarray2 = [
"Ritualistic, repetitive",
"Simultaneously",
"An exhausting dance.",
"Breathing until its enough.",
"Substitution.",
"A supermposition of rhythms",
"(variation)",
"exhausting and exhausted",
"No time for breathing." 
];

function Juxtaposition_of_Elements_under_Aleatory_Influence(n) {

var rannum= Math.floor(Math.random()*textarray2.length);
// document.querySelector(".st").innerHTML=textarray2[rannum];
var r =document.querySelector(".g:nth-child("+n+")"),
st = r.querySelector(".st");
st.innerHTML=textarray2[rannum];
st.style.fontSize="16pt"
st.style.marginTop = "40px";
};

//in the terminal : setInterval("Juxtaposition_of_elements_under_aleatory_influence(5)",200)

//setTimeout(Elements_of_Chance, 1000) 
//setInterval(Elements_of_Chance, 100)   and then clearInterval(number printed in the console)


function leave_the_stage (n){

var r =document.querySelector(".g:nth-child("+n+")");
r.style.visibility="hidden";
};


colors = new Array(" #000000 ", "#101010 ","#202020 ", "#282828 ","#303030" ,"#383838  ", "#404040 ", "#484848 ","#585858 " ,"#505050 ", "#606060 ","#686868 ", "#787878 ",  "#888888 ", "#989898 ", "#A0A0A0 ", "#A8A8A8 ","#C0C0C0 ", "#B0B0B0 ", "#F0F0F0 "," #D8D8D8 ", "#F0F0F0 ","#FFFFFF ","#D0D0D0", " #181818 ", "#909090 ")

colorIndex = 0
idInterval = 0

function choreography_is_the_organization_of_tensions() {
 document.querySelector('html').style.backgroundColor = colors[colorIndex]
 colorIndex = (colorIndex + 1) % colors.length
}
// experiment with::::::: setInterval("choreography_is_the_organization_of_tensions()",30)

/*function choreography_is_the_organization_of_tensions(tempo) {
  clearInterval(idInterval)
  idInterval = setInterval("tension_counter_tension()",tempo)
}

idWhile = 0 */

function Pause (){
  document.getElementById("body").style.backgroundColor = "#000000";
//setTimeout ("BlackOut()", 200 );
};

function Second_Act () {
  var url = window.open('file:///Users/Jo/Desktop/webpage_google/II.html', '_blank');
  window.location.href = url;
  url.focus();
}
// document.querySelector(“html”).style.backgroundColor = "white"


function Second_Act () {
  window.open("https://www.google.com");
}


// <title>Act 2 or Interlude, Interval, Pause</title>

colors = new Array(" #000000 ", "#101010 ","#202020 ", "#282828 ","#303030" ,"#383838  ", "#404040 ", "#484848 ","#585858 " ,"#505050 ", "#606060 ","#686868 ", "#787878 ",  "#888888 ", "#989898 ", "#A0A0A0 ", "#A8A8A8 ","#C0C0C0 ", "#B0B0B0 ", "#F0F0F0 "," #D8D8D8 ", "#F0F0F0 ","#FFFFFF ","#D0D0D0", " #181818 ", "#909090 ")

colorIndex = 0
idInterval = 0

function choreography_is_the_organization_of_tensions() {
 document.querySelector("body").style.backgroundColor = colors[colorIndex]
 colorIndex = (colorIndex + 1) % colors.length
}
//setInterval("choreography_is_the_organization_of_tensions()",20)


function Rotate () {
     var center = document.querySelector("body"),
      deg = 10;
      decenter = setInterval(function() {
     center.style.transform = "rotateY(" + deg + "deg)";
      deg = (deg + 10) % 360
      }, 80); 
} 

function Pause () {
    clearInterval(decenter);
} 
 
//change rotateX

function Final_Act () {
  window.open("https://www.google.com");
}


// <title>Act 3 or Staging Stillness</title>


var delay="10"; //how many seconds
var count='0';
var Texts=new Array();
Texts[0]="Vicious Circle";
Texts[1]="Repeating Itself";
Texts[2]="Inventing Rest";
Texts[3]="Geometry of Time";
Texts[4]="The Private Circle";
Texts[5]="Public Sphere";
Texts[6]="Spheres";
Texts[7]="That continues";
Texts[8]="Rotation";
Texts[9]="Counterclockwise";
Texts[10]="Always with the Movement";
Texts[11]="Spinning Wheel";
Texts[12]="Perpetual Motion";
Texts[13]="Exhausting and Exhausted";
Texts[14]="Infinity and Exhaustion";

function Breathe (){
        document.querySelector('.gLFyf.gsfi').value = Texts[count]; 
        count++;
        if(count==Texts.length){count='0';}
        setTimeout("Breathe()",delay*800);
} 
// setInterval("Breathe()",1600)

var xMax, yMax, xNeg=0, yNeg=1;

function Move () {
    window.scrollBy(5 * xNeg, 5 * yNeg);
    if(xMax == window.scrollX)xNeg = xNeg * 1;
    if(yMax == window.scrollY)yNeg = xNeg * -1;
    scrolldelay = setTimeout(Move,200);
    console.log(window.scrollY);
    xMax = window.scrollX;
    yMax = window.scrollY;
}
Move();
//stop: clearTimeout(scrolldelay)

//document.querySelector(".srg").style.transform="rotate(180deg)"


function Perpetual_Motion () {

window01 = window.open("https://www.google.com/search?q=Vicious+Circle&newwindow=1&sxsrf=ACYBGNTnXcAwb7ztnnGNEkZrZTJQNmO6sQ:1572535954857&source=lnt&tbs=qdr:d&sa=X&ved=0ahUKEwixj_H36MblAhVIUlAKHTJhCJAQpwUIJw&biw=2312&bih=1317", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=5,left=1,width=400,height=900");
window02 = window.open("https://www.google.com/search?q=Repeating+Itself&newwindow=1&sxsrf=ACYBGNR7mXwE8fNbR1uVeq4aNjzzeTTJtg:1572628659243&source=lnt&tbs=qdr:d&sa=X&ved=0ahUKEwjF7uOkwsnlAhWH-qQKHUPqBpgQpwUIJw&biw=1652&bih=749&dpr=2", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=25,left=100,width=1400,height=90"); 
window03 = window.open("https://www.google.com/search?q=Inventing+Rest&newwindow=1&tbas=0&sxsrf=ACYBGNTEesn2O_rcdgF9gab5SCr9d09TBA:1572628752717&source=lnt&tbs=qdr:d&sa=X&ved=0ahUKEwjWgK3RwsnlAhUJ2qQKHSj1CREQpwUIKA&biw=1652&bih=749", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=1000,left=100,width=400,height=100"); 
window04 = window.open("https://www.google.com/search?newwindow=1&biw=1652&bih=749&tbs=qdr%3Ad&sxsrf=ACYBGNS9UbXvr94U5fTsd1_8M0JriSR1aA%3A1572628766905&ei=Hmm8XYz3NsHzkwXT64OoBA&q=Geometry+of+Time&oq=Geometry+of+Time&gs_l=psy-ab.3..0l2j0i22i30l8.51118.51118..51254...0.4..0.57.57.1......0....2j1..gws-wiz.......0i71.sBeziUDwfc4&ved=0ahUKEwiM_o7YwsnlAhXB-aQKHdP1AEUQ4dUDCAo&uact=5", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=50,left=400,width=100,height=200"); 
window05 = window.open("https://www.google.com/search?q=The+private+Circle&newwindow=1&sxsrf=ACYBGNR9AxShpzsMdCK46yliRY0mcsq3Uw:1572628894905&source=lnt&tbs=qdr:y&sa=X&ved=0ahUKEwjrv5OVw8nlAhUBqaQKHUhlDTgQpwUIJw&biw=1652&bih=749", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=500,left=1100,width=900,height=90");
window06 = window.open("https://www.google.com/search?q=Public+Sphere&newwindow=1&sxsrf=ACYBGNSpVuBsVdldIliA-zk-SXSTttSseQ:1572629089524&source=lnt&tbs=qdr:h&sa=X&ved=0ahUKEwiPjvrxw8nlAhVF-6QKHeQGBLkQpwUIKA&biw=1652&bih=749", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=500,left=900,width=100,height=100");
window07 = window.open("https://www.google.com/search?q=Spheres&newwindow=1&tbas=0&tbs=ic:gray,qdr:d&tbm=isch&sxsrf=ACYBGNRIL-D0F56X-x74IPbb8CCgUl5eIQ:1572629193381&source=lnt&sa=X&ved=0ahUKEwj6-ryjxMnlAhVEy6QKHWCJD6YQpwUIIw&biw=1652&bih=749&dpr=2", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=800,left=20,width=100,height=120");
window08 = window.open("https://www.google.com/search?q=That+continues&newwindow=1&sxsrf=ACYBGNRmCltKi6vU_LLR0gcUohLaXvrN7Q:1572629240490&source=lnt&tbs=qdr:h&sa=X&ved=0ahUKEwjElvi5xMnlAhXJ66QKHSTGB40QpwUIKA&biw=1652&bih=749", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=500,left=100,width=400,height=90");
window09 = window.open("https://www.google.com/search?q=Rotation&newwindow=1&sxsrf=ACYBGNQ2VXIjMMiZe8pY_xbUgYz9TiK89g:1572629262507&tbas=0&source=lnt&sa=X&ved=0ahUKEwirirjExMnlAhXOCuwKHa2RAvAQpwUIJw&biw=1652&bih=749", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=25,left=1,width=40,height=400");
window10 = window.open("https://www.google.com/search?q=Counterclockwise&newwindow=1&sxsrf=ACYBGNTLT-J1DGNkXUj7R2bKdtcAIZMF7g:1572629466110&source=lnt&tbs=qdr:d&sa=X&ved=0ahUKEwjSgMOlxcnlAhWPMewKHfFEAKgQpwUIJw&biw=1680&bih=715", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=800,left=1400,width=100,height=900");
window11 = window.open("https://www.google.com/search?q=Always+with+the+movement&newwindow=1&sxsrf=ACYBGNQYnZg8LLoDyaU7VcX-9crajLVplQ:1572629506081&source=lnt&tbs=qdr:h&sa=X&ved=0ahUKEwi10cq4xcnlAhUE_KQKHRcdCo4QpwUIJw&biw=1680&bih=715", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=100,left=100,width=500,height=100");
window12 = window.open("https://www.google.com/search?q=Spinning+wheel&newwindow=1&tbas=0&sxsrf=ACYBGNQIZWP1QkhCJSaNR_8nrHilZxgDSQ:1572629583522&tbas=0&source=lnt&sa=X&ved=0ahUKEwigicHdxcnlAhVMsaQKHeX0C_QQpwUIJw&biw=1680&bih=715", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=900,left=900,width=100,height=10");
window13 = window.open("https://www.google.com/search?newwindow=1&biw=1680&bih=715&sxsrf=ACYBGNStsj9bDPG7PhSJ8coMnqo92Jnjww%3A1572629588783&ei=VGy8XcqxL6PikgWrr5D4Bg&q=Perpetual+Motion&oq=Perpetual+Motion&gs_l=psy-ab.3..0i67l3j0i20i263j0j0i67j0j0i67j0j0i67.46531.46531..46958...0.4..0.66.66.1......0....2j1..gws-wiz.......0i71.H9s6376fNAE&ved=0ahUKEwjKq4LgxcnlAhUjsaQKHasXBG8Q4dUDCAo&uact=5", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=10,left=450,width=300,height=1200");
window14 = window.open("https://www.google.com/search?newwindow=1&biw=1680&bih=715&sxsrf=ACYBGNSEh3c5JZNl_lfqlN4r6oU_S0QCXQ%3A1572629716420&ei=1Gy8Xf2sGabikgXbzZ7gBg&q=Exhausting+and+Exhausted&oq=Exhausting+and+Exhausted&gs_l=psy-ab.3..35i39j0i22i30l5.558276.558276..558753...0.4..0.70.70.1......0....2j1..gws-wiz.......0i71.W4auttJbLpg&ved=0ahUKEwj95vCcxsnlAhUmsaQKHdumB2wQ4dUDCAo&uact=5", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=1000,left=500,width=1200,height=100");
window15 = window.open("https://www.google.com/search?newwindow=1&biw=1680&bih=715&sxsrf=ACYBGNQ8zmTGx6QE12sOsUHRX9G1irEzOg%3A1572629668845&ei=pGy8XbKnM8a1sAe-4YXYCA&q=Infinity+and+Exhaustion&oq=Infinity+and+Exhaustion&gs_l=psy-ab.3...19442.19442..19859...0.0..0.85.85.1......0....2j1..gws-wiz.wVV793_BfFk&ved=0ahUKEwiyiZmGxsnlAhXGGuwKHb5wAYsQ4dUDCAo&uact=5", "_blank", "toolbar=yes,scrollbars=yes,resizable=yes,top=200,left=1100,width=100,height=100");
}

//Perpetual_Motion () 
//setTimeout("Perpetual_Motion()", 10000)

function Or_Rupture() {
    window01.close();
    window02.close();  
    window03.close();
    window04.close();  
    window05.close();
    window06.close();
    window07.close();
    window08.close();  
    window09.close();
    window10.close(); 
    window11.close();
    window12.close();
    window13.close();
    window14.close();  
    window15.close();
}

//setTimeout("Or_Rupture()", 60000)

//document.querySelector("#main").innerHTML="";


The script is part of the exhibition PERPETUAL INTERPRETER (2019), at LOKALE, Copenhagen.

_Made possible with the support of Stimuleringsfonds Creatieve Industrie_
