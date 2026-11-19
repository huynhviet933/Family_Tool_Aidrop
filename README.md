'HƯỚNG DẪN CÀI ĐẶT & CHẠY TOOL

1. Mở CMD tại thư mục chứa file main.js:
npm install axios ethers https-proxy-agent node-machine-id colors

2. Chạy tool:
node main.js

---
CHUẨN BỊ FILE ĐẦU VÀO (CÙNG THƯ MỤC main.js)

- privatekey.txt (Bắt buộc): 1 private key / dòng (có hoặc không có 0x)
0x1234567890abcdef1234567890abcdef1234567890abcdef1234567890abcdef
fedcba0987654321fedcba0987654321fedcba0987654321fedcba0987654321

- license.txt (Bắt buộc): 1 license key (không có tool sẽ hỏi nhập lúc chạy)
YOUR-LICENSE-KEY-HERE

- proxy.txt: 1 proxy / dòng
http://user:pass@127.0.0.1:8080
http://127.0.0.1:8080

- User_agents.txt: 1 User-Agent / dòng (chú ý viết hoa U)
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/150.0.0.0 Safari/537.36

- ref.txt: MA_REF|SO_LUOT trên 1 dòng
ABC123|50
XYZ789|20

- config.json (Tự tạo nếu chưa có):
{
  "max_threads": 3,
  "delay_task_min": 3,
  "delay_task_max": 10,
  "delay_thread_start_min": 3,
  "delay_thread_start_max": 10,
  "delay_wallet_min": 30,
  "delay_wallet_max": 60,
  "auto_reset_7am_vn": true
}

- index.txt (Tự tạo nếu chưa có): Số nguyên vị trí ví bắt đầu
0'


Channel 

Free Airdrop Channel: https://t.me/Vietmmo_Aidrop 
Discord Channel: https://discord.com/invite/uw7dCDbnJu 
Purchase Keyline: https://web.telegram.org/k/#@ToolAirDrop_Bot
Donate : https://huynhviet933.github.io/donate_viet_mmo/
