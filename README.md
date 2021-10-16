## Thông Tin
bot discord music được remake chạy trên repl.it 24/24 bằng uptimerobot và việt hóa bởi Nguyễn Duy An từ phiên bản git gốc
https://github.com/eritislami

## cài đặt

1. cách lấy token discord **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. cách lấy api youtube v3 **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
3. SoundCloud không cung cấp API nữa**
4. Hỗ trợ Node.js v12.0.0 hoặc mới hơn
```
gõ (npm i) vào console
```
Sau khi cài đặt xong, bạn có thể sử dụng `node index.js` để khởi động bot.

🚨🚨 **không share token discord cho bất kì ai, với bất kì lý do nào** 🚨🚨

```
vào config.json
{
  "TOKEN": "", lấy token discord của bạn và  dán vào
  "YOUTUBE_API_KEY": "", lấy api youtube v3 của bạn
  "SOUNDCLOUD_CLIENT_ID": "", không cần
  "MAX_PLAYLIST_SIZE": 10, không cần
  "PREFIX": "/", đổi dấu lệnh
  "PRUNING": false, không cần
  "STAY_TIME": 30, không cần
  "LOCALE": "vi_VN", có thể đổi sang ngôn ngữ khác
  "support_server": "", không cần
  "DEFAULT_VOLUME": 100 không cần
}
```

## Ngôn Ngữ
Các ngôn ngữ hiện có sẵn là:

• English (en)
• French (fr)
• Spanish (es)
• Turkish (tr)
• Korean (ko)
• Brazilian Portuguese (pt_br)
• Simplified Chinese (zh_cn)
• Vietnam (vi_VN) việt hóa bởi Nguyễn Duy An
## 📝 Tính năng & Lệnh

> Note: prefix mặc định là '/'

* 🎶 sử dụng YouTube Url

`/play https://www.youtube.com/c/Vevo`

* 🔎 Phát nhạc qua Tên

`/play FatRat Fire`

* 🔎 tìm nhạc

`/search Imperial March Trap Remix by Goblins from Mars`

