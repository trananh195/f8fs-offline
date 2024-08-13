## Responsive web design
- Thiết kế web thích ứng với các thiết bị khác nhau
- Trước khi có Responsive ==> Adaptive
- responsive sử dụng  css để thay đổi giao diện dựa vào kích thước màn hình

## breakpoint
 - Điểm dừng kích thước màn hình mà tại đó giao diện sẽ thay đổi
 - Không có breakpoint cố định cho mọi dự án
 - Chỉ có breakpoint phổ biến ( có thể thay đổi theo từng dự án)

 Breakpoint phổ biến:
 -576px
 -768px
 -992px
 -1200px
 -1400px

## Media queries
- At-rule có sẵn của css
```css
@media all|screen|print and (min-width:value) and (max-width:value) {
    selection {
        code css
    }
}
```

```css
@media screen and (max-width:1399px) {
    //Selector CSS
}
@media screen and (max-width:1199px) {
    //Selector CSS
}
@media screen and (max-width:991px) {
    //Selector CSS
}
@media screen and (max-width:767px) {
    //Selector CSS
}
@media screen and (max-width:575px) {
    //Selector CSS
}


```

