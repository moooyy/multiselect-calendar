multiselect-calendar
=====================
### demo

http://moooyy.github.io/multiselect-calendar



### 产生
>基于已有项目已经使用了jqueryui框架, 无法满足现有需求

>本功能非扩展方法, 无需额外引用库, 仅针对jqueryui的自带方法的回调进行了一些操作, 实现了简单的日历多选


### 原理
>通过onSelect(date)传入选中日期;

>通过beforeShowDay(selecteable, class)把历次选中日期设为选中样式;

>初始化和每次onSelect之后都会触发 beforeShowDay~

>是的, 就这这么简单~


### set
```javascript
$("#datepicker").data("multidate",["2014-08-01", "2014-08-03"]);
```

### get
```javascript
$("#datepicker").data("multidate");
```
