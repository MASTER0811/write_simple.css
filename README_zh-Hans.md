# CSS 程序接口

## 入门 ``` 给刚接触此程序语言```

把此以下连接放入`<head>`元素里

```html
  <link rel="stylesheet" href="https://jy-web.neocities.org/index.css">
```


## 在`class=""`属性里置入
  1. margin `边距`
  ```txt
    只有 0px 5px 10px 15px 20px 25px 30px 35px 40px 45px 50px 55px 60px 65px 70px 75px 80px 85px 90px 95px 100px 
  ```
  ```html
    例子:<div class="mg50"></div>
  ```
  2. padding `内边距离`
  ```txt
    只有 0px 5px 10px 15px 20px 25px 30px 35px 40px 45px 50px 55px 60px 65px 70px 75px 80px 85px 90px 95px 100px 
  ```
  ```html
    例子:<div class="pd50"></div>
  ```
  3. background `背景`
  ```html
    例子:<div class="bgred"></div>
  ```
| 置入在 `class=""` 属性   | 颜色代码 | 颜色名称                                                                                                                               
| ------------------- | ---------- | ----------|
| `bgred` | #ff0000 | Red `红色` |
| `bgyellow` | #ffff00 | Yellow `黄色` |
| `bgaqua` | #00ffff | Aqua `水色` |
| `bgwhite` | #ffffff | White `白色` |
| `bgblack` | #000000 | Black `黑色` |
| `bggray` | #dfe1e5 | Gray `灰色` |
| `bgmediumblack` | #404040 | Medium Black `中黑色` |
| `bglightblue` | #dae4ff | Light Blue `亮蓝色`|
| `bgmediumblue` | #8ab4f8 | Medium Blue `中蓝色`|
| `bgdarkblue` | #4285f4 | Dark Blue `暗蓝色`|
| `bgdarkblue_2` | #1a73e8 | Dark Blue `暗蓝色` |
| `bglightgreen` | #ddf4e1 | Light Green `亮绿色` |
| `bgmediumpink` | #f65d78 | Medium Pink `中粉色`|
| `bgpurple` | #9c00fe | Purple `紫色`|
| `bgbluepurple` | #4e00c2 | Blue Purple `蓝紫色` |
| `bgmediumgrayblue` | #778899 | Medium Gray Blue `中灰蓝色` |

4. width `宽度`
  ```txt
    只有 0px 5px 10px 15px 20px 25px 30px 35px 40px 45px 50px 55px 60px 65px 70px 75px 80px 85px 90px 95px 100px 
  ```
  ```html
    例子:<div class="w50"></div>
  ```
5. height `长度`
```txt
  只有 0px 5px 10px 15px 20px 25px 30px 35px 40px 45px 50px 55px 60px 65px 70px 75px 80px 85px 90px 95px 100px 
```
```html
  例子:<div class="h50"></div>
```
6. position `位置`
 ```html
    例子:<div class="pst_rlt"></div>
 ```
| 置入在 `class=""` 属性   | 位置属性 |                                                                                                                            
| ------------------- | ---------- |
| `pst_rlt` | relative |
| `pst_abs` | absolute |
| `pst_fic` | fixed |
| `pst_sti` | sticky |
| `pst_sta` | static |
| `pst_ust` | unset |

7. display `显示`
 ```html
    例子:<div class="dpy_block"></div>
 ```
可以到此链接关于更多内容 [点击](https://www.w3schools.com/cssref/pr_class_display.asp)
| 置入在 `class=""` 属性   | 显示属性 |                                                                                                                           
| ------------------- | ---------- |
| `dpy_inline` | inline |
| `dpy_block` | block |
| `dpy_contents` | contents |
| `dpy_flex` | flex |
| `dpy_grid` | grid |
| `dpy_il-block` | inline-block |
| `dpy_il-flex` | inline-flex |
| `dpy_il-grid` | inline-grid |
| `dpy_il-table` | inline-table |
| `dpy_lt-item` | list-item |
| `dpy_r-in` | run-in |
| `dpy_table` | table |
| `dpy_t-cpt` | table-caption |
| `dpy_t-clm-group` | table-column-group |
| `dpy_t-hdr-group` | table-header-group |
| `dpy_t-ftr-group` | table-footer-group |
| `dpy_t-row-group` | table-row-group |
| `dpy_t-cell` | table-cell |
| `dpy_t-column` | table-column |
| `dpy_t-row` | table-row |
| `dpy_none` | none |
| `dpy_itl` | initial |
| `dpy_inh` | inherit |

## 常用在主页面
1. Main height `主要长度`
  `height: 100vh;`
```html
  例子:<body class="bd_h"></body>
```
2. Main width `主要宽度`
  `width: 100%;`
```html
  例子:<body class="bd_w"></body>
```
3. 让全部在中间
  `display: flex;`
  ` align-items: center;`
  `justify-content: center;` 
```html
  例子:<body class="allct"></body>
```

## 放多个元素
```txt
如要在 <div> 添加 background:#ff0000; width:50px; height50px;
```
```html
<div class="bgred w50 h50">
```
##
访问我的个人资料页面 [点击](https://github.com/MASTER0811)




