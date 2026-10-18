/* Reset căn bản */
body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f8fafc;
    color: #334155;
    margin: 0;
    padding: 30px;
}

/* Khung nội dung chính */
.container {
    max-width: 750px;
    margin: 0 auto;
    background-color: #ffffff;
    padding: 40px;
    border-radius: 8px;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
}

/* Định dạng tiêu đề chính - Căn giữa, viết hoa, kích thước lớn */
.main-title {
    text-align: center;
    color: #1e3a8a;
    font-size: 28px;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin-bottom: 5px;
}

/* Định dạng phụ đề/tác giả - Chữ nghiêng, căn phải, màu xám */
.sub-title {
    text-align: right;
    font-style: italic;
    color: #64748b;
    font-size: 15px;
    margin-top: 0;
    margin-bottom: 25px;
}

/* Đoạn trích dẫn / Lời mở đầu - Chữ nghiêng, căn giữa, khung nổi bật */
.quote-box {
    font-style: italic;
    text-align: center;
    font-size: 17px;
    color: #475569;
    background-color: #f1f5f9;
    padding: 15px 20px;
    border-left: 4px solid #3b82f6;
    margin-bottom: 25px;
}

/* Định dạng các đoạn văn bản chính */
.content-paragraph {
    text-align: justify;       /* Căn đều 2 bên */
    text-indent: 30px;          /* Thụt lùi dòng đầu tiên 30px */
    font-size: 16px;            /* Kích thước chữ */
    line-height: 1.8;           /* Khoảng cách giữa các dòng */
    color: #1e293b;             /* Màu chữ đậm vừa */
    margin-bottom: 15px;
}

/* Nhấn mạnh chữ trong đoạn văn */
.highlight {
    color: #d97706;
    font-weight: bold;
    text-decoration: underline;
}