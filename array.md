## Bài giảng chi tiết về array trong C++

### Mở đầu

#### Array là gì?

Array (mảng) là một cấu trúc dữ liệu trong C++ dùng để lưu trữ một tập hợp các phần tử cùng kiểu dữ liệu. Các phần tử này được lưu trữ liên tiếp nhau trong bộ nhớ, và có thể được truy cập thông qua chỉ số (index).

#### Tại sao cần array?

Trong lập trình, có nhiều tình huống chúng ta cần làm việc với một nhóm các giá trị cùng loại. Sử dụng array giúp chúng ta dễ dàng quản lý và thao tác trên các giá trị này. Array cung cấp một cách hiệu quả để lưu trữ và truy xuất dữ liệu, tiết kiệm bộ nhớ và tăng hiệu suất xử lý.

#### Ví dụ liên tưởng trong cuộc sống

Hãy tưởng tượng bạn có một hộp bút chì màu, mỗi bút chì là một phần tử của array. Bạn có thể dễ dàng truy xuất một bút chì cụ thể bằng cách đếm số thứ tự của nó trong hộp. Đây chính là cách array hoạt động: các phần tử được truy cập bằng chỉ số, bắt đầu từ 0.

### Nội dung chính

#### 1. Khai báo và khởi tạo array

Trong C++, array có thể được khai báo và khởi tạo theo nhiều cách khác nhau. Ví dụ:

```cpp
#include <iostream>
using namespace std;

int main() {
    int mang[5]; // Khai báo một mảng chứa 5 phần tử kiểu int
    int mang_khoi_tao[5] = {1, 2, 3, 4, 5}; // Khởi tạo một mảng với các giá trị cụ thể

    cout << "Mang da khoi tao: ";
    for(int i = 0; i < 5; i++) {
        cout << mang_khoi_tao[i] << " ";
    }
    cout << endl;

    return 0;
}
```

#### 2. Truy cập và thay đổi phần tử trong array

Phần tử của array có thể được truy cập và thay đổi thông qua chỉ số:

```cpp
#include <iostream>
using namespace std;

int main() {
    int mang[5] = {1, 2, 3, 4, 5}; // Khởi tạo mảng

    // Gán giá trị 10 cho phần tử đầu tiên của mảng
    mang[0] = 10;

    // Truy xuất phần tử thứ ba của mảng
    int gia_tri = mang[2];

    cout << "Gia tri cua phan tu thu 3: " << gia_tri << endl;

    cout << "Mang sau khi thay doi phan tu dau tien: ";
    for(int i = 0; i < 5; i++) {
        cout << mang[i] << " ";
    }
    cout << endl;

    return 0;
}
```

#### 3. Vòng lặp và array

Sử dụng vòng lặp để duyệt qua các phần tử của array là một kỹ thuật phổ biến:

```cpp
#include <iostream>
using namespace std;

int main() {
    int mang_khoi_tao[5] = {1, 2, 3, 4, 5}; // Khởi tạo mảng

    cout << "Cac phan tu trong mang: ";
    for(int i = 0; i < 5; i++) {
        cout << mang_khoi_tao[i] << " ";
    }
    cout << endl;

    return 0;
}
```

#### 4. Các thao tác trên array

**Tính tổng các phần tử trong array**:

```cpp
#include <iostream>
using namespace std;

int main() {
    int mang_khoi_tao[5] = {1, 2, 3, 4, 5}; // Khởi tạo mảng

    int tong = 0;
    for(int i = 0; i < 5; i++) {
        tong += mang_khoi_tao[i];
    }
    cout << "Tong cac phan tu trong mang: " << tong << endl;

    return 0;
}
```

**Tìm giá trị lớn nhất trong array**:

```cpp
#include <iostream>
using namespace std;

int main() {
    int mang_khoi_tao[5] = {1, 2, 3, 4, 5}; // Khởi tạo mảng

    int gia_tri_lon_nhat = mang_khoi_tao[0];
    for(int i = 1; i < 5; i++) {
        if(mang_khoi_tao[i] > gia_tri_lon_nhat) {
            gia_tri_lon_nhat = mang_khoi_tao[i];
        }
    }
    cout << "Gia tri lon nhat trong mang: " << gia_tri_lon_nhat << endl;

    return 0;
}
```

### Bài tập thực hành

#### Bài tập 1: Đếm số phần tử chẵn trong array

Viết một chương trình C++ để đếm số phần tử chẵn trong một mảng.
Viết một chương trình C++ để tính trung bình cộng các phần tử trong một mảng.
Yêu cầu: Khởi tạo một biến là một mảng int, có 9 giá trị là 1,3,5,7,9,2,4,6,8. Đếm các phần tử là số chẵn trong mảng (array) đã khởi tạo.
Output: So phan tu chan la: 4

#### Bài tập 2: Tính trung bình cộng các phần tử trong array

Viết một chương trình C++ để tính trung bình cộng các phần tử trong một mảng.
Yêu cầu: Khởi tạo một biến là một mảng int, có 9 giá trị là 1,3,5,7,9,2,4,6,8. tính trung bình cộng của các phần tử trong mảng (array) đã khởi tạo.
Output: Trung binh cong la: 5

### Kết luận

Array là một cấu trúc dữ liệu cơ bản và quan trọng trong C++. Hiểu và sử dụng array hiệu quả giúp chúng ta quản lý và xử lý dữ liệu một cách hiệu quả hơn trong các chương trình. Các kỹ thuật và ví dụ trên hy vọng sẽ giúp các bạn nắm vững hơn về cách sử dụng array trong C++.
