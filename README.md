# Tao file quản lý dự án

`npm init` <br>
Enter <br>

# package.json

File quản lý dự án của chúng ta <br>

- Tên dự án
- Thư viện được sử dụng trong dự án

# để cài thư viện dự án

`npm install <ten_thu_vien>`
'npm i <ten_thu_vien>'

# để xoá

`npm uninstall <ten_thu_vien>`

# sau khi cài xong thư viện

-liệt kê thư viện được cài đặt trong file package.json <br>
-tạo ra folder node_modules: chứa các thư viện được cài đặt trong dự án.
tạo ra file package-lock.json

# so sánh package.json vs package-lock.json
- package.json: liệt kê khoảng version được phép cài đặt trong dự án
- package-lock.json: liệt kê chính xác version mà chúng ta cài đặt trong dự án.

# .gitignore
-loại bỏ những folder hay file không muốn comit lên git <br>
-loại bỏ node_modules: vì quá nặng. <br>
