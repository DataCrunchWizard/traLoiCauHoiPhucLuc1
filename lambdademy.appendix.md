1. Việc tách riêng HTML và CSS để làm cho code của file.hmtl gọn gàng hơn, giúp chúng ta dễ fixbug khi có bug xảy ra, dùng lại một các thuộc tính bên CSS nhanh nhất...

2. -ID là dùng để xác định một đối tượng duy nhất mình sử dụng(VD: 1 người chỉ có 1 CMND
 - Class là gôm tất cả các đối tượng lại với nhau. Các đối tượng trong class có tính kế thừa lẫn nhau.
*Sự khác nhau của Class và ID:
      1. ID mạnh hơn Class
        . ID chỉ được gắn với 1 thẻ (thường là <div>) trên file HTML ID không xuất hiện nhiều lần.
        . Class có thể được gán với nhiều thẻ và xuất hiện nhiều lần trong HTML
      2. Có thể dùng nhiều thuộc tính ID trong một trang nhung mỗi thuộc tính có một tên riêng để định nghĩa
      3. Dùng ID để định danh các thẻ, phục vụ cho việc lập trình javacript.

3. Elements là một đơn vị nội dung trong HTML được cấu tạo bởi các thẻ HTML và văn bản hoặc các phương tiện chứa nó. Nói nôm na là bao gồm
thẻ đóng(<tag>) và thẻ mở(<tag>).
        VD: <p> Hello Wordl </p> 

4. Tags là thành phần được bao quanh bởi dấu nhọn mở(<) và dấu đóng(>)
         VD: <tag>

5. Attributes(thuộc tính) là các tên nằm bên trong thẻ dùng để bổ sung thông tin cho thẻ. <tag nameAttributes="valueAttributes";...>
       VD: <meta charset="utf-8"/>

6. 

7. Thẻ div(division) là thẻ dùng để gom nhóm nhiều phần tử. Tạo bố cục cho Wedsite. khi ta dùng thẻ div nó sẽ chia nội dung thành các khu
vực khác nhau. 
    *Cấu tạo 1 Wedsite gồm có 4 phần Header:
      1. Header (banner, logos)
      2. Content (hiển thị nội dung)
      3. Sidebar (cột bên cạnh nội dung)
      4. Footer (khu vực chân Wedsite)
 
 8. Seletor CSS là dùng để truy vấn các thẻ trong HTML. trong một file HTML có nhiều thẻ giống nhau và thông thường chúng sẽ được đặt các ID 
 và Class cho các thẻ để phân. Trong CSS sẽ dựa vào ID và Class truy vấn tới 
                    VD: index.html
                        <body>
                <div class="banner">Thẻ div</div>
            </body>
                        style.css
                        .banner{
                        color: red;
                        }
 9. Properties(thuộc tính) là các giá trị được liên kết với một đối tượng JavaScript. Một đối tượng JavaScript là một tập hợp các thuộc tính không có thứ tự.

Các thuộc tính thường có thể được thay đổi, thêm và xóa, nhưng một số chỉ được đọc.

10. Qurery string là tập hợp các data ở dạng key=value mà ta được vào URL của Wedsite. Query string truyền tải dữ liệu lên sever và gọi đây
là phương thức GET ( là hình thức client gửi data lên sever bằng cách bổ sung các tham số phía sau URL).

11. 

12. Tính thừa kế trong CSS giúp tối ưu hóa dung lượng của file.css. Sử dụng lại cho nhiều trang trong wedsite. Được áp dụng cho nhiều vùng trên một trang, có thể 
dùng cho nhiều dự án khác.

13. 2 attribute trong CSS là posittion và float
   * Attribute position xác định loại của phương pháp định vị trí cho thành phần. Dùng kèm với các thuộc tính định vị trí: left, right, bottom, top
   * Attribute Float trong CSS đóng vai trò rất quan trọng trong việc xây dựng chia bố cục HTML của một trang web. Dùng kèm với left, right, none

14. 3 cách nhúng CSS vào html
        1. inline ( chèn trực tiếp vào html)
        2. internal (được đặt trong mục <head> của một trang nhất định)
        3. external ( tạo 1 file.css riêng biệt)

15. 



