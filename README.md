# utils
用java语言编写的文本内容替换脚本
功能如下：

原始文本：

```
{
label: intl.get(`.model.startDate`).d('开始日期'),
name: 'startDate',
type: 'dateTime',
},
{
label: intl.get(`.model.endDate`).d('结束日期'),
name: 'endDate',
type: 'dateTime',
},
```

功能：

将name后的字符串替换成model后的字符串
