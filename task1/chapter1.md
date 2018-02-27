# 表格
```
# 横的表头
<table>
    <tr>
        <th></th>
        <th></th>
        <th></th>        
    </tr>
</table>

# 竖的表头
<table>
    <tr>
        <th></th>
        <td></td>
    </tr>
    <tr>
        <th></th>
        <td></td>
    </tr>
    ...
</table>

#合并单元格
...
<tr>
    <th></th>
    <td colspan=2></td>
</tr>
...

```

# input
```
# 二选一
<input type='radio' name='sex' value='man'><label for='man'>男</lable>
<input type='radio' name='sex' value='woman'><label for='woman'>女</lable>

# 多选
<input type='checkbox' value='sing' name='sing' id='sing'><label for='sing'>唱歌</label>
<input type='checkbox' value='article' name='article' id='article'><label for='article'>写作</label>
<input type='checkbox' value='paint' name='paint' id='paint'><label for='paint'>画画</label>
```

# 图片
```
<figure>
    <figcaption></figcation>
    <img src=''>
    
</figure>
```