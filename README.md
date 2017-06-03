# app-calendarPlugin
移动端仿ios日历插件</br>
使用指南：</br>
    点击输入框触发</br>
    var calendar = new datePicker();</br>
    calendar.init({</br>
        'trigger': '#demo1', /*按钮选择器，用于触发弹出插件*/ </br>
        'type': 'date',/*模式：date日期；datetime日期时间；time时间；ym年月；*/</br>
        'minDate':'1900-1-1',/*最小日期*/</br>
        'maxDate':'2100-12-31',/*最大日期*/</br>
        'onSubmit':function(){/*确认时触发事件*/</br>
            var theSelectData=calendar.value;</br>
        },</br>
        'onClose':function(){/*取消时触发事件*/</br>
        }</br>
    });</br>
