Để đọc dữ liệu từ console trong C++, bạn thường sử dụng `std::cin`, một phần của thư viện chuẩn. Đây là một vài ví dụ cơ bản về cách sử dụng `std::cin`:

1. **Đọc một số nguyên:**

   ```cpp
   #include <iostream>

   int main() {
       int number;
       std::cout << "Enter a number: ";
       std::cin >> number;
       std::cout << "You entered: " << number << std::endl;
       return 0;
   }
   ```

2. **Đọc một chuỗi ký tự:**

   ```cpp
   #include <iostream>
   #include <string>

   int main() {
       std::string name;
       std::cout << "Enter your name: ";
       std::cin >> name;  // This reads until the first whitespace
       std::cout << "Hello, " << name << "!" << std::endl;
       return 0;
   }
   ```

   Nếu bạn muốn đọc cả dòng có khoảng trắng, bạn có thể sử dụng `std::getline()`:

   ```cpp
   #include <iostream>
   #include <string>

   int main() {
       std::string line;
       std::cout << "Enter a full line: ";
       std::getline(std::cin, line);
       std::cout << "You entered: " << line << std::endl;
       return 0;
   }
   ```

3. **Đọc nhiều dữ liệu cùng một lúc:**

   ```cpp
   #include <iostream>

   int main() {
       int age;
       std::string name;
       std::cout << "Enter your name and age: ";
       std::cin >> name >> age;
       std::cout << "Name: " << name << ", Age: " << age << std::endl;
       return 0;
   }
   ```

Những ví dụ trên cho thấy cách sử dụng cơ bản của `std::cin` để nhập dữ liệu từ người dùng thông qua bảng điều khiển. Bạn có thể điều chỉnh các ví dụ này để phù hợp với nhu cầu cụ thể của bạn.
