# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ CHẠY AFFILIATE)

- **Họ tên:** Nguyễn Vũ Long
- **Lớp:** HN-KS26-CNTT3
- **Link repository Pha2:** [GitHub](https://github.com/vulong1712/HN-KS26-CNTT3-Nguyen_Vu_Long-BOT)
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** Gemini

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký gói Affiliate ra JSON

**KET QUA AI**

```text
[
{
"ma_goi": "TT",
"ngay_bat_dau": "2026-12-20",
"creator_chinh": 2,
"thuc_tap_sinh": 1,
"hang_tai_khoan": "thuong",
"ghi_chu": null
},
{
"ma_goi": "SP",
"ngay_bat_dau": "2027-01-08",
"creator_chinh": 3,
"thuc_tap_sinh": 0,
"hang_tai_khoan": "thuong",
"ghi_chu": "một bạn đang bó bột chân cần ngồi bàn gần cửa ra vào"
},
{
"ma_goi": "PRO",
"ngay_bat_dau": null,
"creator_chinh": 4,
"thuc_tap_sinh": 0,
"hang_tai_khoan": "vip",
"ghi_chu": "mượn thêm đèn trợ sáng và phông xanh để quay mẫu"
}
]
```

**Link trò chuyện:** <https://share.gemini.google/2Bhh2j4ZMqyp>

## 4.3. Báo giá gói Affiliate bằng Chain-of-Thought

**KET QUA AI**

```text
<bang_gia_ve>
BẢNG GIÁ GÓI AFFILIATE (đồng/Creator chính)
TT – Gói TikTok Affiliate: 1.500.000
SP – Gói Shopee Affiliate: 1.000.000
PRO – Gói Livestream Pro: 3.000.000
</bang_gia_ve>

<quy_tac_tinh_gia>
QUY TẮC TÍNH GIÁ

1. Thực tập sinh (từ 15 đến dưới 18 tuổi) tính 60% giá Creator chính. Trẻ nhỏ dưới 15 tuổi đi cùng người nhà (chỉ ngồi khu chờ, không dùng máy) được miễn phí.
2. Team từ 4 Creator chính trở lên được giảm 10% trên tổng tiền gói (tiền Creator chính + tiền thực tập sinh).
3. Phụ thu thuê bộ mic thu âm không dây: 250.000 đồng/bộ. Phụ thu không được giảm giá.
4. Tổng tiền = tiền gói sau giảm + phụ thu.
</quy_tac_tinh_gia>

<yeu_cau_bao_gia>
YÊU CẦU BÁO GIÁ
Một team KOC đăng ký chạy chiến dịch cuối năm, chọn gói TT (Gói TikTok Affiliate), gồm 4 Creator chính, 2 thực tập sinh (16 tuổi và 17 tuổi) và 1 bé 7 tuổi (em nhỏ đi cùng ngồi khu chờ). Team thuê thêm 2 bộ mic thu âm không dây.
</yeu_cau_bao_gia>

1. **Tiền Creator chính:**
Team chọn gói TT (1.500.000 đồng/người) cho 4 Creator chính:

$$4 \times 1.500.000 = 6.000.000 \text{ đồng}$$


2. **Tiền thực tập sinh:**
Team có 2 thực tập sinh (16 tuổi và 17 tuổi, thuộc độ tuổi từ 15 đến dưới 18 tuổi) được tính 60% giá Creator chính. Bé 7 tuổi (dưới 15 tuổi, ngồi khu chờ) được miễn phí (0 đồng):

$$2 \times (1.500.000 \times 60\%) + 0 = 2 \times 900.000 = 1.800.000 \text{ đồng}$$


3. **Tổng tiền gói:**

$$\text{Tổng tiền gói} = 6.000.000 + 1.800.000 = 7.800.000 \text{ đồng}$$


4. **Giảm giá team:**
Vì team có đủ 4 Creator chính nên được giảm 10% trên tổng tiền gói:
* Số tiền được giảm: $7.800.000 \times 10\% = 780.000 \text{ đồng}$
* Tiền gói sau giảm: $7.800.000 - 780.000 = 7.020.000 \text{ đồng}$


5. **Phụ thu thuê mic:**
Team thuê 2 bộ mic thu âm không dây (250.000 đồng/bộ, không áp dụng giảm giá):

$$2 \times 250.000 = 500.000 \text{ đồng}$$


6. **Tổng tiền:**

$$\text{Tổng tiền} = 7.020.000 + 500.000 = 7.520.000 \text{ đồng}$$



[RESULT: 7.520.000 đồng]
```

**Link trò chuyện:** <https://share.gemini.google/97Mge3rBPGcc>

### b) Kiểm tra kết quả AI

Kết luận: AI tính ĐÚNG hoàn toàn các bước và kết quả cuối cùng [RESULT: 7.520.000 đồng]

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
"loai_su_co": "sai_phong",
"so_khach": 3,
"so_hiep_bi_anh_huong": 2,
"tom_tat": "Team 3 khách bị xếp phòng thường thiếu đèn livestream và ồn trong 2 ca đầu."
}
```

**Link trò chuyện:** <https://share.gemini.google/7zOu3mNThm4a>

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí | Điểm | Minh chứng | Đề xuất sửa |
| --- | --- | --- | --- |
| **Đúng thông tin (50%)** | 2.5 / 5.0 | **Câu bị lỗi:** *"Gói TikTok Affiliate bên mình giá chỉ 1.200.000đ/người thôi"*<br>

<br>**Lý do sai:** Báo sai mức giá niêm yết của gói TikTok Affiliate (giá chuẩn là 1.500.000đ/người; đồng thời cần rà soát lại điều kiện hoàn 100% tiền khi báo hủy trước 5 ngày theo đúng quy định hiện hành của trung tâm). | *"Hiện tại, gói thực chiến TikTok Affiliate bên mình có mức học phí chuẩn là 1.500.000đ/người (đã bao gồm đầy đủ quyền lợi theo chính sách của trung tâm) và áp dụng chính sách hoàn hủy theo đúng quy định khi bạn thông báo trước thời hạn cam kết."* |
| **Đầy đủ (30%)** | 1.5 / 3.0 | **Câu bị lỗi:** *"cứ chốt lẹ kẻo hết slot nè!"* (bỏ sót phần khai thác thông tin đăng ký)<br>

<br>**Lý do sai:** Đã trả lời 2 câu hỏi về giá và hoàn tiền nhưng thiếu hoàn toàn phần mời khách hàng cung cấp **ngày đợt thực chiến** và **số lượng suất muốn đăng ký**. | *"Để bên mình kiểm tra chính xác tình trạng chỗ trống và hỗ trợ giữ suất, bạn vui lòng cho mình biết thời gian (ngày) đợt thực chiến bạn dự định tham gia cùng số lượng suất muốn đăng ký nhé."* |
| **Giọng điệu (20%)** | 0.0 / 2.0 | **Lỗi 1 – Câu bị lỗi:** *"Dạ hello bạn nha!"* và *"cứ chốt lẹ kẻo hết slot nè!"*<br>

<br>**Lý do sai:** Sử dụng văn phong suồng sã, thiếu tính chuyên nghiệp và mang tính thúc ép khách hàng.<br>

<br>

<br>**Lỗi 2 – Câu bị lỗi:** *"đăng ký xong gắn link là nổ đơn hoa hồng trăm triệu luôn ạ."*<br>

<br>**Lý do sai:** Cam kết doanh thu và mức hoa hồng ảo, phi thực tế, vi phạm nghiêm trọng chuẩn mực tư vấn. | **Sửa lỗi 1:** *"Chào bạn, cảm ơn bạn đã quan tâm đến khóa học của trung tâm."* và *"Bạn cân nhắc thông tin và phản hồi sớm để bên mình hỗ trợ giữ suất phù hợp cho bạn nhé."*<br>

<br>

<br>**Sửa lỗi 2:** *"Sau khi hoàn thành khóa học, bạn sẽ nắm vững quy trình triển khai và tối ưu kênh để gia tăng cơ hội tạo ra doanh thu thực tế."* |
| **Tổng điểm** | **4.0 / 10** | Bài trả lời sai thông tin giá gói, thiếu bước khai thác nhu cầu (ngày thực chiến, số lượng suất), dùng từ ngữ suồng sã và cam kết hoa hồng ảo. | **Phiên bản hoàn chỉnh đề xuất:** *"Chào bạn, cảm ơn bạn đã quan tâm đến chương trình bên mình. Hiện tại, gói TikTok Affiliate có mức phí là 1.500.000đ/người; sau khi đăng ký, bạn sẽ được hướng dẫn lộ trình bài bản để triển khai gắn link và tối ưu chuyển đổi. Về chính sách hủy, trung tâm hỗ trợ hoàn phí theo đúng quy định khi bạn báo trước thời hạn cam kết. Để bên mình hỗ trợ tư vấn chi tiết hơn, bạn vui lòng chia sẻ thêm ngày đợt thực chiến dự kiến và số lượng suất muốn đăng ký nhé!"* |
```

**Link trò chuyện:** <https://share.gemini.google/K8KWO5pK5o1B>
