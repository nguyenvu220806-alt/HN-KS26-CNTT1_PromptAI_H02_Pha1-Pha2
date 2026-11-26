# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 09
- **Họ tên:** Nguyễn Hồng Vũ 
- **Lớp:** CNTT1
- **Link repository Pha2:** https://github.com/nguyenvu220806-alt/HN-KS26-CNTT1_PromptAI_H02_Pha1-Pha2
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt chỗ workshop ra JSON

**KET QUA AI**

```text
[
  {
    "ma_lop": "NANTAY",
    "ngay_hoc": "2026-12-13",
    "nguoi_lon": 2,
    "tre_em": 1,
    "ca_hoc": "chieu",
    "ghi_chu": null
  },
  {
    "ma_lop": "BANXOAY",
    "ngay_hoc": "2027-01-10",
    "nguoi_lon": 3,
    "tre_em": 0,
    "ca_hoc": null,
    "ghi_chu": "1 người bị đau cổ tay"
  },
  {
    "ma_lop": "VEGOM",
    "ngay_hoc": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "ca_hoc": null,
    "ghi_chu": "1 bạn đi xe lăn"
  }
]
```

**Link trò chuyện:** https://chatgpt.com/share/6b07e513-cae0-83ec-a4fd-06f6ce836169

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
1. Tiền người lớn
- 5 người lớn, mỗi người 550.000 đồng.
- Phép tính: 5 × 550.000 = 2.750.000 đồng.
2. Tiền trẻ em
- 2 trẻ em (8 tuổi và 12 tuổi) tính 70% giá người lớn.
- Giá mỗi trẻ: 550.000 × 70% = 385.000 đồng.
- Phép tính: 2 × 385.000 = 770.000 đồng.
- Bé 4 tuổi đi kèm, không làm sản phẩm: Miễn phí (0 đồng).
3. Tiền học (người lớn + trẻ em)

- 2.750.000 + 770.000 = 3.520.000 đồng.

4. Giảm giá nhóm
- Nhóm có 5 người lớn nên được giảm 5%.
- Tiền giảm: 3.520.000 × 5% = 176.000 đồng.
- Tiền học sau giảm: 3.520.000 − 176.000 = 3.344.000 đồng.
5. Phí nung và giao

- 4 sản phẩm × 80.000 = 320.000 đồng.

6. Tổng tiền

- 3.344.000 + 320.000 = 3.664.000 đồng.

[RESULT: 3.664.000 đồng]
```

**Link trò chuyện:** https://chatgpt.com/share/6b07e540-3300-83ec-9b89-129194d58215

### b) Kiểm tra kết quả AI

Đúng 

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{\
&#x20; "loai_su_co": "hong_san_pham",\
&#x20; "so_khach": 3,\
&#x20; "so_san_pham_bi_hong": 5,\
&#x20; "tom_tat": "Gia đình 3 người nhận hàng có 5 sản phẩm gốm bị nứt vỡ, yêu cầu xưởng giải quyết."\
}
```

**Link trò chuyện:** https://chatgpt.com/share/6b07e6c5-3644-83ec-b013-403b2b439ace

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Điểm: 3/10

Nhận xét:
- Đúng thông tin (0/5 điểm): Báo sai giá (200.000đ thay vì 250.000đ). Sai chính sách đổi lịch: đổi trước 1 ngày mất phí 30.000đ/người, không miễn phí.
- Đầy đủ (1,5/3 điểm): Đã trả lời cả hai câu hỏi nhưng chưa mời khách cung cấp ngày học, ca học và số người để đặt chỗ.
- Giọng điệu (1,5/2 điểm): Thân thiện nhưng sử dụng từ ngữ suồng sã như “Hi chị ơi”, “free nha”, “vui lắm luôn”.
Câu trả lời đề xuất:

"Chào chị! Lớp vẽ gốm có giá 250.000 đồng/người lớn. Nếu chị muốn đổi lịch trước 1 ngày, phí đổi là 30.000 đồng/người. Chị vui lòng cung cấp ngày học, ca học và số lượng người tham gia để bên em hỗ trợ đặt chỗ nhé. Em cảm ơn chị!"
```

**Link trò chuyện:** https://chatgpt.com/share/6b07e710-39b0-83ec-a634-482bb5ab3749
