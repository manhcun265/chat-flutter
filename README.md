[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Cnoy1g24)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17164735&assignment_repo_type=AssignmentRepo)

# Bài tập lớn - Phát triển ứng dụng với Flutter

## Thông tin sinh viên
- **Họ và tên**: Lê Văn Mạnh
- **MSSV**: 2121050680
- **Lớp**: 24K1-7080325-200

## Giới thiệu
Đây là yêu cầu của bài tập lớn cho một trong hai học phần **Phát triển ứng dụng di động đa nền tảng 1 (mã học phần 7080325) và Phát triển ứng dụng cho thiết bị di động + BTL (mã học phần 7080115)**. Sinh viên sẽ xây dựng một ứng dụng di động hoàn chỉnh sử dụng Flutter và Dart, áp dụng các kiến thức đã học về lập trình giao diện người dùng, quản lý trạng thái, tích hợp API hoặc/và CSDL, kiểm thử tự động và CI/CD với GitHub Actions.

## 1 Tính Năng Chính
### 1.1 CRUD
Bài tập lớn nhằm:
- Cho phép người dùng đăng ký tài khoản mới và gửi tin nhắn.
- Hiển thị danh sách người dùng và tin nhắn từ cơ sở dữ liệu.

### 2.2. Tích Hợp API
- Ứng dụng tích hợp với Firebase để quản lý xác thực người dùng và lưu trữ tin nhắn. Cụ thể:
  - Firebase Authentication: Quản lý đăng nhập và đăng ký người dùng.
  - Firebase Firestore: Lưu trữ và quản lý dữ liệu người dùng và tin nhắn.

### 2.3. Giao Diện Người Dùng
- Giao diện người dùng được thiết kế đơn giản, thân thiện và dễ sử dụng. Các màn hình chính bao gồm:
  - Màn hình đăng nhập và đăng ký: Cho phép người dùng tạo tài khoản mới hoặc đăng nhập vào tài khoản hiện có.
  - Màn hình danh sách người dùng: Hiển thị danh sách người dùng để chọn người nhận tin nhắn.
  - Màn hình chat: Hiển thị lịch sử tin nhắn và cho phép người dùng gửi tin nhắn mới.

## 3. Kiểm thử tự động và CI/CD
- Ứng dụng bao gồm các bài kiểm thử tự động để đảm bảo chất lượng và độ ổn định. Các kiểm thử bao gồm:
  - Kiểm thử đơn vị (Unit Tests): Kiểm tra các hàm và phương thức riêng lẻ.
  - Sử dụng GitHub Actions để tự động chạy các kiểm thử khi có thay đổi mã nguồn.
  - Kiểm thử giao diện (UI Tests): Đảm bảo rằng giao diện người dùng hoạt động như mong đợi.

## 4. Công nghệ và Thư viện sử dụng
Sinh viên cần liệt kê một số công nghệ và thư viện cần sử dụng trong quá trình phát triển ứng dụng, ví dụ:
- **Flutter**: Để xây dựng giao diện người dùng.
- **Dart**: Ngôn ngữ lập trình sử dụng trong Flutter.
- **Firebase AuthenticationO**: Quản lý xác thực người dùng.
- **localstore**: Để lưu trữ dữ liệu cục bộ, giúp ứng dụng có thể hoạt động offline.
- **Test Framework (flutter_test)**: Sử dụng để viết các bài kiểm thử tự động.
- **GitHub Actions**: Để tự động hóa quy trình kiểm thử khi có thay đổi mã nguồn.

## kết quả
### 4.1. Quá Trình Thực Hiện
- Quá trình thực hiện bài tập lớn bao gồm các bước chính:
  - Phân tích yêu cầu: Xác định các yêu cầu của ứng dụng và lập kế hoạch thực hiện.
  -	Thiết kế giao diện: Tạo các mockup và wireframe cho ứng dụng.
  -	Phát triển chức năng: Triển khai các tính năng CRUD, tích hợp API và giao diện người dùng.
  - Kiểm thử: Thực hiện kiểm thử tự động và kiểm thử thủ công để đảm bảo chất lượng ứng dụng.
