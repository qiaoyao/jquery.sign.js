# jquery.sign.js
jquery签到插件
$(function(){
	$('.sign-box').Sign({
		signBtn: '.sign-btn',//签到按钮
		current: '.sign-date',//当前日期yyyy-mm
    dateMonth: [2017,4],//设置显示月份
    dateChecked: [1, 2, 3, 4, 5, 6, 8]//已签到日期
	})
})
