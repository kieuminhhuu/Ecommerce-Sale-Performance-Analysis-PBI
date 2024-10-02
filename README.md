# Ecommerce Sales Performance Analysis[PBI]
# Introduction
- Đặt vấn đề:
  - Superstore là một công ty bán lẻ  có cửa hàng trên toàn thế giới. Senior Manager muốn nắm được thông tin về tình hình kinh doanh của công ty để đưa ra chiến lược mở rộng thị trường và quyết định lựa chọn sản phẩm chiến lược. Sử dụng PowerBI để trực quan hóa tình hình kinh doanh của Superstore, đưa ra Insight và Recommendation cho doanh nghiệp
- Dataset: bao gồm 3 bảng là Orders, People, Returns. Trong đó:
  - Orders: lưu thông tin thời gian, sản phẩm, khách hàng của tất cả đơn hàng từ 01/01/2011 → 31/12/2014 của Superstore
  - People: lưu thông tin người bán hàng của từng khu vực
  - Returns: lưu thông tin các đơn hàng bị trả lại
# Analysis & Visualization
<img src="https://github.com/user-attachments/assets/6033f2e3-f7eb-4f55-9729-b0c21ef7ba8b" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/efbfcff7-b483-4d01-aae4-1cd68060ee80" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/851745fe-7fd2-4b90-bea4-c23a946395bc" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/bb4bede3-f6cc-4d4e-b364-d4bd3e02e6f2" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/82a6a88b-1aa8-459f-b1c7-317c1fc85ae1" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/48a8e15f-f1a4-4f84-8e23-680576b3414b" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/8b5aa87d-a8ec-48a9-bec4-8d3a8c234a37" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/98aa4fe2-64b4-4375-91a4-5bc0fc34ad22" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/717966b5-a255-497c-b0bf-3145ee01147b" alt="..." width="500" /><br />
<img src="https://github.com/user-attachments/assets/a7244a5c-29b7-4e36-acab-4025efde2b0d" alt="..." width="500" /><br />
# Key Insights
- Tổng doanh thu là 12,64m với lợi nhuận là 1,47m, tỷ suất lợi nhuận là khoảng 11%
- Tỷ lệ đơn hàng hoàn trung bình là khoảng 4,68% và trả giảm dần qua các năm
- Khu vực có doanh thu cao nhất là Central 2.8 triệu đô
- Khu vực có lợi nhuận cao nhất là Central 300 nghìn đô
- Loại sản phẩm bán chạy nhất là Office Supplies chiếm 60% số lượng sản phẩm bán ra
- Tổng số đơn hàng đã có được là khoảng 25000 đơn và đã bán khoảng 178000 sản phẩm, trung bình doanh thu của một đơn hàng là khoảng 505 đô đem lại lợi nhuẩn khoảng 59 đô
- Tổng quan thì doanh thu hàng năm vẫn tăng nhưng mà tăng rất ít điều này là do:
    - Thứ 1: Phần lớn các sản phẩm bán ra 60% là thuộc nhóm Offier Supplies, 20% là Tech và 20% là Funiture, nhưng về doanh thu thì các sản phẩm Tech và Office có tỷ lệ bằng nhau là 38% điều này có thể giải thích vì đồ công nghệ thường có giá trị cao hơn nhiều so với đồ văn phòng, trung bình các đơn hàng thuộc nhóm offices chỉ khoảng 200$, còn Funiture hay Technology là khoảng 500$ -> tức là phần lớn sản phẩm bán ra là những sản phẩm có giá trị nhỏ
    - Thứ 2: Qua các năm số lượng sản phẩm bán ra đều tăng nhưng phần lớn là các sản phẩm thuộc nhóm Office Supplies còn sản phẩm thuộc nhóm Technology hoặc Furniture tăng rất ít
    - Thứ 3: Tỷ lệ lợi nhuận từ các nhóm sản phẩm cũng không cao: 2 nhóm Office và Tech là khoảng 14% còn Furniture thì khoảng 6%
- Khu vực có tỷ lệ trả hàng cao nhất là North Asia với gần 14%
- Các tháng đầu năm có xu hướng giảm số lượng đơn hàng
# Recommendations
- Tập chung hơn vào việc bán các sản phẩm về Technology hoặc Furniture
- Đối với top 5 khu vực đem lại doanh thu cao nhất là Central, South, North, Oceania, Southeast Asia thì cần:
    - Luôn đảm bảo các sản phẩm bán chạy còn trong kho
    - Bán thêm các sản phẩm nâng cấp hoặc các sản phẩm trong nhóm hàng Technology hoặc Furniture
    - Riêng khu vực North cần tìm hiểu nguyên ngân khách hàng hủy đơn để giảm tỷ lệ hủy hiện tại là 10%
- Khu vực North Asia cũng cần tìm hiểu nguyên nhân để giảm tỷ lệ hủy đơn hàng
- Tăng giá trị đơn hàng của mặt hàng Office Supplies bằng cross-sell, upsell

