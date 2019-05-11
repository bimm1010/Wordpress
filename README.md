#các bước tạo 1 localhost:8888
1. download MAMP và cài đặt 
2. chạy MAMP và nhấn start servers, trình duyệt sẽ tự động xác nhận servers đã chạy 
3. nhấn phpmyadmin ở cửa sổ web 
4. chuyển sang tab database chọn create new database, nhập tên muốn đặt và nhấn create 
5. download Wordpress giải nén và bỏ vào đường dẫn MAMP/htdocs/
6. trên trình duyệt type localhost:8888 sẽ vào setting của wordpress



#thay đổi port 8888 thành 7777

1. tắt MAMP đang chạy 
2. vào tìm file "httpd.conf" theo đường dẫn MAMP/conf/apache/httpd.conf
3. chạy file httpd.conf bằng ide 
4. tìm đến dòng "listen 8888" và sửa lại thành "listen 7777" save file 
5. chạy lại MAMP servers, trên trình duyệt type "localhost:7777" sẽ vào dc setting của wordpress 