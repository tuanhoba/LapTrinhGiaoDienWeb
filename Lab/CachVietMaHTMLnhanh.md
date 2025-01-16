# Cách Viết Tắt Nhanh Trong HTML

Viết mã HTML nhanh chóng và hiệu quả có thể thực hiện thông qua việc sử dụng các phím tắt và tính năng hỗ trợ của các trình soạn thảo mã hiện đại như VS Code, Sublime Text, hoặc Atom. Dưới đây là hướng dẫn các cách viết tắt thường gặp:

## 1. Sử dụng Emmet trong VS Code
Emmet là một plugin hỗ trợ viết mã nhanh bằng cách sử dụng các cú pháp rút gọn. Mặc định, VS Code đã tích hợp sẵn Emmet.

### Một số cú pháp phổ biến:

- **Tạo thẻ đơn lẻ:**
  ```
  div -> <div></div>
  p -> <p></p>
  ```

- **Tạo cấu trúc lồng nhau:**
  ```
  div>ul>li ->
  <div>
      <ul>
          <li></li>
      </ul>
  </div>
  ```

- **Tạo nhiều thẻ con:**
  ```
  ul>li*3 ->
  <ul>
      <li></li>
      <li></li>
      <li></li>
  </ul>
  ```

- **Thêm thuộc tính nhanh:**
  ```
  a[href="#"] -> <a href="#"></a>
  input[type="text"] -> <input type="text">
  ```

- **Thêm class hoặc id:**
  ```
  div.classname -> <div class="classname"></div>
  div#idname -> <div id="idname"></div>
  ```

- **Kết hợp nhiều tính năng:**
  ```
  div.container>header>h1.title+p.subtitle ->
  <div class="container">
      <header>
          <h1 class="title"></h1>
          <p class="subtitle"></p>
      </header>
  </div>
  ```

## 2. Tính năng "Wrap with Abbreviation"
Bạn có thể sử dụng tính năng này để nhanh chóng bao bọc một đoạn mã HTML trong các thẻ mong muốn.

- Ví dụ: Chọn đoạn văn bản và nhấn **Ctrl + Shift + P** (Windows) hoặc **Cmd + Shift + P** (Mac), gõ "Emmet: Wrap with Abbreviation".

## 3. Gợi ý nhanh trong VS Code
Trong khi gõ mã, bạn có thể sử dụng **Ctrl + Space** (Windows) hoặc **Cmd + Space** (Mac) để hiện danh sách gợi ý thẻ HTML và thuộc tính.

## 4. Sử dụng Snippet Tùy Chỉnh
VS Code hỗ trợ tạo snippet riêng để tiết kiệm thời gian viết mã.

### Cách thêm snippet:
1. Mở Command Palette (**Ctrl + Shift + P**) và chọn **Preferences: Configure User Snippets**.
2. Chọn ngôn ngữ "html.json".
3. Thêm đoạn mã snippet:

```json
{
  "Tạo một thẻ section": {
    "prefix": "section",
    "body": [
      "<section>",
      "    <h1>${1:Tiêu đề}</h1>",
      "    <p>${2:Nội dung}</p>",
      "</section>"
    ],
    "description": "Snippet tạo thẻ section."
  }
}
```

4. Lưu lại và sử dụng từ khoá "section" trong file HTML để chèn.

## 5. Phím tắt cơ bản khác trong VS Code
- **Tạo file mới:** Ctrl + N (Windows) hoặc Cmd + N (Mac).
- **Lưu file:** Ctrl + S (Windows) hoặc Cmd + S (Mac).
- **Tự động định dạng mã:** Shift + Alt + F (Windows) hoặc Shift + Option + F (Mac).
- **Chuyển đổi giữa các file đang mở:** Ctrl + Tab.

## 6. Gợi ý nhanh khi viết thuộc tính CSS trong HTML
Khi làm việc với các thẻ HTML có thuộc tính style inline, bạn chỉ cần gõ bắt đầu thuộc tính CSS, ví dụ:

```html
<div style="ba"></div>
```

Trình soạn thảo sẽ gợi ý `background-color`, `background`, v.v.

---
Việc sử dụng các phương pháp trên sẽ giúp bạn tăng tốc quá trình viết mã HTML một cách đáng kể.
