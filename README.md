# 📊 Báo Cáo Tổng Kết & Phát Hiện Gian Lận Trong Chương Trình Khuyến Mãi

## 📝 Giới thiệu
Dự án này phân tích **chương trình khuyến mãi 30%** của Shopee diễn ra từ **30/10/2019 - 02/11/2019**, nhằm:
- Tổng kết kết quả đạt được từ chương trình.
- Phát hiện các hành vi **gian lận tiềm ẩn** từ phía **người bán** và **người mua**.
- Đưa ra gợi ý để **tối ưu hóa các chiến dịch khuyến mãi trong tương lai**.

Người thực hiện: **Trần Hoài Nam**

---

## 📌 Nội dung chính
1. Đặt vấn đề  
2. Kết quả đạt được của chương trình khuyến mãi  
3. Phát hiện các nguy cơ gian lận  
   - Gian lận từ phía **người bán**  
   - Gian lận từ phía **người mua**

---

## 🚀 Kết quả nổi bật
- Tổng doanh thu: **640.9 triệu VND**  
- Tổng số đơn hàng: **4,611** từ **3,093 người mua**  
- Tổng tiền khuyến mãi cấp: **78 triệu VND**  
- Ngày 02/11/2019 đạt **222 triệu VND doanh thu**, cao gấp 1.6 lần ngày đầu tiên.  
- Phát hiện nhiều **mô hình gian lận**:
  - Người bán tạo **đơn hàng ảo** để tăng doanh số.  
  - Người mua sử dụng **nhiều tài khoản** nhằm tận dụng khuyến mãi.  
  - Một số tài khoản có hành vi **mua bán chéo** để khai thác tiền thưởng.  

---

## 📈 Phát hiện gian lận
### Người bán
- Tạo **nhiều đơn hàng giả** với giá trị rất thấp (1.000 – 100 VND).  
- Sử dụng **nhiều shop liên kết** và **khách hàng giả mạo**.  
- Gian lận tổng cộng **~440.000 VND tiền khuyến mãi**.

### Người mua
- Một số ID mua hàng có tần suất bất thường: **10 đơn/giờ** từ cùng 10 shop.  
- Tổng chi tiêu gần **900.000 VND**, nhận lại **200.000 VND khuyến mãi**.  
- Có dấu hiệu **cùng một cá nhân điều khiển nhiều tài khoản**.  

---

## 🔍 Đề xuất
- Kiểm tra **IP, địa chỉ giao hàng, phương thức thanh toán** để phát hiện trùng lặp.  
- Phân tích **lịch sử giao dịch** để nhận diện hành vi bất thường.  
- Điều chỉnh chương trình khuyến mãi:
  - Giới hạn số lần áp dụng voucher.  
  - Áp dụng mức khuyến mãi linh hoạt theo giá trị đơn hàng.  
  - Kiểm soát tốt hơn các đơn hàng giá trị thấp.  

---

## 📂 Cấu trúc repo

