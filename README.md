Hướng dẫn: 

YÊU CẦU ĐÃ CÀI PYTHON NHÉ ANH EM

Chạy lệnh sau để cài các module cần thiết

pip install -r requirements.txt

tạo 2 file data.txt và proxy.txt nhé

Định dạng proxy : http://user:pass@ip:port

trong file data.txt phải có định dạng

eyJhbGciOiJIUzUxMiJ9....

Lấy data bằng cách vào https://app.nodepay.ai/dashboard bấm f12, dán code sau vào console

localStorage.getItem('np_token');
copy chuỗi vừa lấy được ném vào data.txt, hoặc có thể lấy trong network nhé

Chạy tool bằng lệnh

python nodepay.py
