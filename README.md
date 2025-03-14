<META http-equiv=Content-Type content="text/html; charset=UTF-8">
	<HTML>
	<HEAD><TITLE>TL-WR841N</TITLE>
	<META http-equiv=Pragma content=no-cache>
	<META http-equiv=Expires content="wed, 26 Feb 1997 08:21:57 GMT">
	<SCRIPT language="javascript" type="text/javascript"><!--
	//--></SCRIPT>
	<SCRIPT language="javascript" type="text/javascript">
	var httpAutErrorArray = new Array(
	3, 1, "http://192.168.0.1", 0,0 );
	</SCRIPT>
	
	<SCRIPT language="javascript" type="text/javascript">
	if(window.parent != window)
	{
		document.cookie = "Authorization=;path=/"; 
		window.parent.location.href = httpAutErrorArray[2];
	}
	</SCRIPT>
	<script type="text/javascript" src="encrypt.js"></script>
	<style type="text/css">
	body{
		font-family:Arial, sans-serief;
		background-color:#E5E5E5;
		margin:0px;
		padding:0px;
	}
	div.loginBox
	{
		display: block;
		position:relative;
		margin-top:10%; 
		text-align:center;
	}
	.noteDiv{
		color:gray;
		font-family:Arial;
		width:395px;
		text-align:left;
		margin:0px auto;
		font-size:14px;
	}
	#note{
		display:inline-block;
		vertical-align:top;
		_display:inline;
		_zoom:1;
		width:80px;
		font-weight:bold;
	}
	#tip{
		display:inline-block;
		vertical-align:top;
		_display:inline;
		_zoom:1;
		width:340px;
		font-weight:bold;
	}
	div.panelThre{
		margin-top:10px;
	}
	div.picDiv{
		width:395px;
		height:276px;
		background:url("loginbg.png");
		position:relative;
	}
	input.pcPassword{
		width:300px;
		height:50px;
		line-height:50px;
		padding-left:20px;
	}
	div.PCBtnDiv{
		position:relative;
		margin-top:20px;
	}
	img.logoPic{
		width:100%;
	}
	#t_copyright{
		-webkit-text-size-adjust:none;
		font-size:8px;
		color:#6a6969;
		font-family:"Verdana";
		font-weight:normal;
		margin-top:40px;
		display:inline-block;
	}
	.topLogo{
		background:url("top_bg.jpg");
		height:90px;
	}
	ul{
		padding:60px 0px 0px 0px;
		margin:0px;
		list-style:none;
	}
	ul li{
		height:34px;
		width:222px;
	}
	li.unLi{
		background:url("loginUser.png");
	}
	li.pwLi{
		background:url("loginPwd.png");
	}
	li.blank{
		height:15px;
	}
	input.text{
		border:0px;
		height:26px;
		line-height:26px;
		width:175px;
		padding:0px;
		margin:4px 0px 0px 40px;
		font-size:14px;
		color:#6a6969;
		font-family:"Verdana","Arial";
		font-weight:normal;
	}
	label.loginBtn{
		height:34px;
		display:inline-block;
		width:113px;
		margin-top:30px;
		background:url("loginBtn.png");
		cursor:pointer;
	}
	</style>
	</head>
	<body>
		<div class="topLogo">
			<img src="top1_1.jpg" border="0" style="cursor:pointer">
		</div>
		<div class="loginBox"> 
			<div class="noteDiv">
				<span id="note" name="note"></span>
				<span id="tip" name="tip"></span>
			</div>
			<div class="panelThre" align="center">
				<div align="center" class="picDiv" align="center">
					<ul>
						<li id="unLi" class="unLi" name="unLi"><input class="text" id="userName" type="text" maxlength="15" /></li>
						<li class="blank"></li>
						<li id="pwLi" class="pwLi" name="pwLi"><input class="text" id="pcPassword" type="password" maxlength="15"/></li>
					</ul>
					<label id="loginBtn" class="loginBtn" onclick="PCSubWin()"></label>
					<div>
					<label id="t_copyright" name="t_copyright">Copyright © 2015 TP-LINK TECHNOLOGIES CO., LTD. Все права защищены.</label> 
					</div>
				</div>
			</div>
		</div>
		<form action="/userRpm/LoginRpm.htm" method="get" id="loginForm" enctype="multipart/form-data">
			<input type="hidden" value="Save" name="Save" />
		</form>
	</body>
	</html>
	
