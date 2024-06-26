### Bài giảng chi tiết về vòng lặp và cấu trúc điều kiện trong C++ cho người mới nhập môn

#### Mục tiêu:
- Hiểu và sử dụng được các vòng lặp `for`, `while`.
- Hiểu và áp dụng được cấu trúc điều kiện `if`, `else`.
- Thực hành qua các ví dụ và bài tập cụ thể.

### Phần 1: Tổng quan về điều kiện và vòng lặp

#### 1. Điều kiện là gì?

Điều kiện là một mệnh đề mà kết quả của nó có thể là đúng (true) hoặc sai (false). Trong lập trình, điều kiện giúp chúng ta quyết định xem một đoạn mã có được thực thi hay không. 

##### Ví dụ thực tế:
Hãy tưởng tượng bạn đang lái xe và gặp đèn giao thông. Nếu đèn màu xanh, bạn sẽ đi tiếp; nếu đèn màu đỏ, bạn sẽ dừng lại. Đó chính là một ví dụ về điều kiện trong cuộc sống.

#### 2. Vòng lặp là gì?

Vòng lặp là một cấu trúc cho phép chúng ta thực thi một đoạn mã nhiều lần cho đến khi một điều kiện nào đó không còn đúng nữa.

##### Ví dụ thực tế:
Hãy tưởng tượng bạn muốn tưới cây trong vườn. Bạn sẽ tưới từng cây một cho đến khi tất cả các cây đều được tưới. Đó chính là một ví dụ về vòng lặp trong cuộc sống.

#### 3. Tại sao cần điều kiện?

Điều kiện giúp chương trình có thể ra quyết định và thực hiện các hành động khác nhau dựa trên các tình huống khác nhau. Điều này làm cho chương trình trở nên linh hoạt và thông minh hơn.

#### 4. Tại sao cần vòng lặp?

Vòng lặp giúp chúng ta thực hiện một công việc nhiều lần mà không cần phải viết lại mã cho mỗi lần thực hiện. Điều này giúp tiết kiệm thời gian và làm cho mã nguồn gọn gàng, dễ hiểu hơn.

### Phần 2: Vòng lặp trong C++

#### 1. Vòng lặp `for`

##### Cú pháp:
```cpp
for (khoi_tao; dieu_kien; tang_bien) {
    // khối mã sẽ được thực thi
}
```

##### Giải thích:
- `khoi_tao`: Khởi tạo biến điều khiển vòng lặp, thực hiện một lần duy nhất khi vòng lặp bắt đầu.
- `dieu_kien`: Biểu thức điều kiện, vòng lặp tiếp tục nếu điều kiện này đúng.
- `tang_bien`: Tăng hoặc giảm biến điều khiển sau mỗi lần lặp.

##### Ví dụ:
```cpp
#include <iostream>
using namespace std;

int main() {
    for (int i = 0; i < 5; i++) {
        cout << "Gia tri cua i la: " << i << endl;
    }
    return 0;
}
```

#### 2. Vòng lặp `while`

##### Cú pháp:
```cpp
while (dieu_kien) {
    // khối mã sẽ được thực thi
}
```

##### Giải thích:
- `dieu_kien`: Biểu thức điều kiện, vòng lặp tiếp tục nếu điều kiện này đúng.

##### Ví dụ:
```cpp
#include <iostream>
using namespace std;

int main() {
    int i = 0;
    while (i < 5) {
        cout << "Gia tri cua i la: " << i << endl;
        i++;
    }
    return 0;
}
```

#### 3. Vòng lặp `do...while`

##### Cú pháp:
```cpp
do {
    // khối mã sẽ được thực thi
} while (dieu_kien);
```

##### Giải thích:
- Vòng lặp sẽ thực hiện ít nhất một lần, sau đó kiểm tra điều kiện để quyết định tiếp tục hay dừng.

##### Ví dụ:
```cpp
#include <iostream>
using namespace std;

int main() {
    int i = 0;
    do {
        cout << "Gia tri cua i la: " << i << endl;
        i++;
    } while (i < 5);
    return 0;
}
```

### Phần 3: Cấu trúc điều kiện trong C++

#### 1. Cấu trúc `if`

##### Cú pháp:
```cpp
if (dieu_kien) {
    // khối mã sẽ được thực thi nếu điều kiện đúng
}
```

##### Ví dụ:
```cpp
#include <iostream>
using namespace std;

int main() {
    int x = 10;
    if (x > 5) {
        cout << "x lon hon 5" << endl;
    }
    return 0;
}
```

#### 2. Cấu trúc `if...else`

##### Cú pháp:
```cpp
if (dieu_kien) {
    // khối mã sẽ được thực thi nếu điều kiện đúng
} else {
    // khối mã sẽ được thực thi nếu điều kiện sai
}
```

##### Ví dụ:
```cpp
#include <iostream>
using namespace std;

int main() {
    int x = 10;
    if (x > 5) {
        cout << "x lon hon 5" << endl;
    } else {
        cout << "x khong lon hon 5" << endl;
    }
    return 0;
}
```

#### 3. Cấu trúc `if...else if...else`

##### Cú pháp:
```cpp
if (dieu_kien1) {
    // khối mã sẽ được thực thi nếu điều kiện1 đúng
} else if (dieu_kien2) {
    // khối mã sẽ được thực thi nếu điều kiện2 đúng
} else {
    // khối mã sẽ được thực thi nếu tất cả điều kiện đều sai
}
```

##### Ví dụ:
```cpp
#include <iostream>
using namespace std;

int main() {
    int x = 10;
    if (x > 20) {
        cout << "x lon hon 20" << endl;
    } else if (x > 5) {
        cout << "x lon hon 5 nhung khong lon hon 20" << endl;
    } else {
        cout << "x khong lon hon 5" << endl;
    }
    return 0;
}
```

### Phần 4: Bài tập thực hành

#### Bài tập 1: In ra các số từ 1 đến 10 sử dụng vòng lặp `for`

##### Đề bài:
Viết chương trình in ra các số từ 1 đến 10 sử dụng vòng lặp `for`.

##### Input:
Không có.

##### Output:
1 2 3 4 5 6 7 8 9 10

#### Bài tập 2: Tính tổng các số từ 1 đến 100 sử dụng vòng lặp `while`

##### Đề bài:
Viết chương trình tính tổng các số từ 1 đến 100 sử dụng vòng lặp `while`.

##### Input:
Không có.

##### Output:
Tổng các số từ 1 đến 100 là: 5050

#### Bài tập 3: Kiểm tra một số có phải là số chẵn hay không sử dụng cấu trúc điều kiện `if...else`

##### Đề bài:
Viết chương trình nhập vào một số và kiểm tra xem số đó có phải là số chẵn hay không.

##### Input:
- Một số nguyên `so`.

##### Output:
- Nếu số đó là số chẵn, in ra: `<so> la so chan`
- Nếu số đó là số lẻ, in ra: `<so> la so le`

##### Ví dụ:
- Input: 4
- Output: 4 la so chan

- Input: 7
- Output: 7 la so le

Hy vọng bài giảng và các bài tập này sẽ giúp bạn nắm vững hơn về các vòng lặp và cấu trúc điều kiện trong C++. Chúc bạn học tốt!