### 4.2. Kết Quả Cuối Cùng
- Ứng dụng Flutter với các tính năng CRUD, tích hợp Firebase, giao diện người dùng thân thiện và hệ thống kiểm thử tự động. Ứng dụng hoạt động mượt mà và đáp ứng tốt các yêu cầu đặt ra.
## 5. Hướng Dẫn Cài Đặt
1. Tải mã nguồn từ repository.
    ```bash
    git clone <đường dẫn tới repo>
    ```

2. Cài đặt các dependencies:
   ```bash
   flutter pub get
   ```
3. Chạy ứng dụng:
   ```bash
   flutter run
   ```
4. Kiểm tra ứng dụng trên thiết bị hoặc máy ảo.
5. Đăng nhập hoặc tạo tài khoản mới (nếu cần).
6. Thực hiện các thao tác CRUD và kiểm tra kết quả.
7. Thực hiện kiểm thử tự động và xem kết quả:
    ```bash
    flutter test
    ```
## 6. Screenshots

## 7. Video Demo

## Yêu cầu nộp bài
- **Source code**: Đẩy toàn bộ mã nguồn lên GitHub repository cá nhân và chia sẻ quyền truy cập.
- **Kiểm thử tự động**: Sinh viên cần viết các bài kiểm thử tự động cho ứng dụng. Các bài kiểm thử cần được tổ chức rõ ràng và dễ hiểu trong thư mục `test` với hậu tố `_test.dart`. Các bài kiểm thử đơn vị (unit test) cần kiểm tra các chức năng cơ bản của ứng dụng và đảm bảo chất lượng mã nguồn. Kiểm thử UI (widget test) cần được viết để kiểm tra giao diện người dùng và các tương tác người dùng cơ bản.
- **Các video demo**: 
  - Quá trình kiểm thử tự động bao gồm kiểm thử đơn vị và kiểm thử UI (bắt buộc).
  - Trình bày các chức năng chính của ứng dụng (bắt buộc).
  Các video cần biên tập sao cho rõ ràng, dễ hiểu và không quá dài (tối đa 5 phút).
- **Báo cáo kết quả**: Đây là nội dung báo cáo của bài tập lớn. Sinh viên cần viết báo cáo ngắn mô tả quá trình phát triển, các thư viện đã sử dụng và các kiểm thử đã thực hiện. Có thể viết trực tiếp trên file README.md này ở mục `Báo cáo kết quả`.
- **GitHub Actions**: Thiết lập GitHub Actions để chạy kiểm thử tự động khi có thay đổi mã nguồn. Tệp cấu hình workflow cần được đặt trong thư mục `.github/workflows`, đặt tên tệp theo định dạng `ci.yml` (có trong mẫu của bài tập lớn). Github Actions cần chạy thành công và không có lỗi nếu mã nguồn không có vấn đề. Trong trường hợp có lỗi, sinh viên cần sửa lỗi và cập nhật mã nguồn để build thành công. Nếu lỗi liên quan đến `Billing & plans`, sinh viên cần thông báo cho giảng viên để được hỗ trợ hoặc bỏ qua yêu cầu này.

## Tiêu chí đánh giá
**5/10 điểm - Build thành công (GitHub Actions báo “Success”)**
- Sinh viên đạt tối thiểu 5 điểm nếu GitHub Actions hoàn thành build và kiểm thử mà không có lỗi nào xảy ra (kết quả báo “Success”).
- Điểm này dành cho những sinh viên đã hoàn thành cấu hình cơ bản và mã nguồn có thể chạy nhưng có thể còn thiếu các tính năng hoặc có các chức năng chưa hoàn thiện.
- Nếu gặp lỗi liên quan đến `Billing & plans` thì phải đảm bảo chay thành công trên máy cá nhân và cung cấp video demo cùng với lệnh `flutter test` chạy thành công.

