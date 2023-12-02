UPDATE 1.0.3

	- Support Windows 10
	- Add câu trả lời tùy chọn với ChatGPT


UPDATE 1.0.2

	- Fix cuộn tới cuối trang rồi tự động cuộn lên
	- Đã thêm chức năng tìm kiếm View More rồi click
	- Support : Windows 10 and Later


HƯỚNG DẪN CHUNG : 

	- Cài đặt Chocolatey,mở powershell với quyền admin, sau đó chạy dòng lệnh sau : 
	"Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))"

	- Cài đặt Chromium 114 bằng chocolatey : "choco install chromium --version=114.0.5735.199 -y"
	- Copy Folder chromedriver vào thư mục gốc của ổ C 
	( sau khi copy xong sẽ có dạng như sau : "C:\chromedriver" )
	- Chạy file chromedriver.exe trong Folder "C:\chromedriver" để xác nhận thư viện.
	- Quay lại Folder "Twitter Automation" , đổi tên file "api_key.txt.example" thành "api_key.txt"
	- Chạy File Twitter Automation để thưởng thức
	- Để chéo tài khoản,vui lòng thêm link bài viết vào file Excel như mẫu

DONATE NẾU CÓ NHU CẦU :

	- STK : 0021000408140
	- Ngân Hàng : Vietcombank
	- Chủ Tài Khoản : HÁN ANH TƯ