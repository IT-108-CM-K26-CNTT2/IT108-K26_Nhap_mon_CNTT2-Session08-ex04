# Prompt gia sư: Mô hình IPO trong trang trại thông minh

## A. Prompt hoàn chỉnh

````markdown
# Bối cảnh

Bạn là **gia sư thân thiện** dạy sinh viên năm 1, chưa có nền tảng lập trình.
Mình đang khó hiểu **"Mô hình IPO trong trang trại thông minh"**.

# Nội dung

Giải thích mô hình **IPO (Input – Process – Output)** bằng ví dụ hệ thống tưới cây tự động.

## Không cần

- Không cần code, sơ đồ mạch điện hay công thức
- Không cần nhắc đến AI, Cloud hay giao thức truyền thông

# Yêu cầu

- [ ] Ngôn ngữ đời thường, câu ngắn
- [ ] Mở đầu bằng 1 ví dụ quen thuộc (nồi cơm điện)
- [ ] Giải thích 3 thành phần, mỗi phần 1–2 câu
- [ ] Có 1 bảng IPO cho hệ thống tưới cây
- [ ] Kết thúc bằng 1 câu hỏi tự kiểm tra

## Kiểm soát độ khó

- [ ] Tối đa **250 từ**
- [ ] Viết bằng tiếng Việt; chỉ dùng tối đa **3 thuật ngữ tiếng Anh**, mỗi từ giải thích ngay trong ngoặc
````

**Edge Case:** mục `## Kiểm soát độ khó` giới hạn số từ và số thuật ngữ tiếng Anh, nên AI không thể trả lời dài hoặc toàn từ chuyên môn.

## B. Câu trả lời của AI

---

### 🌱 IPO là gì?

Hãy nghĩ đến **nồi cơm điện**: cho gạo và nước vào, nồi nấu, rồi ra cơm chín. Đó là IPO.

- **Input (Đầu vào):** thứ hệ thống nhận vào, như gạo và nước.
- **Process (Xử lý):** hệ thống quyết định, như nồi tính thời gian nấu.
- **Output (Đầu ra):** kết quả làm ra, như cơm chín.

### Ví dụ: tưới cây tự động

| Bước | Trong trang trại | Vai trò |
|:--|:--|:--|
| **Input** | Cảm biến độ ẩm đất | "Mắt": biết đất khô hay ướt |
| **Process** | Bộ điều khiển so với ngưỡng | "Não": đất khô thì cần tưới |
| **Output** | Máy bơm bật | "Tay chân": tưới nước |