**6/10 điểm - Thành công với kiểm thử cơ bản (CRUD tối thiểu)**
- Sinh viên đạt 6 điểm nếu build thành công và vượt qua kiểm thử cho các chức năng CRUD cơ bản (tạo, đọc, cập nhật, xóa) cho đối tượng chính.
- Tối thiểu cần thực hiện CRUD với một đối tượng cụ thể (ví dụ: sản phẩm hoặc người dùng), đảm bảo thao tác cơ bản trên dữ liệu.

**7/10 điểm - Kiểm thử CRUD và trạng thái (UI cơ bản, quản lý trạng thái)**
- Sinh viên đạt 7 điểm nếu ứng dụng vượt qua các kiểm thử CRUD và các kiểm thử về quản lý trạng thái.
- Giao diện hiển thị danh sách và chi tiết đối tượng cơ bản, có thể thực hiện các thao tác CRUD mà không cần tải lại ứng dụng.
- Phản hồi người dùng thân thiện (hiển thị kết quả thao tác như thông báo thành công/thất bại).

**8/10 điểm - Kiểm thử CRUD, trạng thái và tích hợp API hoặc/và CSDL**
- Sinh viên đạt 8 điểm nếu ứng dụng vượt qua kiểm thử cho CRUD, trạng thái, và tích hợp API hoặc/và cơ sở dữ liệu (Firebase, MySQL hoặc lưu trữ cục bộ) hoặc tương đương.
- API hoặc cơ sở dữ liệu phải được tích hợp hoàn chỉnh, các thao tác CRUD liên kết trực tiếp với backend hoặc dịch vụ backend.
- Các lỗi từ API hoặc cơ sở dữ liệu được xử lý tốt và có thông báo lỗi cụ thể cho người dùng.

**9/10 điểm - Kiểm thử tự động toàn diện và giao diện hoàn thiện**
- Sinh viên đạt 9 điểm nếu vượt qua các kiểm thử toàn diện bao gồm:
- CRUD đầy đủ
- Quản lý trạng thái
- Tích hợp API/CSDL
- Giao diện người dùng hoàn chỉnh và thân thiện, dễ thao tác, không có lỗi giao diện chính.
- Đảm bảo chức năng xác thực (nếu có), cập nhật thông tin cá nhân, thay đổi mật khẩu (nếu có).

**10/10 điểm - Kiểm thử và tối ưu hóa hoàn chỉnh, UI/UX mượt mà, CI/CD ổn định**
- Sinh viên đạt 10 điểm nếu ứng dụng hoàn thành tất cả kiểm thử tự động một cách hoàn hảo và tối ưu hóa tốt (không có cảnh báo trong kiểm thử và phân tích mã nguồn).
- UI/UX đẹp và mượt mà, có tính nhiều tính năng và tính năng nâng cao (ví dụ: tìm kiếm, sắp xếp, lọc dữ liệu).
- GitHub Actions CI/CD hoàn thiện, bao gồm kiểm thử và các bước phân tích mã nguồn (nếu thêm), đảm bảo mã luôn ổn định.

**Tóm tắt các mức điểm:**
- **5/10**: Build thành công, kiểm thử cơ bản chạy được.
- **6/10**: CRUD cơ bản với một đối tượng.
- **7/10**: CRUD và quản lý trạng thái (hiển thị giao diện cơ bản).
- **8/10**: CRUD, trạng thái, và tích hợp API/CSDL với thông báo lỗi.
- **9/10**: Hoàn thiện kiểm thử CRUD, trạng thái, tích hợp API/CSDL; UI thân thiện.
- **10/10**: Tối ưu hóa hoàn chỉnh, UI/UX mượt mà, CI/CD đầy đủ và ổn định.

## Tự đánh giá điểm: 7/10
Sinh viên cần tự đánh giá mức độ hoàn thiện của ứng dụng và so sánh với tiêu chí đánh giá để xác định điểm cuối cùng. Điểm tự đánh giá sẽ được sử dụng như một tiêu chí tham khảo cho giảng viên đánh giá cuối cùng.

Chúc các bạn hoàn thành tốt bài tập lớn và khám phá thêm nhiều kiến thức bổ ích qua dự án này!
