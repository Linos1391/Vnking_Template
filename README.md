<div align="center">

# Vnking Template

[![][github-shield]][github-url]

[github-shield]:https://img.shields.io/badge/Github-Linos1391-151b23
[github-url]:https://github.com/Linos1391

Template cho vnking.

</div>

# 1. Timeline

![feature_1](assets/feature_1.gif)

- [Hướng dẫn chi tiết ở đây](tutorial/1.%20Timeline.md) hoặc tự điều chỉnh theo brief code bên dưới nếu bạn tự tin.

```
<div style="width: 70%;float: left">

...(Nội dung)
<p id='(tên)'>...</p>

</div>

<div style="position: sticky;top: 6%;float: left;width: 30%;color: white;font-family: Arial;font-weight: bold">

<div style="background-color: #1d2333;border: 3px solid #272f41;padding: 10px;text-align: center;border-radius: 5px;width: 100%;box-shadow: 1px 1px 2px #bbbbbb">

...(Header)

</div>

<div style="margin: auto;width: 95%;background-color: #c490d1;border: 2px solid #1d2333;border-radius: 0px 0px 5px 5px;float: top;padding: 10px;box-shadow: 1px 1px 2px #bbbbbb;height: ...px;overflow: auto"">

<a href="#(tên)">...(Child)</a>

</div>
</div>
```

# 2. Multiple ending

![feature_2](assets/feature_2.gif)

- [Hướng dẫn chi tiết ở đây](tutorial/2.%20Multiple%20Ending.md) hoặc tự điều chỉnh theo brief code bên dưới nếu bạn tự tin.

```
<!--Notice: height div = 52.5 * (số lựa chọn - 1) + 47.5-->

<h3>...(Content / Question)</h3>
1. (action 1)

2. (action 2)

<div style="height: 100px;background-color: #1d2333;border: 2 solid #272f41;padding: 5px;border-radius: 5px;box-shadow: 1px 1px 2px #bbbbbb">

<button class="collapsed" style="height: 40px;width: 100%;background-color: #f0ad4e;color: #ffffff;border-color: #eea236;border-radius: 5px;font-size: 20px;" data-toggle="collapse" data-target="#id1" aria-expanded="false">Lựa chọn 1</button>

<button class="collapsed" style="height: 40px;width: 100%;background-color: #f0ad4e;color: #ffffff;border-color: #eea236;border-radius: 5px;font-size: 20px;" data-toggle="collapse" data-target="#id2" aria-expanded="false">Lựa chọn 2</button>

</div>
<div id="id1" class="collapse" style="height: 0px" aria-expanded="false">

Ending 1

</div>

<div id="id2" class="collapse" style="height: 0px" aria-expanded="false">

Ending 2

</div>
```

