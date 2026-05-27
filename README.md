<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="ja" lang="ja">

<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<meta http-equiv="Content-Script-Type" content="text/javascript" />
<meta http-equiv="Content-Style-Type" content="text/css" />
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">

<link type="text/css" href="https://www.msweb.jp/msdroot/lib_org/css/smoothness/jquery-ui-1.12.1.custom.min.css" rel="stylesheet" />

<link type="text/css" href="https://www.msweb.jp/msdroot/lib_org/css/jquery.handsontable.full.css" rel="stylesheet" />
<link type="text/css" href="https://www.msweb.jp/msdroot/lib_org/css/Grid.css" rel="stylesheet" />
<link type="text/css" href="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/slick.grid.css" rel="stylesheet" />
<link type="text/css" href="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/slick-default-theme.css" rel="stylesheet" />

<script type="text/javascript" src="https://me.kes.v2.scr.kaspersky-labs.com/7EA5E9BB-55E1-4C31-9C21-4943DDFED2E4/main.js?attr=XkdXwZDOpUKTpfcnxo2TT3CrMzZvdgvtI2BJ5DAD3F4CGikWlesphx16pwXO0pg-6gzdhpWfCVBJDD1kmOcCG4VUNco_qzaQ8Zi5O2neFfViBMJb17Wts33nt3Q2D3xj8VWxcCW-nSJBBYaH9bGBRg" charset="UTF-8"></script><script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_org/jquery-1.8.3.min.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_org/jquery-ui-1.12.1.custom.min.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/jquery.ui.ympicker-custom.js"></script>

<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_org/jquery.tablefix.min.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_org/jquery.handsontable.full.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_org/Grid.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_org/jquery.event.drag-2.2.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/slick.core.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/plugins/slick.autotooltips.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/plugins/slick.cellrangedecorator.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/plugins/slick.cellrangeselector.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/plugins/slick.cellexternalcopymanager.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/plugins/slick.cellselectionmodel.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/plugins/slick.rowselectionmodel.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/plugins/slick.rowmovemanager.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/plugins/slick.checkboxselectcolumn.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/slick.formatters.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/slick.editors.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/slick.dataview.js"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/slick.grid.js?1779868191"></script>
<script type="text/javascript" src="https://www.msweb.jp/msdroot/lib_custom/SlickGrid-gh-pages/slick.remotemodel.js"></script>

<style type="text/css">
* {
margin: 0;
padding: 0;
}
img {
border: 0;
}
html, body {
width: 100%;
height: 100%;
}
#wrap {
width: 100%;
height: 100%;
}
body {
font-size: 100%;
background: #bedef6;
}
/* リンク / */
a, a.mslink {
color: #0011ee;
text-decoration: none;
}
a:hover, a.mslink:hover {
color: #043c78;
text-decoration: underline;
cursor: pointer;
}
/* / リンク */

/* ローディング背景 / */
#loading{
position: fixed;
z-index:1000;
top: 0px;
left: 0px;
width: 100%;
height: 100%;
display: none;
}
html>body .alphaback{
background: url('https://www.msweb.jp/msdroot/images/alphaback.png');
}
* html .alphaback{
filter:progid:DXImageTransform.Microsoft.AlphaImageLoader(src='https://www.msweb.jp/msdroot/images/alphaback.png', sizingMethod='scale');
}
html>body .alphaback_light{
background: url('https://www.msweb.jp/msdroot/images/alphaback_light.png');
}
* html .alphaback_light{
filter:progid:DXImageTransform.Microsoft.AlphaImageLoader(src='https://www.msweb.jp/msdroot/images/alphaback_light.png', sizingMethod='scale');
}
/* / ローディング背景 */

/* /アプリメニュー */
div#app_menu{
background: -moz-linear-gradient(left, #fafdff, #c9e4ff);
background: -webkit-gradient(linear, left top, right top, from(#fafdff), to(#c9e4ff));
filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fafdff', endColorstr='#c9e4ff', GradientType=1);
-ms-filter: "progid:DXImageTransform.Microsoft.gradient(startColorstr='#fafdff', endColorstr='#c9e4ff', GradientType=1)";
background: linear-gradient(to right, #fafdff, #c9e4ff);
border-top: solid 1px #98c9e8;
border-bottom: 1px solid #002277;
left: 0;
position: absolute;
width: 100%;
}
div#app_menu ul{
padding: 0px 10px;
}
div#app_menu ul li{
list-style: none;
text-align: center;
float: left;
padding: 0 3px;
}
div#app_menu a, div#app_menu span{
margin: 3px 0px;
padding: 3px 7px;
color: #007733;
background-color: #ffffff;
border: 1px solid #99bb99;
border-radius: 3px;
-webkit-border-radius: 3px;
-moz-border-radius: 3px;
display: block;
font-weight: bold;
text-decoration: none;
cursor: pointer;
}
div#app_menu a:hover, div#app_menu span:hover, div#app_menu .selected_page {
margin: 3px 0px;
padding: 3px 7px;
color: #005533;
background-color: #f0fff0;
border: 1px solid #008000;
border-radius: 3px;
-webkit-border-radius: 3px;
-moz-border-radius: 3px;
font-weight: bold;
text-decoration: none;
}
/* /アプリメニュー */

