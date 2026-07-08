# 📄 DOCX to LaTeX Converter (Claymation Web Edition)

[![Firebase Hosting](https://img.shields.io/badge/Hosting-Firebase-orange?style=for-the-badge&logo=firebase)](https://doc-latex.web.app)
[![WebAssembly](https://img.shields.io/badge/Powered%20by-WebAssembly-blueviolet?style=for-the-badge&logo=webassembly)](https://webassembly.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

Công cụ chuyển đổi tài liệu Microsoft Word (`.docx`) sang định dạng LaTeX (`.tex`) chuyên nghiệp, chạy trực tiếp trên trình duyệt của bạn bằng công nghệ WebAssembly (WASM).

---

## ⚡ TRUY CẬP ỨNG DỤNG NGAY

👉 **Sử dụng ứng dụng trực tuyến tại đây**: [https://doc-latex.web.app](https://doc-latex.web.app)

*(Không cần cài đặt, không cần đăng ký tài khoản, sử dụng miễn phí 100%!)*

---

## ✨ Các Tính Năng Nổi Bật

*   **⚡ Chuyển đổi siêu tốc bằng WebAssembly**: Sử dụng trực tiếp nhân xử lý của Pandoc chạy trực tiếp trên trình duyệt web, đảm bảo tốc độ tối đa và độ chính xác 100% đối với bảng biểu, tiêu đề và công thức toán phức tạp.
*   **🔒 Bảo mật tuyệt đối (100% Client-side)**: Tài liệu của bạn không bao giờ bị tải lên bất kỳ máy chủ nào. Toàn bộ quá trình xử lý diễn ra cục bộ ngay trên máy tính của bạn, đảm bảo an toàn thông tin cá nhân.
*   **🖼️ Trích xuất hình ảnh tự động (Media)**: Quét và giải nén toàn bộ hình ảnh chèn trong file Word, tự động đóng gói file kết quả `.tex` và thư mục ảnh `media/` vào một file nén `.zip` hoàn chỉnh.
*   **📄 Hỗ trợ tài liệu Độc lập (Standalone)**: Tùy chọn xuất ra file `.tex` độc lập (chứa đủ phần khai báo `\documentclass`, `\begin{document}`) để có thể biên dịch ra PDF được ngay, hoặc xuất dạng đoạn code nội dung (fragment) để chèn vào tài liệu sẵn có.
*   **🎨 Giao diện Đất Sét (Claymation) độc đáo**: Thiết kế wobbly nghệ thuật lấy cảm hứng từ phim hoạt hình đất sét nặn tĩnh (stop-motion) và không gian Gothic cổ kính, mang lại trải nghiệm thú vị khi làm việc.
*   **📱 Hỗ trợ đa nền tảng**: Hoạt động mượt mà trên tất cả các hệ điều hành (Windows, macOS, Linux) và thiết bị di động (iOS, Android).

---

## 🚀 Hướng Dẫn Sử Dụng Nhanh

1.  Truy cập vào trang web [https://doc-latex.web.app](https://doc-latex.web.app).
2.  **Kéo và thả** file Word (`.docx`) cần chuyển đổi vào khu vực trung tâm (hoặc nhấp chuột để chọn file từ máy tính).
3.  Lựa chọn các cấu hình chuyển đổi mong muốn:
    *   *Tài liệu độc lập (Standalone)*
    *   *Trích xuất hình ảnh (Media)*
4.  Nhấp vào nút **Bắt đầu chuyển đổi** màu tím.
5.  Chờ trong vài giây và nhấn nút **Tải file kết quả** để tải file `.tex` hoặc `.zip` về thư mục tải xuống của máy tính.

---

## 🛠️ Công Nghệ Sử Dụng

*   **Pandoc.wasm**: Công cụ chuyển đổi tài liệu đa năng được chạy dưới dạng WebAssembly System Interface (WASI).
*   **fflate**: Bộ mã hóa/giải nén ZIP siêu nhẹ chạy trực tiếp tại Client để đóng gói mã nguồn và ảnh.
*   **CSS Claymorphism**: Thiết kế hiệu ứng đất sét nặn 3D thủ công bằng SVG Filters.

---

*Designed by MinhHK. &copy; 2026. All rights reserved.*
