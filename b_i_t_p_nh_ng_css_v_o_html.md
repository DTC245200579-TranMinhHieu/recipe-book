<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bài Tập: Các Cách Nhúng CSS Vào Trang HTML</title>
    
    <!-- PHẦN 3: EXTERNAL STYLE (Liên kết tới file style.css riêng biệt) -->
    <link rel="stylesheet" href="style.css">

    <!-- PHẦN 2: INTERNAL STYLE (Nội bộ) -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }

        /* Định dạng cho phần 2 */
        .internal-section h1 {
            color: #d97706; /* Màu cam */
        }
        .internal-section p {
            color: #1e40af; /* Màu xanh dương */
            font-size: 16px;
        }

        .box {
            border: 1px solid #ccc;
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h2>BÀI TẬP: NHÚNG CSS VÀO TRANG HTML</h2>
    <hr>

    <!-- PHẦN 1: INLINE STYLE (Nội dòng) -->
    <div class="box">
        <h3>1. Phần 1: Inline Style (Nội dòng)</h3>
        <h1 style="color: #16a34a;">Tiêu đề bài viết - Inline Style (Màu xanh lá)</h1>
        <p style="color: #9333ea; font-size: 16px;">
            Đoạn văn bản được thay đổi màu sắc trực tiếp bằng thuộc tính style trong thẻ p (Màu tím).
        </p>
    </div>

    <!-- PHẦN 2: INTERNAL STYLE (Nội bộ) -->
    <div class="box internal-section">
        <h3>2. Phần 2: Internal Style (Nội bộ)</h3>
        <h1>Tiêu đề bài viết - Internal Style (Màu cam)</h1>
        <p>
            Đoạn văn bản được thay đổi màu sắc bằng bộ chọn trong thẻ &lt;style&gt; ở head (Màu xanh dương).
        </p>
    </div>

    <!-- PHẦN 3: EXTERNAL STYLE (File CSS riêng) -->
    <div class="box external-section">
        <h3>3. Phần 3: External Style (File ngoài)</h3>
        <h1>Tiêu đề bài viết - External Style (Màu đỏ)</h1>
        <p>
            Đoạn văn bản được thay đổi màu sắc và định dạng từ file <code>style.css</code> riêng biệt (Màu xanh ngọc).
        </p>
    </div>

</body>
</html>