/* /ページング */
a.paging_first{
color: #032857;
font-size: 90%;
line-height: 90%;
background: #f0f8ff url(https://www.msweb.jp/msdroot/images/icon_back_04.png) 50% 50% no-repeat;
width: 20px;
float: left;
border: solid 1px #6cbeeb;
padding: 4px;
margin: 2px;
display: block;
text-decoration: none;
text-indent: 120%;
white-space: nowrap;
overflow: hidden;
}
a:hover.paging_first{
background: #a0d8ef url(https://www.msweb.jp/msdroot/images/icon_back_04.png) 50% 50% no-repeat;
color: #17184b;
}
a.paging_prev{
color: #032857;
font-size: 90%;
line-height: 90%;
background: #f0f8ff url(https://www.msweb.jp/msdroot/images/icon_back_03.png) 50% 50% no-repeat;
width: 13px;
float: left;
border: solid 1px #6cbeeb;
padding: 4px;
margin: 2px;
display: block;
text-decoration: none;
text-indent: 120%;
white-space: nowrap;
overflow: hidden;
}
a:hover.paging_prev{
background: #a0d8ef url(https://www.msweb.jp/msdroot/images/icon_back_03.png) 50% 50% no-repeat;
color: #17184b;
}
a.paging_no{
color: #032857;
font-size: 90%;
line-height: 90%;
background-color: #f0f8ff;
float: left;
border: solid 1px #6cbeeb;
padding: 4px;
margin: 2px;
display: block;
text-decoration: none;
}
a:hover.paging_no{
background: #a0d8ef;
color: #17184b;
}
p.now_page{
color: #ffffff;
font-weight: bold;
font-size: 90%;
line-height: 90%;
background-color: #0068b7;
float: left;
border: solid 1px #6cbeeb;
padding: 4px;
margin: 2px;
}
a.paging_next{
color: #032857;
font-size: 90%;
line-height: 90%;
background: #f0f8ff url(https://www.msweb.jp/msdroot/images/icon_next_03.png) 50% 50% no-repeat;
width: 13px;
float: left;
border: solid 1px #6cbeeb;
padding: 4px;
margin: 2px;
display: block;
text-decoration: none;
text-indent: 120%;
white-space: nowrap;
overflow: hidden;
}
a:hover.paging_next{
background: #a0d8ef url(https://www.msweb.jp/msdroot/images/icon_next_03.png) 50% 50% no-repeat;
color: #17184b;
}
a.paging_last{
color: #032857;
font-size: 90%;
line-height: 90%;
background: #f0f8ff url(https://www.msweb.jp/msdroot/images/icon_next_04.png) 50% 50% no-repeat;
width: 20px;
float: left;
border: solid 1px #6cbeeb;
padding: 4px;
margin: 2px;
display: block;
text-decoration: none;
text-indent: 120%;
white-space: nowrap;
overflow: hidden;
}
a:hover.paging_last{
background: #a0d8ef url(https://www.msweb.jp/msdroot/images/icon_next_04.png) 50% 50% no-repeat;
color: #17184b;
}
/* / ページング */

/* 項目テーブル / */
table.field1 {
table-layout: auto;
border-collapse: separate;
border-spacing: 1px;
background: #708090;
margin-bottom: 10px;
}
table.field1 th, table.field1 td {
padding: 3px;
}
table.field1 th {
background: #dae8fc;
color: #000;
text-align: left;
font-weight: normal;
font-size: 14px;
}
table.field1 td {
background: white;
color: #000;
font-size: 14px;
}

table.field1.optnowrap th {
white-space: nowrap;
}
table.field1.optnowrap td {
white-space: nowrap;
}
/* 横 */
table.ifs_field1 {
border-spacing: 0px;
height: 100%;
}
table.ifs_field1 th {
border-right: 1px solid #708090;
}
table.ifs_field1 th:not(:first-child) {
border-left: 1px solid #708090;
}
/* 縦 */
table.ifs_field2 {
border-spacing: 0px;
height: 100%;
width: 100%;
}
table.ifs_field2 th {
border-bottom: 1px solid #708090;
}
table.ifs_field2 th:not(:last-child),
table.ifs_field2 td:not(:last-child) {
border-right: 1px solid #708090;
}
/* 横縦 */
table.ifs_field3 {
border-spacing: 0px;
height: 100%;
width: 100%;
}
table.ifs_field3 th {
border-right: 1px solid #708090;
}
table.ifs_field3 tr:not(:last-child) th,
table.ifs_field3 tr:not(:last-child) td {
border-bottom: 1px solid #708090;
}
table.ifs_field3 th:not(:first-child) {
border-left: 1px solid #708090;
}
/* / 項目テーブル */

