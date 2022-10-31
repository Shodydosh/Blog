#Tại sao không chỉ css cho một trong ba cái

![image](https://user-images.githubusercontent.com/87895460/199024526-539244c9-5b9f-42f0-b110-4b3cda9fc14c.png)

- * thì tác động lên toàn bộ các phần tử
- html hoặc :root dùng cho đặt biến trong CSS, đặt font-size mặc định cho trang web khi dùng đơn vị rem. VD: font-size: 62.5%
- body dùng cho trường hợp đặt background cho thân trang và thêm những thuộc tính CSS có tính thừa kế (inherited) chung/phổ biến trong toàn trang như: font-family, font-size, line-height, v.v. Mặc dù viết ở HTML hay :root cũng OK, nhưng tình huống này viết ở body sẽ hợp lý hơn, vì body nó là thẻ cha lớn nhất cho phần nhìn thấy được trên 1 trang web. Trong trường hợp dùng font-size: 62.5% tại thẻ html, rồi muốn đặt font-size mặc định cho trang tương ứng 16px (default) thì cũng cần thêm font-size: 1.6rem tại thẻ body => Để các thẻ bên trong nó thừa kế lại.
