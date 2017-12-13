#MAIN LENDING DOCUMENTATION
=====================
The work based on framework BOOTSTRUP.

Used fonts:
-----------------
'Open Sans' та 'Dosis'

## Used icon libraries:
 1. Fontawesome
 2. Et-line

### Default styles
'''css
.bg-grey{
	background-color: #f8f8f8;
}
.bg-black{
	background-color: #111;
}
.text-white{
	color: #fff !important;
}
'''

### Default components

/* === SECTIONS === */
.default-section{
	padding: 140px 0;
}
.small-section{
	padding: 75px 0;
}
@media (max-width: 767px){
	.default-section{
		padding: 80px 0;
	}
	.small-section{
		padding: 40px 0;
	}
}
/* === SECTIONS END === */

/* === RHOMB ICON === */
.rhomb-icon{
	display: inline-block;
	width: 23px;
	height: 23px;
	border-radius: 2px;
	text-align: center;
	line-height: 1.5em;
	font-size: 14px;
	transform: rotate(45deg);
}
.rhomb-icon > *{
	transform: rotate(-45deg);
}
.rhomb-icon.black-icon{
	background-color: #111;
}
.rhomb-icon.white-icon{
	border: 1px solid #646464;
	background-color: #fff;
}
.rhomb-icon.large-icon{
	height: 27px;
	width: 27px;
	line-height: 27px;
	color: #111;
}
/* === RHOMB ICON END === */

/* === TITLE === */
.title{
	font-size: 18px;
	font-family: 'Dosis', 'sans-serif';
	font-weight: 400;
	text-transform: uppercase;
	letter-spacing: .5em;
	margin-bottom: 75px;
	color: #111;
}
.title.light{
	font-weight: 300;
	letter-spacing: .3em;
}
.title.small{
	font-size: 14px;
	letter-spacing: .4em;
	margin-bottom: 30px;
}
.title.less-margin{
	margin-bottom: 20px;
}
.title.author{
	font-size: 11px;
	letter-spacing: .4em;
	color: #999;
}
@media (max-width: 599px){
	.title{
		margin-bottom: 40px;
	}
}
/* === TITLE END === */

.default-text{
	font-size: 15px;
	line-height: 1.7333;
}
blockquote{
	padding: 0;
	margin: 0;
	border: none;
	font-size: 24px;
	line-height: 1.6;
}
blockquote span{
	font-size: 11px;
	letter-spacing: .2em;
	text-transform: uppercase;
}
.icon{
	font-size: 48px;
}

/* ==TABS== */
.nav-tabs{
	border: none;
}
.nav-tabs > li{
	margin-bottom: 0;
}
.nav > li > a{
	padding: 0;
	margin-right: 0;
	color: rgba(17, 17, 17, .5);
	font-family: 'Dosis', 'sans-serif';
	font-weight: 400;
	letter-spacing: .4em;
}
.nav > li > a:hover{
	background-color: transparent;
	border: none;
	color: rgba(17, 17, 17, .8)
}
.nav-tabs>li.active>a, 
.nav-tabs>li.active>a:focus, 
.nav-tabs>li.active>a:hover{
	border: none;
	color: #111;
}
/* ==TABS END== */

/* ==BTN== */
.btn{
	display: inline-block;
	font-size: 14px;
	line-height: 26px;
	letter-spacing: .2em;
	padding: 6px 40px;
}
/* ==BTN END== */

/* ==BTN-DEFAULT== */
.btn.btn-default{
	background-color: #cfcfcf;
	color: #111;
}
.btn.btn-xs{
	font-size: 11px;
	background-color: #e5e5e5;
	color: #777;
	padding: 0 15px;
}
.btn.btn-black{
	background-color: #111;
	color: #fff;
	font-size: 13px;
}
.btn.btn-submit{
	line-height: 22px;
}
.btn.btn.btn-default:hover{
	background-color: #f3e9e9;
	border: 1px solid #f3e9e9;
}
.btn-black:hover{
	background-color: rgba(0, 0, 0, .7);
}
/* ==BTN-DEFAULT END== */

/* == DEFAULT FORM ELEMENT == */
.form-control{
	border: 1px solid #e5e5e5;
	border-radius: 2px;
	height: 36px;
	padding: 6px 13px;
	font-size: 12px;
	letter-spacing: .2em;
	text-transform: uppercase;
	color: #777777;
	box-shadow: none;
}
.form-control:focus{
	box-shadow: none;
	border-color: #6f6e6e;
}
textarea.form-control{
	padding-top: 12px;
}
.form-submit{
	font-size: 11px;
	color: #aaa;
}
.form-submit fa{
	font-size: 12px;
}

/* == DEFAULT FORM ELEMENT END == */

blockquote p{
	margin-bottom: 25px;
}