/* 検索結果用テーブル / */
table.result1 {
table-layout: auto;
border-collapse: separate;
border-spacing: 1px;
background: #0f2350;
margin-bottom: 10px;
}
table.result1 th, table.result1 td {
padding: 4px;
}
table.result1 th {
color: white;
background: #234C8E;
font-size: 14px;
}
table.result1 td {
background: white;
color: #000;
font-size: 14px;
}

table.result2 {
table-layout: auto;
border-collapse: separate;
border-spacing: 1px;
background: #0f2350;
margin-bottom: 10px;
}
table.result2 th, table.result2 td {
padding: 6px;
}
table.result2 th {
color: white;
background: #234C8E;
font-size: 14px;
}
table.result2 td {
background: white;
color: #000;
font-size: 14px;
}
th.sortcol a {
display: block;
width: 100%;
height: 100%;
color: white;
text-decoration: none;
}
a.desc:after {
content: ' ▼';
}
a.asc:after {
content: ' ▲';
}
/* / 検索結果用テーブル */

/* 入力フォーム / */
input.mstext {
padding: 2px 3px;
border: 1px #666666 solid;
font-family: monospace;
margin: 1px;
}
input.mstext:disabled {
background: #ccc;
}
/* datepicker幅 */
input.mstextdate {
width: 90px;
}
input.mscheckbox {
margin: 1px 2px;
}
input.mscheckbox:disabled {
background: #ccc;
}
input.msradio {
margin: 1px 2px;
}
input.msradio:disabled {
background: #ccc;
}
input.msimportant {
padding: 1px 2px;
margin: 1px;
border-top: 1px #eee solid;
border-left: 1px #eee solid;
border-right: 1px #333 solid;
border-bottom: 1px #333 solid;
background: #ffadad;
cursor: pointer;
font-size: 14px;
}
input.msbutton {
padding: 1px 2px;
margin: 1px;
border-top: 1px #eee solid;
border-left: 1px #eee solid;
border-right: 1px #333 solid;
border-bottom: 1px #333 solid;
background: #ccc;
cursor: pointer;
font-size: 14px;
}
input.mspassword {
padding: 2px 3px;
border: 1px #666666 solid;
margin: 1px;
}
textarea.mstextarea {
border: 1px #666666 solid;
padding: 1px;
font-family: monospace;
resize: none;
margin: 1px;
overflow: auto;
}
select.msselect {
padding: 1px;
border: 1px #666666 solid;
margin: 1px;
}
select.msselect:disabled {
background: #ccc;
}
/* / 入力フォーム */

/* 必須項目 / */
table th.required, table td.required, .required {
color: red;
white-space: nowrap;
}
table th.required:after, table td.required:after, .required:after {
content: ' *'
}
/* / 必須項目 */

.error_position {}

/* 最終更新者表示用スタイル */
div.box_lastupdate_user {
background: none repeat scroll 0 0 #ffffff;
border: 1px solid #ffa500;
display: inline-block;
padding: 3px 7px;
margin-bottom: 5px;
}

/* サブミットパネル / */
#submit_panel {
position: absolute;
left: 0;
width: 100%;
height: 40px;
background: #ddd;
}
.submit_left {
float: left;
padding: 10px;
}
.submit_right {
float: right;
padding: 10px;
}
/* / サブミットパネル */

.clearfix {
clear: both;
}

.grid_header {
font-size: 14px;
text-align: center;
background: #234C8E;
color: #fff;
}
.display_none {
display: none !important;
}
.grid_cell {
font-size: 14px;
}
.slick-row.odd div.grid_cell {
// background:#fff;
}
.slick-row.even div.grid_cell {
// background:#f0f5ff;
}
.grid_cell a {
color: #00f;
}
.grid_center {
text-align: center;
}
.grid_right {
text-align: right;
}
.slick-cell.copied {
background: blue;
background: rgba(0, 0, 255, 0.2);
-webkit-transition: 0.5s background;
}

/* ポップアップアイコン / */
a.popup:after {
content: url("https://www.msweb.jp/msdroot/images/icon_popup_01.png");
}
div#app_menu * a.popup:after {
content: url("https://www.msweb.jp/msdroot/images/icon_popup_02.png");
}
/* / ポップアップアイコン */

/* ダウンロードアイコン / */
/* ノーマルバージョン */
a.download:after {
content: url("https://www.msweb.jp/msdroot/images/icon_download_01.png");
}
/* インラインぽいバージョン */
a.inline:after {
content: url("https://www.msweb.jp/msdroot/images/icon_download_02.png");
}
/* / ダウンロードアイコン */

a.pdf:after {
content: url("https://www.msweb.jp/msdroot/images/icon_pdf.png");
}

