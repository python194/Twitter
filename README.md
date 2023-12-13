UPDATE 1.0.3
	- Update 13/12/2023 : bắt cáo chính xác, tùy chọn thời gian trước khi chạy tool =))
	- Support Windows 10
	- Add câu trả lời tùy chọn với ChatGPT
	- Bỏ cuộn trang Ads
	- Fix lỗi Java


UPDATE 1.0.2

	- Fix cuộn tới cuối trang rồi tự động cuộn lên
	- Đã thêm chức năng tìm kiếm View More rồi click
	- Support : Windows 10 and Later


HƯỚNG DẪN CHUNG : 

	- Cài đặt Chocolatey,mở powershell với quyền admin, sau đó chạy dòng lệnh sau : 
	"Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))"

	- Cài đặt Chromium 114 bằng chocolatey : "choco install chromium --version=114.0.5735.199 -y"
	- Cài đặt Git : "choco install git.install -y"
	- Clone : "git clone https://github.com/python194/Twitter.git"
	- Copy Folder chromedriver vào thư mục gốc của ổ C 
	( sau khi copy xong sẽ có dạng như sau : "C:\chromedriver" )
	- Chạy file chromedriver.exe trong Folder "C:\chromedriver" để xác nhận thư viện.
	- Quay lại Folder "Twitter Automation" , đổi tên file "api_key.txt.example" thành "api_key.txt"
	- Chạy File Twitter Automation để thưởng thức
	- Để chéo tài khoản,vui lòng thêm link bài viết vào file Excel như mẫu. Lưu ý không để bài viết quá dài.
	- Cập nhật tất cả các thay đổi : "git stash" ; "git pull origin master"
	- Ngôn ngữ phải để bằng : Tiếng Anh
	
DONATE NẾU CÓ NHU CẦU :

	- STK : 0021000408140
	- Ngân Hàng : Vietcombank
	- Chủ Tài Khoản : HÁN ANH TƯ