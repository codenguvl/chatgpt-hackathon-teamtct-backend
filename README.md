# Cấu trúc trang web

Trang web này được xây dựng bằng ReactJS, NodeJS, ExpressJS và MongoDB. Nó bao gồm ba thư mục chính: `backend`, `frontend` và `database`. Dưới đây là mô tả chi tiết về các thư mục:

- Thư mục `backend` chứa các tệp `model`, `controller` và `routes` để quản lý dữ liệu và xử lý các yêu cầu từ phía client. Ứng dụng chạy trên cổng `localhost:8800`.
- Thư mục `frontend` chứa các thư mục `api`, `components`, `page`, `dataStatic` và `hooks`. Nó sử dụng thư viện `Styled Components` để tổ chức và quản lý CSS của hệ thống. Ứng dụng chạy trên cổng `localhost:3000`.
- Thư mục `database` chứa các bảng dữ liệu của ứng dụng bao gồm `majors`, `universities`, `universityentranceexamscores` và `users`.

## Chức năng của trang web

### Người dùng

Trang web này cung cấp các chức năng sau:

#### Hướng dẫn người dùng sử dụng website

Người dùng có thể click vào nút "Tìm hiểu ngay" để nhận được hướng dẫn sử dụng, chức năng của website.
![Hướng dẫn người dùng sử dụng website](images/add-edit-university.png)

#### Tính điểm

Người dùng có thể tính điểm bằng cách nhập điểm đầy đủ, sau đó hệ thống sẽ tính điểm và đưa ra gợi ý khối thi, ngành học phù hợp với điểm số.
![Tính điểm](images/add-edit-university.png)

#### Tìm hiểu về ngành học

Có đầy đủ thông tin chi tiết về tất cả các khối thi và ngành học. Người dùng có thể tìm hiểu về ngành học hoặc khối thi bằng cách highlight lên đoạn text, bấm vào biểu tượng dấu hỏi để nhận được câu trả lời.
![Tìm hiểu về ngành học](images/add-edit-university.png)
![Tìm hiểu về ngành học](images/add-edit-university.png)

#### Xem điểm chuẩn

Người dùng có thể xem thông tin về điểm chuẩn của khối thi, ngành và khu vực mình chọn.
![Xem điểm chuẩn](images/add-edit-university.png)

### Xem thông tin trường học

Từ kết quả của xem điểm chuẩn, người dùng có thể click vào tên trường để xem được ảnh, thông tin của trường. Ngoài ra, người dùng có thể xem  gợi ý về các quán ăn, nhà trọ gần trường.
![Xem thông tin trường học](images/add-edit-university.png)
![Xem thông tin trường học](images/add-edit-university.png)

### Xem thông tin tuyển sinh

Người dùng có thể xem thông tin về tuyển sinh mới nhất của các trường

![Xem thông tin tuyển sinh](images/add-edit-university.png)

#### Chatbot tư vấn ngành học thông minh

Kết hợp với API của ChatGPT, chatbot có thể hỗ trợ người dùng khi hỏi bất cứ câu hỏi nào về chọn ngành, trường học.
![Chatbot tư vấn thông minh](images/add-edit-university.png)

### Quản trị viên

Truy cập vào đường dẫn http://localhost:3000/admin, ( ở trang login tài khoản admin đã được lưu sẳn ) quản trị viên sẽ có thể sử dụng các chức năng sau:

#### Thêm, sửa, xóa thông tin trường học

Quản trị viên có thể thêm, sửa, xóa thông tin về trường học, bao gồm các thông tin về tên trường, vị trí, vị trí, logo, hình ảnh và các thông tin khác
![Thông tin tuyển sinh](images/add-edit-university.png)

#### Thêm, sửa, xóa thông tin ngành học

Quản trị viên có thể thêm, sửa, xóa thông tin về ngành học.
![Thông tin tuyển sinh](images/add-edit-university.png)

#### Thêm, sửa, xóa thông tin điểm chuẩn

Quản trị viên có thể thêm, sửa, xóa thông tin về điểm chuẩn của trường và ngành học, bao gồm các thông tin về điểm chuẩn của các năm 2020, 2021, 2022.
![Thông tin tuyển sinh](images/add-edit-university.png)

## Tài liệu tham khảo

- [ReactJS documentation](https://reactjs.org/docs/getting-started.html)
- [NodeJS documentation](https://nodejs.org/en/docs/)
- [ExpressJS documentation](https://expressjs.com/)
- [MongoDB documentation](https://docs.mongodb.com/)
- [Styled Components documentation](https://styled-components.com/docs)