/* ヘルプ用ライトボックス / */
.lightbox {
z-index: 1102;
position: absolute;
border: double #000000;
background-color: #ffffff;
padding: 10px;
display: none;
}
#lightbox_closebutton {
position: absolute;
top: -10px;
right: -10px;
width: 20px;
height: 20px;
background: transparent url('https://www.msweb.jp/msdroot/images/icon_close_03.png') 0px 0px;
cursor: pointer;
z-index: 1103;
}
.lightbox_closescreen {
position: absolute;
cursor: pointer;
display: block;
width: 100%;
height: 100%;
z-index: 1101;
}
/* / ヘルプ用ライトボックス */

</style>

<script type="text/javascript">

//ヘルプ用ライトボックス
function lightbox_open(id) {
$("#loading").css("display","block");
$("#loading").append('<div class="lightbox_closescreen" onclick="lightbox_close(\'' + id + '\');"></div>');
$("#"+id).append('<span id="lightbox_closebutton" onclick="lightbox_close(\'' + id + '\')";></span>');

// 中央に再配置
$("#"+id).css("left", $(window).width()/2 - parseInt($("#"+id).css("width"))/2 );
$("#"+id).css("top", "30px");
$("#"+id).fadeIn();
}
function lightbox_close(id) {
$("#loading").css("display","none");
$('.lightbox_closescreen').remove();
$("#"+id).fadeOut();
}


function grid_html(row, cell, value, columnDef, dataContext) {
return value;
}

// -- SlickGridのfrozenColumn系でダイアログ上にて実行時、ヘッダが消えるのを修正
var g_gridheader_ids = [];
function dialog_gridheader_fix(id) {
// 初回読み込み時のみ実行する。
if ( g_gridheader_ids.indexOf(id) < 0 ) {
g_gridheader_ids[g_gridheader_ids.length] = id;
$header_div = $(id + ' div.slick-pane-header');
$panel_div = $(id + ' div.slick-pane-top');
$scroll_div = $(id + ' div.slick-viewport-top');
$panel_div.css('top', $header_div.height() + 'px').css('height', ($panel_div.height() - $header_div.height()) + 'px');
$scroll_div.css('height', ($panel_div.height() - $header_div.height()) + 'px');
}
}

var trover_td_color = ''; //テーブル行マウスオーバー時のtdの色取得用


function table_alternative_set() {
// tableにクラスresultがある場合、行ごとに色を分ける。
for (i=0; i<$('table.result1 tr').length; i++) {
if (i%2 == 1) {
$('table.result1 tr').eq(i).children('td').css('background','#ffffff');
} else {
$('table.result1 tr').eq(i).children('td').css('background','#ddeeff');
}
}
}

$(function() {
// アプリメニュー
$('div#app_menu * a').each(function(){
var url = $(this).attr('href');
if(location.href.match(url) && url == "") {
$(this).addClass('selected_page');
$(this).css("cursor","auto");
$(this).removeAttr('href');
$(this).click(function()
{
return false;
});
}
});

// datepickerのカレンダー画像改行禁止
$('.datepicker').closest("td").css('white-space', 'nowrap');
$('.datepickerm').closest("td").css('white-space', 'nowrap');

table_alternative_set();

// tablefix サンプル
//$('.tablefix').tablefix({width: 1000, height: 400, fixRows: 1, fixCols: 0});

set_datepicker();

// 補完機能のセット
$(document).on('change', '.datepicker', function() {
msdate_autocomplete($(this));
msdate_valid($(this));
});
$(document).on('change', '.datepicker_prev', function() {
msdate_autocomplete($(this));
msdate_valid($(this));
});
$(document).on('change', '.datepickerm', function() {
msdate_month_autocomplete($(this));
msdate_month_valid($(this));
});
$(document).on('change', '.timetext', function() {
timetext_autocomplete($(this));
});
// $(document).on('mouseover', '.datepicker', function() {
// $(this).datepicker(
// {
// changeMonth: true,
// changeYear: true,
// showOn: "button",
// numberOfMonths: 1,
// inline: true,
// dateFormat: 'yy/mm/dd',
// buttonImage: "https://www.msweb.jp/msdroot/images/icon_calendar_01.gif",
// buttonImageOnly: true
// })
// .attr('maxlength','10');
// // $(this).datepicker("show");
// console.log("pic");
// });

});

// =================================================
// == datepickerセット 途中でエレメント追加された時用に関数化
// =================================================
function set_datepicker() {
$('input.datepicker').not('.hasDatepicker').datepicker({
changeMonth: true,
changeYear: true,
showOn: "button",
numberOfMonths: 1,
dateFormat: 'yy/mm/dd',
buttonImage: "https://www.msweb.jp/msdroot/images/icon_calendar_01.gif",
buttonImageOnly: true
})
.prop('maxlength','10');

// 前月初期表示
$('input.datepicker_prev').not('.hasDatepicker').datepicker({
changeMonth: true,
changeYear: true,
showOn: "button",
numberOfMonths: 2,
dateFormat: 'yy/mm/dd',
showCurrentAtPos: 1,
buttonImage: "https://www.msweb.jp/msdroot/images/icon_calendar_01.gif",
buttonImageOnly: true
})
.prop('maxlength','10');

//月までver.
$('input.datepickerm').datepickerm({
showOn: "button",
dateFormat: 'yy/mm',
buttonImage: "https://www.msweb.jp/msdroot/images/icon_calendar_01.gif",
buttonImageOnly: true
})
.prop('maxlength','7');

// カレンダーアイコン マウスオーバー時
$('img.ui-datepicker-trigger').prop('title','Open calender');
$('img.ui-datepicker-trigger').prop('alt','Open calender');
$('img.ui-datepicker-trigger').on('mouseover', function(){
$(this).css('cursor','pointer');
});
}

