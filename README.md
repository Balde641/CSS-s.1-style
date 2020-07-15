# CSS-s.1-style

/* This one is for all margin and padding.
*{
margin:0;
padding:0;
}
*/

body{
background-color:#f4f4f4;
color:#555555;

font-family:Arial, Helvetica, sans-serif;
font-size:16px;
font-weight:normal;
/* Same as above */
font:normal 16px Arial, Helvetica, sans-serif;

line-height:1.6em;
margin:0;
}

a{
text-decoration:none;
color:#000;
}

a:hover{
color:blue;
}

a:active{
color:green;
}

a:visited{

}

.container{
width:80%;
margin:auto;
}

.button{
background-color:#333;
color:#fff;
padding:10px 15px;
border:none;
}

.button:hover{
background:red;
color:white;
}

.clr{
clear:both;
}

.box-1{
background-color:#333;
color:#fff;

border-right:5px red solid;
border-left:5px red solid;
border-top:5px red solid;
border-bottom:5px red solid;
/* This one targets the border-width */
border-width:3px;
border-bottom-width:10px;
border-top-style:dotted;
    /* Same as first one for the four sides */
border: 5px green solid;

padding-top:20px;
padding-bottom:20px;
padding-right:20px;
padding-left:20px;

/* Same as above */
padding:20px;

margin-top:20px;
margin:20px 0;
}

.box-1 h1{
font-family:Tahoma;
font-weight:800;
font-style:italic;
text-decoration:underline;
text-transform:uppercase;
letter-spacing:0.2em;
word-spacing:1em;
}

.box-2{
border:3px dotted #ccc;
padding:20px;
margin:20px 0;
}

.categories{
border:1px #ccc solid;
padding:10px;
border-radius:15px;

}

.categories h2{
text-align:center;
}

.categories ul{
padding:0;
padding-left:20px;
list-style:square;
list-style:none;
}

.categories li{
padding-bottom:6px;
border-bottom:dotted 1px #333;
list-style-image: url('../images/check (1).jpg');
}

.my-form{
padding:20px;
}

.my-form .form-group{
padding-bottom:15px;
}

.my-form label{
display:block;
}

.my-form input[type="text"], .my-form textarea{
padding:8px;
width:100%;
}

.block{
float:left;
width:33.3%;
border:1px solid #ccc;
padding:10px;
box-sizing:border-box;

}

#main-block{
float:left;
width:70%;
padding:15px;
box-sizing:border-box; 
}

#sidebar{
float:right;
width:30%;
background-color:#333;
color:#fff;
padding:15px;
box-sizing:border-box; 
}

.p-box{
width:800px;
height:500px;
border:1px solid #000;
margin-top:30px;
position:relative;
background-image:url('../images/ict.jpg');
background-repeat: no-repeat;
background-position:100px 200px;
background-position:center top;


}

.p-box h1{
position:absolute;
top:30px;
left:30px;
}

.p-box h2{
position:absolute;
bottom:30px;
right:30px;

}

.fix-me{
position:fixed;
top:400px;
}

.my-list li:first-child{
background: red;
}

.my-list li:last-child{
background: blue;
}

.my-list li:nth-child(5){
background: yellow;
}

.my-list li:nth-child(even){
background: green;
}
