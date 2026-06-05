# Auto-Quest-Discord ENGLISH GUIDE VERSION 

Auto quest discord

## System Requirements
- **Node.js**: Version >= 18 (Download from: [Node.js Official Website](https://nodejs.org/))
- **Git**

## Installation Guide

1. **Clone or download the source code**:
   ```bash
   git clone https://github.com/harukykun/Auto-Quest-Discord.git
   cd Auto-Quest-Discord
   ```

2. **Install dependencies**:
   Open a terminal in the project folder and run the following command to install required libraries:
   ```bash
   npm install
   ```

## Get Authentication Token
1. Open Discord and open DevTools (F12 on web, Ctrl + Shift + I on client)
2. In the Network tab find `/api/v9/users/@me` and refresh the page (F5 on web, Ctrl + R on client)
3. Select any request, then scroll down to the Request headers section. You will see `authorization` with the corresponding token.

## Configuration

This project requires an environment file (`.env`) to run.

1. Rename `.env.example` to `.env`
2. Paste the authentication token into `TOKEN`

## Usage

After installing and configuring `.env`, you can run the bot with:

- **Start the bot**:
  ```bash
  npm start
  ```

# Auto-Quest-Discord HƯỚNG DẪN BẢN TIẾNG VIỆT

Auto quest discord

- [English version](README_en.md)

## Yêu cầu tải các gói hệ thống
- **Node.js**: Phiên bản >= 18 (Tải tại đây: [Node.js Official Website](https://nodejs.org/))
- **Git**
## Hướng dẫn cài đặt

1. **Clone hoặc tải mã nguồn về máy**:
   ```bash
   git clone https://github.com/harukykun/Auto-Quest-Discord.git
   cd Auto-Quest-Discord
   ```

2. **Cài đặt thư viện (dependencies)**:
   Mở terminal tại thư mục dự án và chạy lệnh sau để cài đặt các thư viện cần thiết:
   ```bash
   npm install
   ```
## Lấy mã authen
1. Lên discord mở devtool (F12 với web, ctrl + shift + i với client) 
2. Qua network tìm /api/v9/users/@me sau đó refresh lại trang (F5 với web, ctrl + r với client)
3. Vào bất cứ mục nào, sau đó kéo xuống phần Request headers bạn sẽ thấy authorization kèm mã tương ứng

## Cấu hình 

Dự án yêu cầu một file biến môi trường (`.env`) để hoạt động.

1. Đổi tên file .env.example thành .env
2. Dán mã authen vào TOKEN

## Hướng dẫn sử dụng

Sau khi cài đặt xong và đã cấu hình `.env`, bạn có thể chạy bot bằng các lệnh sau:

- **Chạy bot**:
  ```bash
  npm start
  ```
