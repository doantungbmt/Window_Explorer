Tên: Nguyễn Doãn Tùng
- Đề số 8
- Câu 1:  FileExplore
- Câu 2: CHức năng xóa File.
- video hương dẫn: https://www.youtube.com/watch?v=kBdEzaOAPcg&feature=youtu.be

Hướng dẫn chạy code:
- Tải project GiuaKy về máy
- mở cmd
- Dùng lệnh cd chuyển đến thư mục chứa source code:
ví dụ: cd D:\JAVA\java_done\GiuaKy
- Biên dịch lệnh javac:
  . javac KTGiuaKy\FileMngt.java
- chạy bằng lệnh java:
  . java KTGiuaKy.FileMngt


hướng dẫn sử dụng: 
chức năng delete:
- cho cac dòng lệnh vào eclipse để chạy.
- chọn file cần xóa trên table
- nhấp chuột vào nút delete
- nhấn "Ok" để xóa

Các hàm chức năng:
_ public Container getGui(): chứa những thành phần của cửa sổ, gọi các hàm đã viết thêm vào cửa 
sổ.
- public void showRootFile(): hiển thị các tệp lên jtree và jtable từ lớp FileTableModel.
- private void deleteFile(): thực hiện chức năng Xóa một tệp tin.
- private void showChildren(final DefaultMutableTreeNode node): thêm các cành jtree.
- private void setFileDetails(File file): làm mới jtree và jtable sau khi thực hiện xóa.
**Lớp "class FileTableModel extends AbstractTableModel" thực hiện chứ năng hiển thị lên jtable.

