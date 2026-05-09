# VsisProxy — Chrome / Edge / Brave Extension Releases

[![Chrome Web Store](https://img.shields.io/badge/Chrome-Web%20Store-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/vsisproxy/)
[![License: MPL 2.0](https://img.shields.io/badge/License-MPL_2.0-orange.svg)](https://www.mozilla.org/MPL/2.0/)

Tiện ích quản lý + chuyển proxy nhanh trên Chrome / Edge / Brave / Cốc Cốc của [VSIS](https://vsis.net).
Hỗ trợ HTTP / HTTPS / SOCKS5 / SOCKS4, auto-switch theo URL kiểu SwitchyOmega.

> Repo này chỉ chứa **release artifacts** (file `.zip` / `.crx` cài cho khách).
> Source code là tài sản nội bộ VSIS — không công khai.

> **Đang chuẩn bị release đầu tiên.** Bản Firefox đã có tại
> [vsisproxy-firefox-releases](https://github.com/vsisnet/vsisproxy-firefox-releases).

## ⚠️ Lưu ý quan trọng cho bản Chrome

Chrome **không hỗ trợ user/password authentication cho SOCKS5** (giới hạn lâu năm của Chromium). Nếu cần SOCKS5 + auth, sếp/khách dùng **bản Firefox**. Bản Chrome chạy tốt với:

- HTTP / HTTPS proxy có hoặc không có auth
- SOCKS5 / SOCKS4 **không** có auth

## 🔽 Cài đặt (sẽ cập nhật khi có release)

### Cách 1 — Chrome Web Store *(khuyến nghị, sau khi Google approve)*

```
https://chromewebstore.google.com/detail/vsisproxy/
```

### Cách 2 — Tải `.zip` từ Releases và load unpacked

1. Mở tab **[Releases](https://github.com/vsisnet/vsisproxy-extension-releases/releases)**
2. Tải file `.zip` của version mới nhất, giải nén
3. Mở `chrome://extensions/`
4. Bật **Developer mode** (góc trên phải)
5. Click **Load unpacked** → chọn thư mục vừa giải nén

## ✨ Tính năng

- Dán proxy nhiều format: `ip:port`, `ip:port:user:pass`, `user:pass@ip:port`, `http://`, `https://`, `socks5://`, `socks4://`
- 1-click chuyển proxy cho cửa sổ Chrome
- Auto-switch theo URL với rule wildcard / host / regex
- Profile có màu + nhãn riêng, sync giữa thiết bị qua Chrome Sync
- Test proxy trong popup (latency + IP echo)
- UI Tiếng Việt + English

## 🔒 Quyền riêng tư

- Không telemetry, không analytics
- Không inject content script vào trang web
- Không gọi mạng trừ khi user bấm **Test proxy**
- Đầy đủ: [PRIVACY.md](./PRIVACY.md)

## 📞 Hỗ trợ

- Email: [vsisnet@gmail.com](mailto:vsisnet@gmail.com)
- Website: [vsis.net](https://vsis.net)
- Doc: [doc.vsis.net](https://doc.vsis.net)

## 📜 License

[Mozilla Public License 2.0](./LICENSE)
