# Đề Quản Lý Giáo Viên

- Tạo lần lượt các lớp
  - Giáo Viên
  - Giáo Viên Thịnh Giảng
  - Giáo Viên Hợp Đồng
  - Quản lý giáo viên

## Lớp Giáo Viên

    -Thuộc tính
        + mã giáo viên tăng tự động
        + họ giáo viên
        + tên giáo viên
        + địa chỉ
        + giới tính
        + lương cơ bản là hằng số bằng 1490000
    - Phương thức
        + Nhập thông tin(phải kiểm tra tính hợp lệ của dữ liệu)
        + xuất thông tin

## Lớp giáo viên thịnh giảng (kế thừa lớp giáo viên)

lương thưởng = 10% lương cơ bản \* số giờ làm việc
tính lương nếu số giờ làm việc lớn hơn 20 giờ một tuần lương = lương thưởng + (lương cơ bản \* số giờ làm việc)

    - Thuộc tính
        + số giờ làm việc
    - Phương thức
        + Nhập thông tin
        + xuất thông tin
        + Tính lương

## Lớp giáo viên hợp đồng (Thừ kế từ lớp giáo viên)

tính lương nếu chức vụ bằng trưởng khoa thì lương cơ bản nhân 10 + với 3% lương thực nhận
nếu chức vụ bằng phó khoa thì lương cơ bản nhân 10 + với 2% số lương thực nhận
nếu chức vụ bằng giáo viên thì lương cơ bản nhan 10

    - Thuộc tính
        + chức vụ
    - Phương thức
        + Nhập thông tin
        + xuất thông tin
        + Tính lương

## Lớp quản lý giáo viên

    -Thuộc tính
    -Phương thức
        + thêm giáo viên
        + xóa giáo viên theo mã giáo viên
        + sửa giáo viên theo mã giáo viên
        + Tìm kiếm giáo viên theo tên
        + tìm kiếm giáo viên theo mã giáo viên
        + sắp xếp giáo viên theo lương giảm dần