@media (max-width: 991px){
	blockquote p{
		margin-bottom: 0;
	}
	blockquote{
		margin-bottom: 25px;
	}
}
'''

Загальна документація по лендінгу
=====================
В проекті використано framework BOOTSTRUP.

Використані шрифти:
-----------------
'Open Sans' та 'Dosis'

### Використано такі бібліотеки іконок

 1. Fontawesome
 2. Et-line


### Застосовано такі стилі за умовчанням
'''scss
.bg-grey{
	background-color: #f8f8f8;
}
.bg-black{
	background-color: #111;
}
.text-white{
	color: #fff !important;
}

### Застосована компоненти за умовчанням

.default-section{
	padding: 140px 0;
}
.small-section{
	padding: 75px 0;
}
@media (max-width: 767px){
	.default-section{
		padding: 80px 0;
	}
	.small-section{
		padding: 40px 0;
	}
}
/* === RHOMB ICON === */
.rhomb-icon{
	display: inline-block;
	width: 23px;
	height: 23px;
	border-radius: 2px;
	text-align: center;
	line-height: 1.5em;
	font-size: 14px;
	transform: rotate(45deg);
}
.rhomb-icon > *{
	transform: rotate(-45deg);
}
.rhomb-icon.black-icon{
	background-color: #111;
}
.rhomb-icon.white-icon{
	border: 1px solid #646464;
	background-color: #fff;
}
.rhomb-icon.large-icon{
	height: 27px;
	width: 27px;
	line-height: 27px;
	color: #111;
}
/* === RHOMB ICON END === */

/* === TITLE === */
.title{
	font-size: 18px;
	font-family: 'Dosis', 'sans-serif';
	font-weight: 400;
	text-transform: uppercase;
	letter-spacing: .5em;
	margin-bottom: 75px;
	color: #111;
}
.title.light{
	font-weight: 300;
	letter-spacing: .3em;
}
.title.small{
	font-size: 14px;
	letter-spacing: .4em;
	margin-bottom: 30px;
}
.title.less-margin{
	margin-bottom: 20px;
}
.title.author{
	font-size: 11px;
	letter-spacing: .4em;
	color: #999;
}
@media (max-width: 599px){
	.title{
		margin-bottom: 40px;
	}
}
/* === TITLE END === */

.default-text{
	font-size: 15px;
	line-height: 1.7333;
}
blockquote{
	padding: 0;
	margin: 0;
	border: none;
	font-size: 24px;
	line-height: 1.6;
}
blockquote span{
	font-size: 11px;
	letter-spacing: .2em;
	text-transform: uppercase;
}
.icon{
	font-size: 48px;
}
/* ==TABS== */
.nav-tabs{
	border: none;
}
.nav-tabs > li{
	margin-bottom: 0;
}
.nav > li > a{
	padding: 0;
	margin-right: 0;
	color: rgba(17, 17, 17, .5);
	font-family: 'Dosis', 'sans-serif';
	font-weight: 400;
	letter-spacing: .4em;
}
.nav > li > a:hover{
	background-color: transparent;
	border: none;
	color: rgba(17, 17, 17, .8)
}
.nav-tabs>li.active>a, 
.nav-tabs>li.active>a:focus, 
.nav-tabs>li.active>a:hover{
	border: none;
	color: #111;
}
/* ==TABS END== */

/* ==BTN== */
.btn{
	display: inline-block;
	font-size: 14px;
	line-height: 26px;
	letter-spacing: .2em;
	padding: 6px 40px;
}
/* ==BTN END== */

/* ==BTN-DEFAULT== */
.btn.btn-default{
	background-color: #cfcfcf;
	color: #111;
}
.btn.btn-xs{
	font-size: 11px;
	background-color: #e5e5e5;
	color: #777;
	padding: 0 15px;
}
.btn.btn-black{
	background-color: #111;
	color: #fff;
	font-size: 13px;
}
.btn.btn-submit{
	line-height: 22px;
}
.btn.btn.btn-default:hover{
	background-color: #f3e9e9;
	border: 1px solid #f3e9e9;
}
.btn-black:hover{
	background-color: rgba(0, 0, 0, .7);
}
/* ==BTN-DEFAULT END== */

/* == DEFAULT FORM ELEMENT == */
.form-control{
	border: 1px solid #e5e5e5;
	border-radius: 2px;
	height: 36px;
	padding: 6px 13px;
	font-size: 12px;
	letter-spacing: .2em;
	text-transform: uppercase;
	color: #777777;
	box-shadow: none;
}
.form-control:focus{
	box-shadow: none;
	border-color: #6f6e6e;
}
textarea.form-control{
	padding-top: 12px;
}
.form-submit{
	font-size: 11px;
	color: #aaa;
}
.form-submit fa{
	font-size: 12px;
}

/* == DEFAULT FORM ELEMENT END == */

blockquote p{
	margin-bottom: 25px;
}

@media (max-width: 991px){
	blockquote p{
		margin-bottom: 0;
	}
	blockquote{
		margin-bottom: 25px;
	}
}
'''