// 正しい日付かどうかチェック
function msdate_valid($thi) {
if ($thi.val() == "") return;
ret = true;

var result = $thi.val().match(/^([0-9]{4})\/([0-9]{2})\/([0-9]{2})$/);
if (result) {
var yy = parseInt(result[1],10);
var mm = parseInt(result[2],10)-1; //getMonth()は0からなので-1
var dd = parseInt(result[3],10);

var d = new Date(yy,(mm),dd);
if ( !(d.getFullYear()==yy && d.getMonth()==mm && d.getDate()==dd) ) {
ret = false;
}
} else {
ret = false;
}

if (!ret) {
alert('It is not a valid date.[' + $thi.val() + ']');
$thi.val('');
}
}
// 正しい日付かどうかチェックMONTH版
function msdate_month_valid($thi) {
if ($thi.val() == "") return;
ret = true;

var result = $thi.val().match(/^([0-9]{4})\/([0-9]{2})$/);
if (result) {
var yy = parseInt(result[1],10);
var mm = parseInt(result[2],10)-1; //getMonth()は0からなので-1

var d = new Date(yy,(mm),1);
if ( !(d.getFullYear()==yy && d.getMonth()==mm) ) {
ret = false;
}
} else {
ret = false;
}

if (!ret) {
alert('It is not a valid date.[' + $thi.val() + ']');
$thi.val('');
}
}

// 日付の補完
function msdate_autocomplete(obj) {
var ret = $(obj).val().match(/^([0-9]{4})([0-9]{2})([0-9]{2})$/);
if ( ret ) {
var txt = ret[1]+'/'+ret[2]+'/'+ret[3];
$(obj).val(txt);
}
}

// 日付の補完MONTH版
function msdate_month_autocomplete(obj) {
var ret = $(obj).val().match(/^([0-9]{4})([0-9]{2})$/);
if ( ret ) {
var txt = ret[1]+'/'+ret[2];
$(obj).val(txt);
}
}

// 時間の補完
function timetext_autocomplete(obj) {
var ret = $(obj).val().match(/^([0-2][0-9])([0-5][0-9])$/);
if ( ret ) {
var txt = ret[1]+':'+ret[2];
$(obj).val(txt);
}
}

function ajax_eval(str) {
eval(str);
}

// formの入力項目までスクロール(name指定)
function scroll_form(name, tab_block_id, tab_name_id) {
return scroll_form_by_selector('input[name="'+name+'"], select[name="'+name+'"], textarea[name="'+name+'"]', tab_block_id, tab_name_id);
}
// formの入力項目までスクロール(selector指定)
function scroll_form_by_selector(selector, tab_block_id, tab_name_id) {

// タブを囲っているIDと切り替え先のタブID名が指定されていれば、タブを切り替える
if ( tab_block_id != "" && tab_name_id != "" ) {
tab_link_object = $('#'+tab_block_id+' li a[href="#'+tab_name_id+'"]');
if ( tab_link_object.length == 1 ) {
tab_index = $('#'+tab_block_id+' li').index(tab_link_object.closest('li'));
$('#'+tab_block_id).tabs({active:tab_index});
}
}

var p = parseInt( $(selector).offset().top );
p = p - parseInt( $("#header").height() ) - 10;
if ( p < 0 ) { p = 0; }
if ( $("#app_menu").length > 0 ) {
p -= parseInt($("#app_menu").css("height"))+2; // メニューがあればその高さを引く
}
$('#contents').animate({ scrollTop: p }, 'fast');
$(selector).focus();
return false;
}

// == ajaxで1000個以上POSTするときに使用
function post_serialize($form) {
d = $form.serialize();
// "post_serialize"というnameでPOSTさせる
d = d.replace(/%09/g, "+"); // %09はurlエンコされたタブ文字 タブ文字をスペース(+)に変換
d = "post_serialize=" + d.replace(/&/g, "%09");
return d;
}

function loading_on(bg) {
bg = bg || "normal";
if ( bg == "normal" ) {
$('#loading').removeClass('alphaback_light').addClass('alphaback');
} else if ( bg == "light" ) {
$('#loading').removeClass('alphaback').addClass('alphaback_light');
}
$("#loading").css("display","block");
}

function loading_off() {
$("#loading").css("display","none");
}

