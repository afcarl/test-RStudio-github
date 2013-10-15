業務でも使える RStudio + github で作る解析環境のひとつの理想形
======================================

## knitr を使えば R のコードと結果を HTML に出力できる

xy 平面上に乱数を 100 組生成して描画する．


```r
data <- data.frame(x = rnorm(100), y = rnorm(100))
plot(data)
```

![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1.png) 

