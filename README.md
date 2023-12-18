UPDATE 1.0.3
	- Update 18/12/2023 : fix lỗi link không có cáo
	- Update 13/12/2023 : bắt cáo chính xác, tùy chọn thời gian trước khi chạy tool =))
	- Anh em chạy file Twitter automation.exe trong folder "Laster" nhé !
	- Support Windows 10
	- Add câu trả lời tùy chọn với ChatGPT
	- Bỏ cuộn trang Ads
	- Fix lỗi Java


UPDATE 1.0.2

	- Fix cuộn tới cuối trang rồi tự động cuộn lên
	- Đã thêm chức năng tìm kiếm View More rồi click
	- Support : Windows 10 and Later


HƯỚNG DẪN CHUNG : 

	- 1. Cài đặt Chocolatey,mở powershell với quyền admin, sau đó chạy dòng lệnh sau : 
	"Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))"
	- 2. Cài đặt Chromium 114 bằng chocolatey : "choco install chromium --version=114.0.5735.199 -y"
	- 3. ài đặt Git : "choco install git.install -y"
	- 4. Clone : "git clone https://github.com/python194/Twitter.git"
	- 5. Copy Folder chromedriver vào thư mục gốc của ổ C 
	( sau khi copy xong sẽ có dạng như sau : "C:\chromedriver" )
	- 6. Chạy file chromedriver.exe trong Folder "C:\chromedriver" để xác nhận thư viện.
	- 7. Quay lại Folder "Twitter Automation" , đổi tên file "api_key.txt.example" thành "api_key.txt"
	- 8. Chạy File Twitter Automation để thưởng thức
	- 9. Để chéo tài khoản,vui lòng thêm link bài viết vào file Excel như mẫu. Lưu ý không để bài viết quá dài.
	- 10. Cập nhật tất cả các thay đổi : "git stash" ; "git pull origin master"
	- 11. Ngôn ngữ trình duyệt phải để bằng : Tiếng Anh
	
DONATE NẾU CÓ NHU CẦU :

	- STK : 0021000408140
	- Ngân Hàng : Vietcombank
	- Chủ Tài Khoản : HÁN ANH TƯ