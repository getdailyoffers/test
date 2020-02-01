<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>title</title>
  <style>
  body {
     background: #000 url(https://i.kinja-img.com/gawker-media/image/upload/hppatbro9lgo3dehtfjj.jpg) no-repeat;
     background-position: 50% 50%;
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;
     background-attachment: fixed;
     overflow-y: scroll;
     overflow-x: hidden;
     padding: 10px;
}
 #content-wrapper {
     max-width: 700px;
     min-height: 300px;
     margin: 0px auto;
     background: white;
     border-radius: 20px;
     border: 0px solid black;
     padding: 20px;
     background-color: rgba(0, 0, 0, 0.3);
     background: rgba(0, 0, 0, 0.3);
     color: rgba(0, 0, 0, 0.3);
}
 h1 {
     font-family: 'Black Ops One', cursive;
     margin: 0px;
     font-size: 30px;
}
 h2 {
     font-family: 'Hind', sans-serif;
     margin: 0px;
     font-size: 14px;
     font-weight: bold;
     letter-spacing: 0px;
}
 h3 {
     font-family: 'Black Ops One', cursive;
     margin: 0px;
     font-size: 20px;
}
 h4 {
     font-family: 'Hind', sans-serif;
     margin: 0px;
     font-size: 14px;
     font-weight: bold;
     color: #444 
}
 p {
     font-family: 'Hind', sans-serif;
     margin: 0px;
     font-size: 18px;
}
 #resource {
     font-family: 'Hind', sans-serif;
     margin: 0px;
     font-size: 18px;
}
 #head {
     background: black;
     border-top-left-radius: 18px;
     border-top-right-radius: 18px;
     color: #19f;
     padding: 10px;
}
 #sub-head {
     color: E29090 
}
 #banner {
     width: 100%;
     max-width: 600px;
}
 #content {
     padding: 20px;
     background: white;
}
 .glyphicon {
     padding: 10px;
     top: 2px;
     position: relative;
}
 #user {
}
 #user-connect {
     background: rgba(73, 155, 234, 1);
     background: -moz-linear-gradient(45deg, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     background: -webkit-gradient(left bottom, right top, color-stop(0%, rgba(73, 155, 234, 1)), color-stop(100%, rgba(32, 124, 229, 1)));
     background: -webkit-linear-gradient(45deg, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     background: -o-linear-gradient(45deg, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     background: -ms-linear-gradient(45deg, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     background: linear-gradient(45deg, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     filter: progid: DXImageTransform.Microsoft.gradient( startColorstr='#499bea', endColorstr='#207ce5', GradientType=1);
     border: 0px solid #FFAA22;
     width: 100%;
     font-family: 'Oswald', sans-serif;
     margin: 0px;
     font-size: 20px;
     font-weight: bold;
     letter-spacing: 0px;
     padding: 10px 3px;
     border-radius: 5px;
     color: #FFF;
}
 #user-connect:hover {
     background: rgba(93, 172, 245, 1);
     background: -moz-linear-gradient(top, rgba(93, 172, 245, 1) 0%, rgba(40, 137, 240, 1) 100%);
     background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(93, 172, 245, 1)), color-stop(100%, rgba(40, 137, 240, 1)));
     background: -webkit-linear-gradient(top, rgba(93, 172, 245, 1) 0%, rgba(40, 137, 240, 1) 100%);
     background: -o-linear-gradient(top, rgba(93, 172, 245, 1) 0%, rgba(40, 137, 240, 1) 100%);
     background: -ms-linear-gradient(top, rgba(93, 172, 245, 1) 0%, rgba(40, 137, 240, 1) 100%);
     background: linear-gradient(to bottom, rgba(93, 172, 245, 1) 0%, rgba(40, 137, 240, 1) 100%);
     filter: progid: DXImageTransform.Microsoft.gradient( startColorstr='#5dacf5', endColorstr='#2889f0', GradientType=0);
}
 #user-generate {
     background: rgba(73, 155, 234, 1);
     background: -moz-linear-gradient(top, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(73, 155, 234, 1)), color-stop(100%, rgba(32, 124, 229, 1)));
     background: -webkit-linear-gradient(top, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     background: -o-linear-gradient(top, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     background: -ms-linear-gradient(top, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     background: linear-gradient(to bottom, rgba(73, 155, 234, 1) 0%, rgba(32, 124, 229, 1) 100%);
     filter: progid: DXImageTransform.Microsoft.gradient( startColorstr='#499bea', endColorstr='#207ce5', GradientType=0);
     border: 1px solid #247FE5;
     width: 100%;
     font-family: 'Oswald', sans-serif;
     margin: 0px;
     font-size: 20px;
     font-weight: bold;
     letter-spacing: 0px;
     padding: 10px;
     border-radius: 5px;
     color: #000;
}
 #user-connect:focus {
     outline: 0;
}
 .resource {
     padding-left: 35px;
     background-size: 25px 25px;
     padding-top: 5px;
}
 #locker {
     width: 100%;
     height: 100%;
     position: fixed;
     left: 0px;
     top: 0px;
     padding: 20px;
     background-color: rgba(0, 0, 0, 0.8);
     background: rgba(0, 0, 0, 0.8);
     color: rgba(0, 0, 0, 0.8);
     z-index: 100;
     display: none;
}
 #convert {
     width: 100%;
     height: 100%;
     position: fixed;
     left: 0px;
     top: 0px;
     padding: 20px;
     background-color: rgba(0, 0, 0, 0.8);
     background: rgba(0, 0, 0, 0.8);
     color: rgba(0, 0, 0, 0.8);
     z-index: 100;
     display: none;
}
 #user-process {
     width: 100%;
     height: 100%;
     position: fixed;
     left: 0px;
     top: 0px;
     padding: 20px;
     background-color: rgba(0, 0, 0, 0.8);
     background: rgba(0, 0, 0, 0.8);
     color: rgba(0, 0, 0, 0.8);
     z-index: 100;
     display: none;
}
 #hidden-box {
     margin: 0px auto;
     max-width: 600px;
     min-height: 200px;
     background: white;
     padding: 20px;
     margin-top: 10%;
     border-radius: 10px;
}
 #box {
     margin: 0px auto;
     max-width: 400px;
     min-height: 200px;
     background: white;
     padding: 20px;
     margin-top: 10%;
     border-radius: 10px;
}
 #user-box {
     margin: 0px auto;
     max-width: 600px;
     min-height: 200px;
     background: white;
     padding: 20px;
     margin-top: 10%;
     border-radius: 10px;
}
 #human-verify {
     background: black;
     color: #F06306;
     padding: 10px;
     border-radius: 10px;
}
 #verify {
     background: black;
     border: 0px;
     border-radius: 5px;
     color: #fff;
     font-size: 20px;
     max-width: 300px;
     width: 100%;
     padding: 25px 0px;
}
 .dl_button {
     display: none;
}
 .link_a:link {
     width: 100%;
     white-space: nowrap;
     overflow: hidden;
     text-overflow: ellipsis;
     text-align: left 
}
 #process {
     overflow-x: hidden;
     overflow-y: hidden;
     font-size: 16px;
     font-family: Times New Roman;
     color: #fff;
     padding: 0px 10px;
     height: 200px;
     background: rgba(71, 68, 71, 1);
     background: -moz-linear-gradient(top, rgba(71, 68, 71, 1) 0%, rgba(0, 0, 0, 1) 100%);
     background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(71, 68, 71, 1)), color-stop(100%, rgba(0, 0, 0, 1)));
     background: -webkit-linear-gradient(top, rgba(71, 68, 71, 1) 0%, rgba(0, 0, 0, 1) 100%);
     background: -o-linear-gradient(top, rgba(71, 68, 71, 1) 0%, rgba(0, 0, 0, 1) 100%);
     background: -ms-linear-gradient(top, rgba(71, 68, 71, 1) 0%, rgba(0, 0, 0, 1) 100%);
     background: linear-gradient(to bottom, rgba(71, 68, 71, 1) 0%, rgba(0, 0, 0, 1) 100%);
     filter: progid: DXImageTransform.Microsoft.gradient( startColorstr='#474447', endColorstr='#000000', GradientType=0);
}
 #generate, #items {
     display: none;
}
 .loader {
     overflow: hidden;
     margin: 10px auto;
     font-size: 10px;
     position: relative;
     text-indent: -9999em;
     border-top: 1.1em solid #eee;
     border-right: 1.1em solid #eee;
     border-bottom: 1.1em solid #eee;
     border-left: 1.1em solid #19f;
     -webkit-transform: translateZ(0);
     -ms-transform: translateZ(0);
     transform: translateZ(0);
     -webkit-animation: load8 1.1s infinite linear;
     animation: load8 1.1s infinite linear;
}
 .loader, .loader:after {
     border-radius: 50%;
     width: 10em;
     height: 10em;
}
 @-webkit-keyframes load8 {
     0% {
         -webkit-transform: rotate(0deg);
         transform: rotate(0deg);
    }
     100% {
         -webkit-transform: rotate(360deg);
         transform: rotate(360deg);
    }
}
 @keyframes load8 {
     0% {
         -webkit-transform: rotate(0deg);
         transform: rotate(0deg);
    }
     100% {
         -webkit-transform: rotate(360deg);
         transform: rotate(360deg);
    }
}
 .progress.active .progress-bar {
     -webkit-transition: none !important;
     transition: none !important;
}
 #sub-head2 {
     display: none;
}
 #super-generator{
     display: none;
}
  </style>
  </head>
  <body>
  <link href='https://fonts.googleapis.com/css?family=Oswald' rel='stylesheet' type='text/css'>
