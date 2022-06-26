# Hướng dẫn sử dụng cronjsob bằng nodejs

# Bước 1:
Cài đặt nodejs từ <a href="https://nodejs.org/en/download/">https://nodejs.org/en/download/</a>

# Bước 2:
Chạy lệnh
```base
git clone https://github.com/haiquang110/cronjob.git
```

# Bước 3:
Chạy lệnh 
```base
cd cronjob
```

# Bước 4:
Chạy lệnh
```base
npm install axios
```

# Sau khi cài đặt xong các bước trên thì tiến hành tạo file linkcron.txt trong thư mục cronjob, sau đó thêm Link cron vào.
<b><span style="color: red;">Lưu ý:</span> Mỗi link 1 dòng</b>

# Sau khi thêm link cron tiến hành:
Chạy lệnh
```base 
node cron
```

Nhập số giây muốn cron, tối thiểu 2-5s đỡ bị dupp vì mình viết setInterval chứ không phải module node cron.

<h1>Author: Nguyễn Hải Quang</h1>
<h1>Facebook: <a href="https://facebook.com/quang.hai.uda77">https://facebook.com/quang.hai.uda77</a></h1>
<h1>Zalo: <a href="https://zalo.me/0359917579">https://zalo.me/0359917579</a></h1>
