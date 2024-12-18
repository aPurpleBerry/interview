# flex

> https://www.ruanyifeng.com/blog/2015/07/flex-grammar.html
>
> https://www.bilibili.com/video/BV1n54y1n7mC/?spm_id_from=333.337.search-card.all.click&vd_source=ceab44fb5c1365a19cb488ab650bab03

## 容器的属性

- `flex-direction`主轴的方向（即项目的排列方向）

  ```
  row（默认值）：主轴为水平方向，起点在左端。
  row-reverse：主轴为水平方向，起点在右端。
  column：主轴为垂直方向，起点在上沿。
  column-reverse：主轴为垂直方向，起点在下沿。
  ```

- `justify-content`属性定义了项目在主轴上的对齐方式。

  ```
  flex-start（默认值）：左对齐
  flex-end：右对齐
  center： 居中
  space-between：两端对齐，项目之间的间隔都相等。
  space-around：每个项目两侧的间隔相等。所以，项目之间的间隔比项目与边框的间隔大一倍。
  ```

- `align-items`属性定义项目在交叉轴上如何对齐。

  ```
  flex-start：交叉轴的起点对齐。
  flex-end：交叉轴的终点对齐。
  center：交叉轴的中点对齐。
  baseline: 项目的第一行文字的基线对齐。
  stretch（默认值）：如果项目未设置高度或设为auto，将占满整个容器的高度。
  ```

- `flex-wrap`：默认情况下，项目都排在一条线（又称"轴线"）上。`flex-wrap`属性定义，如果一条轴线排不下，如何换行。

- `align-content`属性定义了多根轴线的对齐方式。如果项目只有一根轴线，该属性不起作用。

## 项目的属性

```
order
flex-grow
flex-shrink
flex-basis
flex
align-self
```

