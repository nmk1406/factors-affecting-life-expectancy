# Factors Affecting Life Expectancy

Trong project này tôi sử dụng phương pháp thống kê suy diễn để tìm ra các yếu tố ảnh hưởng đến tuổi thọ trung bình.
Ngoài ra tôi còn sử dụng thêm Machine Learning để dự đoán tuổi thọ trung bình.

## Thông tin dataset

[Life Expectancy WHO Dataset](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who) được thu thập bởi WHO và trang web của liên hợp quốc. Gồm 2938 dòng và 22 cột.

- Country: quốc gia
- Year: năm
- Status: trạng thái đã phát triển hay đang phát triển
- Life.expectancy: tuổi thọ trung bình
- Adult.Mortality: số ca tử vong ở người trưởng thành (từ 15-60 tuổi) trên 1000 người
- infant.deaths: số ca tử vong ở trẻ em trên 1000 người
- Alcohol: mức tiêu thụ rượu tính theo bình quân đầu người (lit)
- percentage.expenditure: chi tiêu cho y tế tính theo phần trăm tổng sản phẩm quốc nội bình quân đầu người
- Hepatitis.B: tỷ lệ tiêm chủng viêm gan B ở trẻ 1 tuổi (%)
- Measles: số cả sởi ghi nhận
- BMI: chỉ số khối cơ thể
- under.five.deaths: sô ca trẻ dưới 5 tuổi tử vong trên 1000 người
- Polio: tỷ lệ tiêm chủng viêm bại liệt ở trẻ 1 tuổi (%)
- Total.expenditure: chi tiêu chung của chính phủ cho y tế tính theo tỷ lệ phần trăm trong tổng chi tiêu của chính phủ
- Diphtheria: tỷ lệ tiêm chủng viêm bạch hầu, ho gà, uống ván ở trẻ 1 tuổi (%)
- HIV.AIDS: số ca tử vong ở trẻ em (từ 0-4 tuổi) do HIV/AIDS trên 1000 người
- GDP: tổng sản phẩm quốc nội ($)
- Population: dân số của quốc gia
- thinness..1.19.years: tỷ lệ gầy ốm của thanh niên (từ 10-19 tuổi)
- thinness.5.9.years: tỷ lệ gầy ốm của thanh niên (từ 5-9 tuổi)
- Income.composition.of.resources: chỉ số phát triển con người dựa trên thành phần thu nhập của các nguồn lực (từ 0-1)
- Schooling: số năm đi học
