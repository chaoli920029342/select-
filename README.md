# select-

IE7 下select 无法自定义样式，为了个浏览器的统一，可用DIV+JQuery模拟一套
兼容IE7+、firefox、chrome 等多种浏览器

注意事项：
1、如果有多个并列，互相之间会相互影响,IE7下，会被遮挡，为避免，所有 设置层级为：1，选中时，层级改为2
2、<a>标签，缺少herf属性的话，IE7下将无hover效果
3、使用event.stopPropagation();阻止冒泡，event.preventDefault();阻止默认事件