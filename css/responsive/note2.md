# Responsive Web Design (RWD)
- Thiết kế web thích ứng
- Đáp ứng giao diện web hoạt động tốt trên các thiết bị khác nhau ( Dựa theo kích thước màn hình)
- Adaptive

## Breakpoint
- Điểm thay đổi 
- Tại đây giao diện sẽ bị thay đổi
- Không có các breakpoint cố định cho mọi dự án, mà chỉ có breakpoint phổ biến

+ 576px
+ 768px
+ 992px
+ 1200px
+ 1400px

## Meta Viewport 

- Viewport: Khung nhìn
* cross browser tester

## Media Queries

@media all |screen| print and (max-width: minValue) and (max-width: maxValue){
    selector {
        /* code css*/
    }
}

@media screen and (max-width:1399px)
/* code css*/

@media screen and (max-width:1199px)
/* code css*/

@media screen and (max-width:991px)
/* code css*/

@media screen and (max-width:767px)
/* code css*/

@media screen and (max-width:575px)
/* code css*/

```css
@media screen and (min-width: 576px){
    /*code css*/
}
@media screen and (min-width: 768px){
    /*code css*/
}
@media screen and (min-width: 992px){
    /*code css*/
}
@media screen and (min-width: 1200px){
    /*code css*/
}
@media screen and (min-width: 1400px){
    /*code css*/
}
```