function number_format(num) {
if ( num == "" || num == undefined ) { return "0"; }
return num.toString().replace(/([0-9]+?)(?=(?:[0-9]{3})+$)/g , '$1,');
}

function flash_check() {
var flash = 0;
try{
var f = new ActiveXObject("ShockwaveFlash.ShockwaveFlash");
flash = 1;
} catch(e) {
flash = 0;
}
if (!flash){
if (navigator.mimeTypes && navigator.mimeTypes["application/x-shockwave-flash"] ?navigator.mimeTypes["application/x-shockwave-flash"].enabledPlugin : 0){
flash = 1;
}
}
if (flash){
return true;
} else {
return false;
}
}

function window_opener_check(opener_url) {
try {
if (window.opener || !window.opener.close) {
var url = window.opener.location.href;
url = url.replace(window.opener.location.search, "");
url = url.replace("/index.php", "/");
opener_url = opener_url.replace("/index.php", "/");
if (url == opener_url) {
return true;
}
}
} catch(e) {
// IEで親閉じてる時、親URLが別ドメインの場合通る
// 親URLが別ドメインの場合、セキュリティ上opener取得が出来ないので必ずエラーが出る。
}
return false;
}

function urlpath() {
var path = window.location.pathname;
var head = path.indexOf('msdroot/');
return path.substr( head + 7 );
}

function nl2br(str) {
if ( str == "" || str == undefined ) { return ""; }
str = str.replace(/\r\n/g,"\n");
str = str.replace(/\r/g,"\n");
str = str.replace(/\n/g,"<br />");
return str;
}

function objdump(obj) {
var s = '';
for ( var prop in obj ) {
s += prop + "=" + obj[prop] + "\n";
}
alert(s);
}

