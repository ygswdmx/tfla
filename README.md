99久久国产精品免费人妻久99久久国产

html5中新增两个表单属性，分别autocomplete和novalidate属性

1.autocomplete属性

   该属性用于控制自动完成功能的开启和关闭。可以设置表单或者input元素，有两个属性值，当设置为on时，启动该功能；当设置off时，关闭该功能。启用该功能后，当用户在自动完成域开始输入时，浏览器就会在该域中显示填写的选项。用户每提交一次，就会增加一个用于选择的选项  

<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title></title>
</head>
<body>
   <form action="#" method="get" autocomplete="on">
      请输入：<input type="text"  name="txt" /><br/>
       <input type="submit" />
   </form>
</body>
</html>

2.novalidate属性

  input输入类型，当提交表单时，会对这些输入内容进行验证。而novalidate属性则用于在提交表单时不对form或input进行验证：
