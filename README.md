# CheckTheWordSymmetry
Mô tả bài toán
Xây dựng chương trình sử dụng đệ quy để kiểm tra một từ có phải là từ đối xứng không. Phương thức kiểm tra chuỗi đối xứng có nguyên mẫu như sau:

function isPalindrome(s) ;
Phương thức isPalindrome() trả về true nếu chuỗi truyền vào là chuỗi đối xứng. Còn lại trả về false.

Để hoàn thành bài thực hành, học viên cần:

Đưa mã nguồn lên GitHub
Dán link của repository lên phần nộp bài trên CodeGymX
Hướng dẫn
Một chuỗi palindrome là một từ được đọc theo thứ tự xuôi, ngược đều giống nhau. Ví dụ, rotor và redder là các chuỗi palindrome, nhưng motor thì không phải.

Kiểm tra một chuỗi là một palindrome được chia thành hai bài toán con

(1) Kiểm tra xem ký tự đầu tiên và ký tự cuối cùng của chuỗi có bằng nhau.

(2) Bỏ qua hai ký tự đầu và cuối, kiểm tra xem phần còn lại của chuỗi con là một palindrome.

Bài toán con thứ hai (2) giống như vấn đề ban đầu nhưng nhỏ hơn về kích thước.
