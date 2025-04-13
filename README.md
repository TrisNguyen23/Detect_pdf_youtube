<h1>📝 Ghi chú và Tóm tắt Nội dung Tự động</h1>

<p>Ứng dụng Python với giao diện Tkinter giúp bạn:</p>
<ul>
  <li>Trích xuất nội dung văn bản từ URL.</li>
  <li>Tóm tắt nội dung bằng thuật toán LSA (Sumy).</li>
  <li>Ghi chú và lưu kết quả vào tệp Word (.docx).</li>
</ul>

<h2>🚀 Cài đặt</h2>
<ol>
  <li><strong>Sao chép kho lưu trữ:</strong>
    <pre><code>git clone https://github.com/TrisNguyen23/Detect_pdf_youtube.git
cd Detect_pdf_youtube</code></pre>
  </li>
  <li><strong>Tạo môi trường ảo (tùy chọn):</strong>
    <pre><code>python -m venv env
source env/bin/activate  # Trên Windows: env\Scripts\activate</code></pre>
  </li>
  <li><strong>Cài đặt các thư viện phụ thuộc:</strong>
    <pre><code>pip install -r requirements.txt</code></pre>
    <p><em>Nếu chưa có tệp <code>requirements.txt</code>, bạn có thể cài đặt trực tiếp:</em></p>
    <pre><code>pip install requests beautifulsoup4 python-docx sumy</code></pre>
  </li>
</ol>

<h2>💻 Sử dụng</h2>
<ol>
  <li><strong>Chạy ứng dụng:</strong>
    <pre><code>python app.py</code></pre>
  </li>
  <li><strong>Thao tác trên giao diện:</strong>
    <ul>
      <li>Nhập URL của trang web cần trích xuất nội dung.</li>
      <li>Nhấn nút <strong>"Lấy nội dung"</strong> để trích xuất văn bản.</li>
      <li>Nhấn nút <strong>"Tóm tắt nội dung"</strong> để tạo bản tóm tắt.</li>
      <li>Nhấn nút <strong>"Lưu ghi chú"</strong> để lưu kết quả vào tệp Word.</li>
    </ul>
  </li>
</ol>

<h2>📄 Giấy phép</h2>
<p>Dự án này được cấp phép theo <a href="LICENSE">MIT License</a>.</p>

<p><em>Cảm ơn bạn đã sử dụng ứng dụng!</em></p>
