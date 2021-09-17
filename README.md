# utils
用java语言编写的文本内容替换脚本
功能如下：
功能1：对单一文本进行操作，将批量的指定位置的字符串替换为另一指定位置的批量字符串
功能2：对两个文本进行操作，将file1的批量的指定位置的字符串替换为file2的指定位置的批量字符串
功能1示例：
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


