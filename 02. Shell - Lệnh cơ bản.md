# Shell và một số lệnh cơ bản

---

# Mục lục

* [1. Shell Linux là gì ? ](#1)

* [2. Những phiên bản Shell Linux](#2)

* [3. Các lệnh cơ bản](#3)

* [Tham khảo](#tk)

---
![Shell Scripting Bash](https://user-images.githubusercontent.com/79433103/109039264-2d14ad80-76ff-11eb-8c4c-b04e9103ae42.jpg)


<a name = '1'></a>
## 1. Shell Linux là gì ?
- Chúng ta đã biết Kernel Linux là nhân kết nối giữa hệ thống phần cứng với các phần mềm. Một hệ điều hành thường sẽ có thêm giao diện, phần mềm. Và để tối ưu các thao tác, tiết kiệm thời gian cho các nhà phát triển (developer) chúng ta cần thêm một công cụ để đảm nhận nhiệm vụ `giao tiếp` với nhân Kernel. Và đó là sự ra đời của `Shell`.


  - `Shell` là một chương trình (program) chạy trên hệ điều hành. Đây là một **user interface**, giao diện người dùng tương tác trực tiếp với hệ điều hành. Mọi lệnh của người dùng đều thông qua Shell rồi đến lớp nhân Kernel và sau đó phần cứng thực hiện yêu cầu. 
  - Ngoài ra, `Shell` còn là một **trình biên dịch**. Nó phân giải các lệnh về thành ngôn ngữ máy, trước khi chuyển tới lõi Kernel và thực thi. 
  - Sau một quá trình phát triển, `Shell` đã hỗ trợ người dùng nhiều tính năng, giúp người sử dụng thao tác chuyên nghiệp và tiện lợi hơn như là: thao tác phím tắt `tab` để gợi ý câu lệnh, ....
  - Shell cũng có chức năng lập trình để giúp các nhà phát triển (developer) có thể tự động hóa công việc, lập trình chạy tự động các jobs, etc. 

<a name = '2'></a>
## 2. Những phiên bản Shell Linux
   - Vì là một program nên `Shell` cũng có đa dạng nhiều phiên bản, phù hợp với nhiều đối tượng và mục đích sử dụng. Các phiên bản được tạo nên vì các thói quen của các nhóm đối tượng, nhu cầu và để thuận tiện nhất cho nhóm người sử dụng đó. 
   - **BASH*
      - Đây được coi là phiên bản Shell phổ biến nhất trong hệ điều hành Linux. Nó được tạo nên từ shell gốc của Unix và được cài mặc định trên một số phiên bản của Linux.
      - BASH có nhiều tính năng và khá hoàn thiện, các câu lệnh và thao tác có phần quen thuộc với các nhà phát triển (developer)
   - **KornShell*
      - Khá giống với BASH, điểm nổi bật của KornShell là cấu trúc vòng lặp và gợi ý câu lệnh đa dạng hơn so với BASH Shell.
      - BASH và KornShell có thể thay đổi trực tiếp trên Command Lines mà không bị mất hay phải cài đặt lại hệ điều hành. Chúng có thể chuyển đổi để thuận tiện cho việc sử dụng.
   - **TCSH**
      - Đây là phiên bản cải tiến của `C Shell` với các cải tiến như: Chỉnh sửa dòng lệnh, truy cập lịch sử dòng lệnh, etc.
      - Với những lập trình viên đã quen làm việc với ngôn ngữ C thì đây là phiên bản phù hợp vì ngôn ngữ script.
   - **Z Shell**
      - Được tích hợp nhiều tính nắng của các phiên bản Shell nên Z Shell khá đa dạng tính năng như: sửa lỗi chính tả vượt trội, hoàn thiện dòng lệnh, lịch sử được chia sẻ trên terminal, ....
   #### - Các phiên bản `Shell` chỉ thật sự khác nhau khi vào các phân vùng cấu hình nên có thể có những phiên bản nhiều tính năng nhưng khi sử dụng lại không phù hợp với mục đích và nhu cầu của người dùng. 
   
<a name = '3'></a>
## 3.Các lệnh cơ bản
- Câu lệnh trong Command Lines đều có dạng **Command [option] [argument]** trong đó:
   - Command là câu lệnh muốn thực thi
   - [option] là cách câu lệnh được thực thi hoạc cách câu lệnh được diễn giải
   - [argument] là đối tượng mà ta muốn đề cập 
 
  **Lưu ý: những phần trong dấu [] có thể bỏ trống và câu lệnh vẫn được thực thi**
   
#### Bảng câu lệnh hay gặp
|Dòng lệnh|Tác dụng|
|---------|--------|
|ls -a|Hiện thị các file cấu hình ẩn|
|ls -h|Thêm các trường đơn vị 
|ls -l|Hiển thị đầy đủ thông tin của file|
|ls -t|Liệt kê theo thời gian|

![lenh ls](https://user-images.githubusercontent.com/79433103/109109862-a85e7980-7768-11eb-9056-97e22706c922.png)

|Dòng lệnh|Tác dụng|
|---------|--------|
|pwd| (print working directory) cho biết người dùng đang làm việc tại thư mục nào|
|cd| thay đổi vị trí sang thư mục khác|
|cat| sử dụng để xem các file không quá dài|
|head| show ra 10 dòng đầu tiên của file|
|tail| show ra 10 dòng cuối cùng của file|

<a name = 'tk'></a>
## Tham Khảo
[1.](https://quantrimang.com/linux-shell-la-gi-cac-linux-shell-pho-bien-nhat-174496)

[2. Giáo trình LPIC1]

[3. Github](https://github.com/quangln94/Linux/blob/master/Overview/Content/02_Working_with_file.md)