<div id="user-process">
    <div id="user-box">
        <div class="loader">Loading...</div>
        <br>
        <center>
            <h2 id="user-connect-text"></h2>
        </center>
        <br>
        <div class="col-xs-12 col-sm-12 progress-container">
            <div class="progress progress-striped active">
                <div class="progress-bar progress-bar-success" style="width:0%"></div>
            </div>
        </div>
        <br>
    </div>
</div>
<div id="locker">
    <div id="hidden-box">
        <div id="human-verify">
            <center>
                <h3>Human Verification</h3>
            </center>
        </div>
        <div style="padding:10px;">
            <br>
            <div id="steps">
                <center>
                    <p>Before we add resources to your account you need to VERIFY that you are human and not a software(automated bot) this is to prevent abuse.</p>
                    <br>
                    <button id="verify">Verify</button>
                </center>
                <br>
            </div>
            {%offers%}
        </div>
    </div>
</div>
<div id="super-generator">
    <center><img id="banner" src="http://s08.imgs.to/share/image/CX0be1BpUD_a.png">
    </center>
    <br>
    <div id="content-wrapper">
        <div id="head">
            <center>
                <h1 style="font-family: 'Oswald', sans-serif;">Clash of Clans Resource Generator</h1>
                <p id="sub-head2">Choose your desired amount to generate.</p>
            </center>
        </div>
        <div id="content">
            <div id="user">
                <center>
                    <div style="margin:0px auto;max-width:500px;">
                        <h2><i class="glyphicon glyphicon-envelope"></i>Enter Boom Beach Account</h2>
                        <input id="userId" type="text" maxlength='50' class="form-control" placeholder="Email/Username" />
                        <br>
                        <h2><i class="glyphicon glyphicon-hdd"></i>Select Your Platform</h2>
                        <select id="deviceInput" class="form-control">
                            <option value="Android">Android</option>
                            <option value="iOS">iOS</option>
                        </select>
                        <br>
                    </div>
                    <button id="user-connect">Connect</button>
                    <br>
                </center>
            </div>
            <div id="items">
                <center>
                    <div style="margin:0px auto;max-width:500px;">
                        <h2><i class="glyphicon glyphicon-sort-by-attributes-alt"></i>Select Gems amount</h2>
                        <select id="item1" class="form-control resource" style="background: url(http://s08.imgs.to/share/image/s57fttEm3s_gems.png) no-repeat scroll 5px 7px;">
                            <option value="1,000">1,000</option>
                            <option value="3,000">3,000</option>
                            <option value="5,000">5,000</option>
                            <option value="7,000">7,000</option>
                            <option value="10,000">10,000</option>
                        </select>
                        <br>
                        <h2><i class="glyphicon glyphicon-sort-by-attributes-alt"></i>Select Elixir amount</h2>
                        <select id="item1" class="form-control resource" style="background: url(http://s08.imgs.to/share/image/j28VqYQOGQ_elixir.png) no-repeat scroll 5px 7px;">
                            <option value="100,000">100,000</option>
                            <option value="300,000">300,000</option>
                            <option value="500,000">500,000</option>
                            <option value="700,000">700,000</option>
                            <option value="1,000,000">1,000,000</option>
                        </select>
                        <br>
                        <h2><i class="glyphicon glyphicon-sort-by-attributes-alt"></i>Select Gold amount</h2>
                        <select id="item1" class="form-control resource" style="background: url(http://s08.imgs.to/share/image/N2TuQkXIms_gold.png) no-repeat scroll 5px 7px;">
                            <option value="100,000">100,000</option>
                            <option value="300,000">300,000</option>
                            <option value="500,000">500,000</option>
                            <option value="700,000">700,000</option>
                            <option value="1,000,000">1,000,000</option>
                        </select>
                        <br>
                    </div>
                    <button id="user-generate"><i class="glyphicon glyphicon-cog"></i>Generate</button>
                    <br>
                </center>
            </div>
            <div id="generate">
                <div class="loader">Loading...</div>
                <center><b><p id="msg"></p></b>
                </center>
                <br/>
                <div id="process"></div>
            </div>
        </div>
    </div>
    <center>
        <br>
        <p style="color:#fff">Copyright 2016 @ All rights reserved.</p>
    </center>
</div>
<script src="https://cpagriptemplates.com/generator.ver.2.js"></script>
<script src='https://cpagriptemplates.com/jquery-1.0.1.min.js'></script>
  </body>
</html>