// htmlspecialchars js版
function js_htmlspecialchars(str) {
str = str.replace(/&/g, '&amp;');
str = str.replace(/"/g, '&quot;');
str = str.replace(/</g, '&lt;');
return str.replace(/>/g, '&gt;');
}

function mywindowclose() {
if (/Chrome/i.test(navigator.userAgent)) {
// Chromeの場合、まずは通常のcloseを試みる。
window.close();
}
// ハック的な方法でcloseする。
window.open('about:blank', '_self').close();
}

// 擬似placeholder
function placeholder_set() {
// -- placeholder対応してなければ、valueでplaceholderを擬似的に再現
var supportsInputAttribute = function (attr) {
var input = document.createElement('input');
return attr in input;
};
if (!supportsInputAttribute('placeholder')) {
var place_color = '#757575';
var default_color = '#000';
var place_text;
$('[placeholder]').each(function(){
place_text = $(this).attr('placeholder');
if ($(this).val() == '') {
$(this).val(place_text).css('color', place_color);
} else {
$(this).css('color', default_color);
}
});
$('[placeholder]').focus(function(){
if ($(this).val() == $(this).attr('placeholder')) {
$(this).val('').css('color', default_color);
}
})
.blur(function(){
if ($(this).val() == '') {
$(this).val($(this).attr('placeholder')).css('color', place_color);
} else if ($(this).val() == $(this).attr('placeholder')) {
$(this).css('color', place_color);
}
});
}
}

// 擬似placeholderをクリア
function placeholder_clear() {
var supportsInputAttribute = function (attr) {
var input = document.createElement('input');
return attr in input;
};
if (!supportsInputAttribute('placeholder')) {
var place_text;
$('[placeholder]').each(function(){
if ($(this).val() == $(this).attr('placeholder')) {
$(this).val('');
}
});
}
}

// 直前の日付用テキストに現在日をいれる。
function insert_today(t){
var today = new Date();
var y = today.getFullYear();
var m = today.getMonth()+1;
var d = today.getDate();
if(m < 10){ m = "0" + m; }
if(d < 10){ d = "0" + d; }
$(t).prev('img').prev('input.mstextdate').val( y+"/"+m+"/"+d );
}

// 本日より1週間・1ヶ月・1年のいずれかの日付を出力する
function set_kikan( unit, start_name, end_name, befaft='BEF' ) {
var today = new Date();
var y = today.getFullYear();
var m = today.getMonth()+1;
var d = today.getDate();
if(m < 10){ m = "0" + m; }
if(d < 10){ d = "0" + d; }

if ( befaft=='BEF' ) {
$('[name="'+end_name+'"]').val( y+"/"+m+"/"+d );

switch(unit){
case 'd': break;
case 'w': today.setDate(today.getDate()-7); break;
case 'm': today.setMonth(today.getMonth()-1); break;
case 'y': today.setFullYear(today.getFullYear()-1); break;
}
var y = today.getFullYear();
var m = today.getMonth()+1;
var d = today.getDate();
if(m < 10){ m = "0" + m; }
if(d < 10){ d = "0" + d; }
$('[name="'+start_name+'"]').val( y+"/"+m+"/"+d );
} else if ( befaft=='AFT' ) {
$('[name="'+start_name+'"]').val( y+"/"+m+"/"+d );

switch(unit){
case 'd': break;
case 'w': today.setDate(today.getDate()+7); break;
case 'm': today.setMonth(today.getMonth()+1); break;
case 'y': today.setFullYear(today.getFullYear()+1); break;
}
var y = today.getFullYear();
var m = today.getMonth()+1;
var d = today.getDate();
if(m < 10){ m = "0" + m; }
if(d < 10){ d = "0" + d; }
$('[name="'+end_name+'"]').val( y+"/"+m+"/"+d );
}
}

// ---------------------------------------------------
// -- jqueryui版 OK,Cancelのconfirm
// -- 呼び出し時、ok_evalの指定まででも動く
// -- str : ダイアログに表示させる文字列(htmlタグOK)
// -- ok_eval : OKボタン時のjvascript処理。evalで実行するので文字列形式で
// -- cancel_eval : Cancelボタン時のjvascript処理
// -- w : ダイアログのwidth値
// -- h : ダイアログのheight値
// ---------------------------------------------------
function ui_dialog_confirm(str, ok_eval, cancel_eval, w, h){
cancel_eval = cancel_eval || '';
w = w || 300;
h = h || 240;

// dialogのブロック生成
var $html = $('<div id="ui_dialog_confirm"></div>').html(str);
$('body').append($html);

// jqueryui dialog起動
$('#ui_dialog_confirm').dialog({
autoOpen: true, // 自動起動
width: w,
height: h,
open: function(){
var $ui_box = $(this).parent();
$ui_box.css('font-size', 'small');
// dialogを真ん中よりちょっと上に表示
var posi = parseInt($(window).height()) / 3 - parseInt($ui_box.css('height')) / 2;
if ( posi < 0 ) { posi = 0; }
$ui_box.css('top', parseInt(posi) + 'px');
// #loadingのz-index取得して、loading背景より上に表示させるようにする
var loading_zindex = Number($('#loading').css('z-index')) + 1000;
loading_on();
$ui_box.css('z-index', loading_zindex);
},
close: function( event, ui ) {
// ダイアログ閉じた時に生成したブロックは削除
loading_off();
$(this).remove();
},
buttons: {
'OK': function(){
$(this).dialog('close');
eval(ok_eval);
},
'Cancel': function(){
$(this).dialog('close');
eval(cancel_eval);
}
},
});
}
</script>
<script type="text/javascript">
function myrep_correct_submit( reptable, act_file, submit_data, no_user_session ) {
// user_sessionを使わない場合は0を指定する
no_user_session = no_user_session || 0;
$.ajax({
url: 'https://www.msweb.jp/msdroot/lib_custom/myrep_ajax.php',
cache: false, type: 'post', async: true, dataType: 'html',
data: {
act: 'myrep_correct_submit',
reptable: reptable,
act_file: act_file,
submit_data: submit_data,
no_user_session: no_user_session
}
}).done(function(response){
loading_off();
ajax_eval(response);
}).fail(function(jqXHR, textStatus, errorThrown ) {
loading_off();
alert(textStatus);
// 失敗時処理
}).always(function(response) {
// doneまたはfail実行後の共通処理
loading_off();
});
}
</script>
<script type="text/javascript">
var delay_printing = 0; // 表示中フラグ

// 自分の遅延プロセスを表示する
function delay_list_user() {
$.ajax({
type: 'POST', url: 'https://www.msweb.jp/msdroot/lib_custom/mydelay_ajax.php', cache: false, async: false,
data: { "act":"delay_list_user" },
success: function(v){ ajax_eval(v); },
error: function(a,b,c){ alert('error'); },
});
}

// 遅延プロセスを送信する
function delay_submit( act, uniq_key, data ) {
$.ajax({
type: 'POST', url: 'https://www.msweb.jp/msdroot/lib_custom/mydelay_ajax.php', cache: false, async: false,
data: { "act":act, "uniq_key":uniq_key, "data":data },
success: function(v){ ajax_eval(v); },
error: function(a,b,c){ alert('error'); },
});
}

// 遅延プロセスを中断する
function delay_abort(delay_id) {
if ( confirm('Abort the process, OK ?') == false ) { return false; }
$("#delay_button_abort_"+delay_id).attr("disabled","disabled");
$.ajax({
type: 'POST', url: 'https://www.msweb.jp/msdroot/lib_custom/mydelay_ajax.php', cache: false, async: false,
data: { "act":"delay_abort", "delay_id":delay_id },
success: function(v){ ajax_eval(v); },
error: function(a,b,c){ alert('error'); },
});
}

// 告知を閉じる
function delay_close(delay_id) {
$("#delay_item_"+delay_id).hide('slow');
$.ajax({
type: 'POST', url: 'https://www.msweb.jp/msdroot/lib_custom/mydelay_ajax.php', cache: false, async: false,
data: { "act":"delay_close", "delay_id":delay_id },
success: function(v){ ajax_eval(v); },
error: function(a,b,c){ alert('error'); },
});
}

// 処理終了後のコールバック関数のダミー
// 使いたい場合、実体は呼び出し側で同名の関数を多重定義する
// 意図しない画面で関数が動作しないよう、uniq_keyをチェックすること
function delay_callback(uniq_key) {
}

// 詳細開いていれば詳細画面リロード、indexならdraw_table()
// dir: service , ship 等
// detail_path: 詳細画面のファイル名、detail.php 等
// param: urlにつけるパラメータ。sid=1111 等
function delay_end_reload(dir, detail_path, param) {
if ( urlpath() == '/'+dir+'/' || urlpath() == '/'+dir+'/index.php' ) {
draw_table();
}
if ( urlpath() == '/'+dir+'/'+detail_path ) {
location.href = 'https://www.msweb.jp/msdroot/'+dir+'/'+detail_path+'?'+param;
}
}

</script>
<title>MS-WEB - Certificate Validation Page</title>
</head>
<body>

<style type="text/css">

#contents {
background: #FFF;
overflow: auto;
color: #404040;
text-align: center;
width: 172mm;
margin: auto;
position: relative;
}
#contents .inner {
padding: 0;
}

