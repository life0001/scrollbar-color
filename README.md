# scrollbar-color   自定义滚动条  不兼容火狐浏览器
<pre>
//启用自定义滚动条设置
element ::-webkit-scrollbar {
    width: 7px;
    background-color: #f0f0f0;
}

//滚动条上的块样式设置
::-webkit-scrollbar-thumb {
    background-color: #6a8bfa;
}
::-webkit-scrollbar-button:start:decrement, ::-webkit-scrollbar-button:end:increment{
    width:10px;height:10px; //上下箭头宽度和高度设置
}   
::-webkit-scrollbar-button:vertical:decrement{
    background:url(../img/bg.png) -29px -10px;  //上箭头样式设置
}  
::-webkit-scrollbar-button:vertical:decrement:hover{
    background-position: -29px 0;  //上箭头事件样式设置
}          
::-webkit-scrollbar-button:vertical:increment{
    background:url(../img/bg.png) -20px -10px;   //下箭头样式设置
}    
::-webkit-scrollbar-button:vertical:increment:hover{
    background-position: -20px 0;  //下箭头事件样式设置
}          
::-webkit-scrollbar-thumb:vertical{
    height:100px;background:#d0d0d0;   //底部背景色
}  
::-webkit-scrollbar-thumb:vertical:hover{
    background:#aaaaab;   //底部背景色鼠标事件
}         
::-webkit-scrollbar-thumb:horizontal{
    width:80px;height:10px;background-color:#ccc;
}
</pre>

<a href="http://www.lyblog.net/detail/314.html" target="_blank">1. webkit 内核浏览器滚动条颜色设置</a><br/>
<a href="http://edu.cnzz.cn/201212/836936e7.shtml" target="_blank">2. webkit滚动条详解</a><br/>
<a href="http://passer-by.com/widget/jquery-scrollbar/" target="_blank">3. js模拟滚动条</a><br/>
