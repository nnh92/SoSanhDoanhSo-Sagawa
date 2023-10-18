# SoSanhDoanhSo-Sagawa
So sánh doanh số bán hàng với số tiền sagawa nhận được. Mục đích biết được ai đã trả tiền
-------------------------------------

- ①. So sánh dữ liệu: giá trị cột H của biểu doanh số (thực tế cột này k tồn tại) với giá trị ở cột J của biểu Sagawa
- ②. Sẽ có trường hợp nhiều giá trị tiền bị trùng nhau, thì tạo riêng 1 sheet trả về các kết quả bị trùng (bao gồm các thông tin: cột C, D, E, F của biểu doanh số)
- ③. Bước cuối cùng: Sau khi hoàn thành so sánh, so sánh giá trị tổng tiền ở biểu Sagawa và tổng giá trị ở biểu doanh số)

Chú ý: 	
	+ Biểu Sagawa là biểu tổng hợp số tiền (data) theo 1 tuần, không phải data của 1 tháng
	+ Cột G (biểu thị ngày tháng tiền vào), không có giá trị tham khảo k nhìn vào cột này
	+ Biểu doanh số là biểu theo dõi doanh số của 1 tháng nên lượng data sẽ nhiều hơn, và có những data k cần so sánh (do không sử dụng dịch vụ COD của Sagawa)
	+ Giá trị cột H là tổng của cột E + F, 
	+ Chỉ so sánh khi cột E hoặc F có giá trị (nếu trống thì không tính giá trị cột H và không so sánh)
	+ Trên biểu Sagawa, cột N và O thực tế k tồn tại, giá trị ở 2 cột này chỉ dùng với mục đích hướng dẫn cách tính giá trị cột O
	+ Giá trị của cột O sử dụng để tính tổng tiền sẽ nhận được từ Sagawa ở bước cuối cùng
	+ Ở bước cuối cùng, công thức sẽ là tổng các giá trị trong cột O trừ đi (-) ¥481 (phí chuyển khoản)
![image](https://github.com/nnh92/SoSanhDoanhSo-Sagawa/assets/78486384/4a38b432-f094-4aff-9b8c-af8151c72269)
