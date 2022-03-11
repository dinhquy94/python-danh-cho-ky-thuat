![Tài liệu lập trình Python trong kỹ thuât](https://github.com/dinhquy94/python-danh-cho-ky-thuat/blob/main/template.jpg "Tài liệu lập trình Python trong kỹ thuât")


# Giới thiệu về tài liệu
Lập trình là việc điều khiển máy tính thực hiện một nhiệm vụ nào đó bằng các dòng lệnh. Lập trình được sinh ra để giải quyết các vấn đề từ đơn giản đến phức tạp để tiết kiệm thời gian của con người.
Lập trình được ứng dụng rộng rãi trong nhiều lĩnh vực khác nhau đặc biệt là trong các lĩnh vực về Khoa học - Kỹ thuật. Ngày nay, lập trình không chỉ là công việc của các lập trình viên, ai cũng đều nên biết về lập trình và biến nó thành trợ thủ đắc lực cho công việc của mình. Huyền thoại Steve Jobs đã từng nói rằng: “Ai cũng nên học lập trình“.

Xuất phát từ những lý do quan trọng của việc học lập trình, tôi biên soạn tài liệu "Lập trình python dùng trong kỹ thuật" tập trung vào việc giới thiệu và hướng dẫn sử dụng python - ngôn ngữ phổ biến vì đơn giản và dễ tiếp cận với tất cả mọi người và giới thiệu, hướng dẫn sử dụng các thư viện dùng trong các ngành kỹ thuật như **numpy** và **scipy** cùng với kỹ thuật visualize dữ liệu bằng **matplotlib**.

 Ngoài ra cuốn sách cũng cung cấp jupyter notebook đi kèm từng phần để người đọc dễ dàng thực hành các nội dung trong cuốn sách.
 
Trong tài liệu này, tôi có tham khảo một số giáo trình nước ngoài về python và bài viết của một số blog. Tài liệu mang tính tổng hợp và biên soạn để người học có thêm tài nguyên để tiếp cận với lập trình python.

# Các nội dung chính

[Chương 1](#ch--ng-1)
  * [1.1 Mô hình tính toán.](#11-m--h-nh-t-nh-to-n)
    + [1.1.1 Giới thiệu](#111-gi-i-thi-u)
    + [1.1.2 Mô hình tính toán](#112-m--h-nh-t-nh-to-n)
    + [1.1.3. Lập trình hỗ trợ mô hình tính toán](#113-l-p-tr-nh-h--tr--m--h-nh-t-nh-to-n)
  * [1.2. Vì sao sử dụng python](#12-v--sao-s--d-ng-python)
  * [1.3. Các phiên bản python](#13-c-c-phi-n-b-n-python)
  * [1.4 Cài đặt Python](#14-c-i---t-python)
- [Chương 2: Tính toán python](#ch--ng-2--t-nh-to-n-python)
  * [2.1 Chạy chương trình đầu tiên](#21-ch-y-ch--ng-tr-nh---u-ti-n)
  * [2.2 Tính toán trong python](#22-t-nh-to-n-trong-python)
  * [2.3 Phép chia số nguyên](#23-ph-p-chia-s--nguy-n)
    + [2.3.1 Tránh chia lấy nguyên trong python](#231-tr-nh-chia-l-y-nguy-n-trong-python)
    + [2.3.2 Tại sao lại cần chú ý phép chia số nguyên trong python](#232-t-i-sao-l-i-c-n-ch----ph-p-chia-s--nguy-n-trong-python)
  * [2.4 Các hàm toán học trong python](#24-c-c-h-m-to-n-h-c-trong-python)
  * [2.5 Biến trong python](#25-bi-n-trong-python)
  * [2.6 Một số toán tử gán bất thường](#26-m-t-s--to-n-t--g-n-b-t-th--ng)
    + [2.6.1 Toán tử +=](#261-to-n-t----)
- [Chương 3: Các kiểu dữ liệu và cấu trúc dữ liệu](#ch--ng-3--c-c-ki-u-d--li-u-v--c-u-tr-c-d--li-u)
  * [3.1 Xác định các kiểu dữ liệu](#31-x-c---nh-c-c-ki-u-d--li-u)
  * [3.2 Kiểu số](#32-ki-u-s-)
    + [3.2.1 Số nguyên](#321-s--nguy-n)
    + [3.2.2 Kiểu long](#322-ki-u-long)
    + [3.2.3 Kiểu dữ liệu số thực](#323-ki-u-d--li-u-s--th-c)
    + [3.2.4 Số phức](#324-s--ph-c)
    + [3.2.5 Hàm áp dụng cho tất cả các kiểu dữ liệu số](#325-h-m--p-d-ng-cho-t-t-c--c-c-ki-u-d--li-u-s-)
  * [3.3 Kiểu dữ liệu tuần tự](#33-ki-u-d--li-u-tu-n-t-)
    + [3.3.1 Kiểu dữ liệu String](#331-ki-u-d--li-u-string)
    + [3.3.2 Kiểu dữ liệu List](#332-ki-u-d--li-u-list)
    + [3.3.3 Kiểu dữ liệu Tuple](#333-ki-u-d--li-u-tuple)
    + [3.3.4 Chỉ mục trong kiểu dữ liệu tuần tự](#334-ch--m-c-trong-ki-u-d--li-u-tu-n-t-)
    + [3.3.5 Cắt lát](#335-c-t-l-t)
    + [3.3.6 Kiểu dữ liệu Dictionary](#336-ki-u-d--li-u-dictionary)
  * [3.4 Truyền tham số cho hàm](#34-truy-n-tham-s--cho-h-m)
    + [3.4.1 Tham số bắt buộc](#341-tham-s--b-t-bu-c)
    + [3.4.2 Tham số dạng từ khoá](#342-tham-s--d-ng-t--kho-)
    + [3.4.3 Tham số mặc định](#343-tham-s--m-c---nh)
    + [3.4.4 Tham số biến động \*args](#344-tham-s--bi-n---ng---args)
    + [3.4.5 Tham số biến động với keyword argument, \*\*kwargs](#345-tham-s--bi-n---ng-v-i-keyword-argument------kwargs)
- [Chương 4: Vào ra trong Python](#ch--ng-4--v-o-ra-trong-python)
  * [4.1 In ra màn hình](#41-in-ra-m-n-h-nh)
  * [4.2 Nhập dữ liệu từ bàn phím](#42-nh-p-d--li-u-t--b-n-ph-m)
  * [4.3 Nhập xuất dữ liệu từ File](#43-nh-p-xu-t-d--li-u-t--file)
    + [4.3.1 Mở File trong Python](#431-m--file-trong-python)
    + [4.3.2 Đóng file](#432---ng-file)
    + [4.3.3 Ghi File trong Python](#433-ghi-file-trong-python)
    + [4.3.3 Đọc File trong Python](#433---c-file-trong-python)
    + [4.3.4 Một số phương thức làm việc với File trong Python](#434-m-t-s--ph--ng-th-c-l-m-vi-c-v-i-file-trong-python)
- [Chương 5: Điều khiển luồng](#ch--ng-5---i-u-khi-n-lu-ng)
  * [5.1 Luồng cơ bản](#51-lu-ng-c--b-n)
    + [5.1.1 Kiểu dữ liệu bool và biểu thức điều kiện](#511-ki-u-d--li-u-bool-v--bi-u-th-c--i-u-ki-n)
      - [Kiểu dữ liệu bool](#ki-u-d--li-u-bool)
      - [Biểu thức điều kiện](#bi-u-th-c--i-u-ki-n)
    + [5.2.1 Lệnh if](#521-l-nh-if)
    + [5.2.2 Lệnh if...else](#522-l-nh-ifelse)
  * [5.3 Vòng lặp For](#53-v-ng-l-p-for)
  * [5.4 Vòng lặp while](#54-v-ng-l-p-while)
  * [5.5 Xử lý ngoại lệ](#55-x--l--ngo-i-l-)
- [Chương 6: Hàm và module](#ch--ng-6--h-m-v--module)
  * [6.1 Hàm](#61-h-m)
  * [6.2 Module](#62-module)
  * [6.3 Hàm vô danh](#63-h-m-v--danh)
  * [6.4 Map](#64-map)
  * [6.5 Map function](#65-map-function)
  * [6.6 Reduce function](#66-reduce-function)
  * [6.7 List Comprehension](#67-list-comprehension)
- [Chương 7: Numerical Python (numpy)](#ch--ng-7--numerical-python--numpy-)
  * [7.1 Cài đặt numpy](#71-c-i---t-numpy)
  * [7.2 Sử dụng numpy](#72-s--d-ng-numpy)
    + [7.2.1 Tạo mảng](#721-t-o-m-ng)
    + [7.2.2 Phép toán số học với Numpy](#722-ph-p-to-n-s--h-c-v-i-numpy)
    + [7.2.3 Cắt lát và chỉ mục](#723-c-t-l-t-v--ch--m-c)
  * [7.3 Các phép toán trên ma trận](#73-c-c-ph-p-to-n-tr-n-ma-tr-n)
    + [7.3.1. Nhân ma trận với một vô hướng](#731-nh-n-ma-tr-n-v-i-m-t-v--h--ng)
    + [7.3.2. Cộng 2 ma trận](#732-c-ng-2-ma-tr-n)
    + [7.3.3. Nhân 2 ma trận](#733-nh-n-2-ma-tr-n)
    + [7.3.4. Chuyển vị ma trận](#734-chuy-n-v--ma-tr-n)
    + [7.3.5 Ma trận nghịch đảo](#735-ma-tr-n-ngh-ch---o)
    + [7.3.6 Phép nhân từng phần tử Hadamard](#736-ph-p-nh-n-t-ng-ph-n-t--hadamard)
    + [7.3.7 Các phép toán theo từng phần tử (Hadamard) khác](#737-c-c-ph-p-to-n-theo-t-ng-ph-n-t---hadamard--kh-c)
    + [7.3.8. Norm](#738-norm)
- [Chương 8: Visualization trong python](#ch--ng-8--visualization-trong-python)
  * [8.1 Biểu đồ line](#81-bi-u----line)
  * [8.2 Biểu đồ barchart](#82-bi-u----barchart)
  * [8.3. Biểu đồ tròn](#83-bi-u----tr-n)
  * [8.4 Biểu đồ boxplot](#84-bi-u----boxplot)
  * [8.6 Các biểu đồ biểu diễn phân phối.](#86-c-c-bi-u----bi-u-di-n-ph-n-ph-i)
    + [8.6.1 Density plot](#861-density-plot)
    + [8.6.2 Histogram plot](#862-histogram-plot)
    + [8.2.6 Swarn plot](#826-swarn-plot)
- [Chương 9: SciPy](#ch--ng-9--scipy)
  * [9.2 Các hàm cơ bản](#92-c-c-h-m-c--b-n)
  * [9.3 Tổng quan về các gói con của Scipy](#93-t-ng-quan-v--c-c-g-i-con-c-a-scipy)
  * [9.4 Tính tích phân](#94-t-nh-t-ch-ph-n)
  * [9.5 Giải phương trình vi phân](#95-gi-i-ph--ng-tr-nh-vi-ph-n)
  * [9.6 Tìm nghiệm phương trình](#96-t-m-nghi-m-ph--ng-tr-nh)
    + [9.6.1 Giải phương trình bằng phương pháp chia đôi - BISECTION](#961-gi-i-ph--ng-tr-nh-b-ng-ph--ng-ph-p-chia---i---bisection)
    + [9.6.2 Tìm nghiệm bằng hàm fsolve](#962-t-m-nghi-m-b-ng-h-m-fsolve)
  * [9.7 Nội suy](#97-n-i-suy)