table {
margin: 0 auto;
width: 90%;
border-collapse: collapse;
font-size: 80%;
}
table th {
text-align: right;
width: 50%;
min-width: 50%;
white-space: nowrap;
}
table td {
text-align: left;
}
table td, table th {
padding: 3px;
border: 1px solid black;
min-width: 50%;
}
table tr:nth-child(even) {
background: #F2F2F2;
}

dd {
display: none;
}
dt {
cursor: pointer;
}
dt span {
position: relative;
}
dt span::before {
position: absolute;
content: "";
width: 0;
height: 0;
border-style: solid;
border-width: 8px 5px 0 5px;
border-color: #FFF transparent transparent transparent;
top: 6px;
bottom: 0;
margin: auto;
left: -16px;
}

</style>

<script type="text/javascript">

$(function() {
$("dl").on( "click", "dt", function () {
$("+dd",this).toggle("slow");
} );
});

</script>

<div id="contents"><div class="inner">

<img src="../images/logo_validity.png" style="position: absolute; width: 130px; left: 15px; top: -5px;">
<br>
<h2 style="padding-top: 30px;">証書の正当性検証ページ</h2>
<h4 style="margin-top: -5px;padding-bottom: 30px;font-weight: normal;">Certificate Validation Page</h4>
<table style="margin: 0 auto;">
<tr><th>COC No.</th><td>2510204B</td></tr>
<tr><th>Date of Isuue</th><td>October/22/2025</td></tr>
<tr><th>Name of Vessel</th><td>KMAX LEADER</td></tr>
<tr><th>IMO Number</th><td>9477414</td></tr>
<tr><th>Model of VDR/S-VDR</th><td>JCY-1800</td></tr>
<tr><th>Serial Number</th><td>MB37123</td></tr>
</table>
<br>
<br>
<div style="background: #B50000; color: #FFF; width: 100%; margin: 0 auto; padding: 10px 0; margin-bottom: 8px;">
<h2>正当性検証</h2>
<h5 style="margin-top: -5px;font-weight: normal;">Legitimacy Verification</h5>
</div>
<br>
<div>
<span style="background:#D36666;color:#FFF;padding:5px 10px;margin-right: 5px;">PDF</span>
Download PDF
</div>
<br>
<h5>証書をダウンロードし比較ご確認ください。</h5>
<p style="margin-top: -5px; font-size: 80%;">Please download and compare the certificates.</p>
<br>
<br>

<dl>
<dt style="color: #FFF;font-size: 80%;background: #A6A6A6;padding: 5px 0;"><span>詳細<p style="margin-top: -6px; font-size: 70%;">Detail</p></span></dt>
<dd>
<br>
<table style="margin: 0 auto;">
<tr><th>COC No.</th><td>2510204B</td></tr>
<tr><th>Order No.</th><td></td></tr>
<tr><th>Date of Isuue</th><td>October/22/2025</td></tr>
<tr><th>Name of Vessel</th><td>KMAX LEADER</td></tr>
<tr><th>IMO Number</th><td>9477414</td></tr>
<tr><th>Flag</th><td>LIBERIA</td></tr>
<tr><th>Class</th><td>RINA (ITALY)</td></tr>
<tr><th>Model of VDR/S-VDR</th><td>JCY-1800</td></tr>
<tr><th>Serial Number</th><td>MB37123</td></tr>
<tr><th>Name of service company</th><td>MACKAY MARINE SERVICES LTD</td></tr>
<tr><th>Address of service company</th><td>921 Seaco Avenue, Deer Park, TX, 77536</td></tr>
<tr><th>Service companys class approval expiry date</th><td>Aug/8/2027</td></tr>
<tr><th>Date of Annual Performance Test</th><td>Oct/16/2025</td></tr>
</table>
</dd>
</dl>
<br>
<br>

</div></div>

</div><!--/wrap-->

</body>
</html>
