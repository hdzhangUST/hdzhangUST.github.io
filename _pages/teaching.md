---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

{% include base_path %}

> The fruit of righteousness in peace is sown for them  that make peace. ---<cite>John 3:18</cite>


Teaching
======
`2021 Sep.` Discrete Mathematics, SZU [【Video】](https://space.bilibili.com/61190440/channel/seriesdetail?sid=414728&ctype=0) <br>
`2020 Sep.` Natural Language Processing, SZU<br>
`2020 Sep.` Discrete Mathematics, SZU<br>
`2020 Feb.` Natural Language Processing, HKUST<br>
`2019 Sep.` Discrete Mathematics, SZU<br>
`2019 Feb.` Compilers, SZU [【Video】](https://space.bilibili.com/61190440/channel/detail?cid=115820) <br>
`2018 Sep.` Discrete Mathematics, SZU<br>
`2018 Feb.` Programming Languages, SZU<br>


{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

Teaching Experience
------


<style>
table {
    width: 100%; /*表格宽度*/
    /*max-width: 65em; 表格最大宽度，避免表格过宽*/
    border: 1px solid #dedede; /*表格外边框设置*/
    # margin: 15px 10px; /*外边距*/
    border-collapse: collapse; /*使用单一线条的边框*/
    empty-cells: show; /*单元格无内容依旧绘制边框*/
}
table th,
table td {
  height: 20px; /*统一每一行的默认高度*/
  border: 1px solid #dedede; /*内部边框样式*/
  padding: 0 10px; /*内边距*/
}

table th {
    font-weight: bold; /*加粗*/
    text-align: center !important; /*内容居中，加上 !important 避免被 Markdown 样式覆盖*/
    background: rgba(158,188,226,0.2); /*背景色*/
}
table tbody tr:nth-child(2n) {
    background: rgba(158,188,226,0.12); 
}
table tr:hover {
    background: #efefef; 
    font-color: #094CD1;
}
table th {
    white-space: nowrap; /*表头内容强制在一行显示*/
}
table td:nth-child(1) {
    white-space: nowrap; 
}
[].slice.call(document.querySelectorAll('table')).forEach(function(el){
    var wrapper = document.createElement('div');
    wrapper.className = 'table-area';
    el.parentNode.insertBefore(wrapper, el);
    el.parentNode.removeChild(el);
    wrapper.appendChild(el);
})
</style>


|  | University | Class | Course | Evaluation |
| :--- | :----: | :----: | :----: | :----: |
| 2021 Spring |  SZU | Undergraduate | Discrete Mathematics  | 98.1/100 (Top 7.1%)   |
| 2020 Fall |  SZU | Undergraduate | Discrete Mathematics  | 93.8/100   |
| 2020 Fall |  SZU | Undergraduate | Natural Language Processing  | 85.2/100   |
| 2020 Spring | HKUST | Master | Natural Language Processing | - |
| 2020 Spring | SZU | Undergraduate | Compilers | 85.7/100 |
|	2019 Fall | SZU | Undergraduate | Discrete Mathematics | 94.6/100 |
|	2019 Spring | SZU | Undergraduate | Compilers | 100/100 (Top 0.7%)|
|	2018 Fall | SZU | Undergraduate | Discrete Mathematics | 93.6/100 (Top 9.8%)|
|	2018 Spring | SZU | Undergraduate | Programming Languages | 82.7/100 |

