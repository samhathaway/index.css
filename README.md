# index.css

.grad {
    height: auto;
  background: #7FFFD4; /* For browsers that do not support gradients */
  background: -webkit-linear-gradient(left top, #00cc66, white); /* For Safari 5.1 to 6.0 */
  background: -o-linear-gradient(bottom right, #00cc66, white); /* For Opera 11.1 to 12.0 */
  background: -moz-linear-gradient(bottom right, #00cc66, white); /* For Firefox 3.6 to 15 */
  background: linear-gradient(to bottom right, #00cc66, white); /* Standard syntax */
/*aqua gradient #7FFFD4*/
}
html{
    background:
    /*url (contactbg.jpg);*/
}
/*#page-wrap {
     width: 900px;
     margin: 0 auto;
}*/
#wrap {
width:850px;
margin:0 auto;
background:#39ac73;
}
body{
    font-family: 'Handlee', cursive;
    font-size:20px;
    font-style:bold;
    position: relative;
    overflow-x: hidden;
}
.banner{
    padding: 5px;
}
.d1, .d2, .d3, .d4, .d5, .d6{
    position:relative;
    width:250px;
    height: 250px;
    box-shadow: 10px 10px 5px grey;
    margin: 15px;
}
.fullimage{
    position:relative;
    border:solid purple;
    padding-left:50px;
    padding-right: 50px;
    display:inline-block;
    text-decoration: underline;
}
.contactxt{
    color:white;
}
.contact{
    border:dotted purple;
    display:inline-block;
    position: relative;
}
.fa {
    padding: 20px;
    font-size: 30px;
    width: 30px;
    text-align: center;
    text-decoration: none;
    border-radius: 50%;
}


.container {
  position: relative;
  width: 50%;
}
.image {
  display: block;
  width: 250px;
  height: 250px;
}

.overlay {
  position: absolute;
  bottom: 100%;
  left: 0;
  right: 0;
  background-color: #008CBA;
  overflow: hidden;
  width: 100%;
  height:0;
  transition: .5s ease;
  opacity: .4;
}

.container:hover .overlay {
  bottom: 0;
  height: 100%;
}
.text {
  font-family: 'Handlee', cursive;
  white-space: nowrap; 
  color: white;
  font-size: 40px;
  position: absolute;
  overflow: hidden;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
}
a:link{
    color:white
}
a:visited{
    color:black
}
a:hover{
    color:grey
}
a:active{
    color:purple
}



.firstcharacter {
  color: #903;
  float: left;
  font-family: Georgia;
  font-size: 75px;
  line-height: 60px;
  padding-top: 4px;
  padding-right: 8px;
  padding-left: 3px;
}
.pquote {
    float: right;
    width: 200px;
    background: url(images/openquote.gif) top left no-repeat;
    color: #030;
    font-size: 26px;
    line-height: 0.9;
    font-style: italic;
    padding: 13px;
}

blockquote {
    margin: 0;
}

.pquote p:first-letter {
    font-size: 39px;
    font-weight: bold;
}
input[type=text], textarea {
  -webkit-transition: all 0.30s ease-in-out;
  -moz-transition: all 0.30s ease-in-out;
  -ms-transition: all 0.30s ease-in-out;
  -o-transition: all 0.30s ease-in-out;
  outline: none;
  padding: 3px 0px 3px 3px;
  margin: 5px 1px 3px 0px;
  border: 1px solid #DDDDDD;
}
 
input[type=text]:focus, textarea:focus {
  box-shadow: 0 0 5px rgba(81, 203, 238, 1);
  padding: 3px 0px 3px 3px;
  margin: 5px 1px 3px 0px;
  border: 1px solid rgba(81, 203, 238, 1);
}
.slider-holder
        {
            width: 800px;
            height: 400px;
            background-color: yellow;
            margin-left: auto;
            margin-right: auto;
            margin-top: 0px;
            text-align: center;
            overflow: hidden;
        }
        
        .image-holder
        {
            width: 2400px;
            background-color: red;
            height: 400px;
            clear: both;
            position: relative;
            
            -webkit-transition: left 2s;
            -moz-transition: left 2s;
            -o-transition: left 2s;
            transition: left 2s;
        }
        
        .slider-image
        {
            float: left;
            margin: 0px;
            padding: 0px;
            position: relative;
        }
        
        #slider-image-1:target ~ .image-holder
        {
            left: 0px;
        }
        
        #slider-image-2:target ~ .image-holder
        {
            left: -800px;
        }
        
        #slider-image-3:target ~ .image-holder
        {
            left: -1600px;
        }
        
        .button-holder
        {
            position: relative;
            top: -20px;
        }
        
        .slider-change
        {
            display: inline-block;
            height: 10px;
            width: 10px;
            border-radius: 5px;
            background-color: brown;
        }
