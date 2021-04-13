<!--
 * @Author: XuCheri
 * @Date: 2021-04-13 23:30:31
 * @LastEditTime: 2021-04-13 23:43:47
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \To-Do-List\README.md
-->
# To-Do-List

该系统可以实现学生信息的增删改查，并且可以将数据进行可视化展示

## 布局

>采用HTML5 + css 菜单栏用媒体查询做了响应式，在手机，平板，电脑均可以正常显示

>logo用css3做出动画效果

## 事件

>用jQuery来绑定事件实现学生的增删改查
>用jQuery里的ajax函数发送网络请求给后端来获取学生信息

>当学生数量过多的时候会产生翻页，这里使用一个turnPage插件来实现

## 可视化
>用echarts将获取到的数据展现为饼图，将echarts中需要用到的功能单独分离出来形成一个pie.js并对其进行配置


转载注明出处