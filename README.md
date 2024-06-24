## Bài giảng về Biến, Kiểu dữ liệu và Hàm trong C++

### Giới thiệu
Trong lập trình C++, biến, kiểu dữ liệu và hàm là những khái niệm cơ bản và rất quan trọng. Hiểu và sử dụng thành thạo những khái niệm này sẽ giúp bạn viết mã dễ hiểu và dễ sửa lỗi hơn.

### 1. Biến (Variables)
- **Định nghĩa**: Biến là một không gian lưu trữ có tên để lưu trữ dữ liệu.
- **Cú pháp khai báo**: `kiểu_dữ_liệu tên_biến;`
- **Ví dụ**:
  ```cpp
  int tuoi; // Khai báo biến 'tuoi' kiểu int
  float luong; // Khai báo biến 'luong' kiểu float
  char diem; // Khai báo biến 'diem' kiểu char
  ```

#### 1.1 Khởi tạo biến
- **Cú pháp**: `kiểu_dữ_liệu tên_biến = giá_trị;`
- **Ví dụ**:
  ```cpp
  int tuoi = 15; // Khởi tạo biến 'tuoi' với giá trị 15
  float luong = 3000.50; // Khởi tạo biến 'luong' với giá trị 3000.50
  char diem = 'A'; // Khởi tạo biến 'diem' với giá trị 'A'
  ```

### 2. Kiểu dữ liệu (Data Types)
C++ hỗ trợ nhiều kiểu dữ liệu khác nhau. Một số kiểu dữ liệu cơ bản bao gồm:

- **Kiểu số nguyên (Integer)**:
  - `int`: Số nguyên có dấu (thường dùng nhất).
  - `short`, `long`: Các biến thể của số nguyên với độ dài khác nhau.
  - **Ví dụ**:
    ```cpp
    int a = 10;
    long b = 100000;
    ```

- **Kiểu số thực (Floating Point)**:
  - `float`: Số thực đơn chính xác.
  - `double`: Số thực kép chính xác.
  - **Ví dụ**:
    ```cpp
    float x = 5.75;
    double y = 19.99;
    ```

- **Kiểu ký tự (Character)**:
  - `char`: Lưu trữ một ký tự.
  - **Ví dụ**:
    ```cpp
    char chu = 'A';
    ```

- **Kiểu logic (Boolean)**:
  - `bool`: Lưu trữ giá trị đúng hoặc sai (`true` hoặc `false`).
  - **Ví dụ**:
    ```cpp
    bool laHocSinh = true;
    ```

### 3. Hàm (Functions)
- **Định nghĩa**: Hàm là một khối mã có tên, có thể được gọi để thực thi từ nhiều nơi trong chương trình.
- **Cú pháp định nghĩa hàm**: 
  ```cpp
  kiểu_trả_về tên_hàm(danh_sách_tham_số) {
      // Khối lệnh
      return giá_trị; // nếu có
  }
  ```
- **Ví dụ**:
  ```cpp
  int cong(int a, int b) {
      return a + b;
  }

  void hienThiThongDiep() {
      std::cout << "Xin chào các bạn!";
  }
  int main () {
    int a = 10;
    int b = 20;
    tong_a_b = cong(a, b);
    count << tong_a_b;
    hienThiThongDien();
  }
  ```

#### 3.1 Gọi hàm
- **Cú pháp**: `tên_hàm(tham_số);`
- **Ví dụ**:
  ```cpp
  int tong = cong(5, 3); // Gọi hàm cong và lưu kết quả vào biến tong
  hienThiThongDiep(); // Gọi hàm hienThiThongDiep
  ```

#### 3.2 Hàm trả về không (Void Function)
- **Định nghĩa**: Hàm không trả về giá trị nào.
- **Ví dụ**:
  ```cpp
  void inSo(int so) {
      std::cout << "Số là: " << so;
  }
  ```

#### 3.3 Hàm với tham số (Function with Parameters)
- **Định nghĩa**: Hàm có thể nhận dữ liệu đầu vào thông qua tham số.
- **Ví dụ**:
  ```cpp
  void chao(std::string ten) {
      std::cout << "Xin chào, " << ten;
  }
  ```

### 4. Thực hành
- **Bài tập 1**: Viết một chương trình khai báo các biến kiểu `int`, `float`, `char`, `bool` và khởi tạo chúng với giá trị tương ứng.
- **Bài tập 2**: Viết một hàm tính tổng hai số nguyên và một hàm hiển thị một thông điệp ra màn hình.

### Tổng kết
Hiểu biết về biến, kiểu dữ liệu và hàm là nền tảng quan trọng trong lập trình C++. Qua bài giảng này, bạn đã được giới thiệu về cách khai báo và sử dụng chúng trong C++. Hãy tiếp tục thực hành và áp dụng những kiến thức này vào các bài tập và dự án thực tế để nắm vững hơn.

Chúc các bạn học tốt!

---

Hy vọng bài giảng này sẽ giúp các học sinh lớp 8 của bạn dễ dàng hiểu và học lập trình C++.
