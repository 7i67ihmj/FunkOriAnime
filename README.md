<div align="center">
  <img src="public/logo.png" alt="LuanOri MrFunk" width="120" />
  <h1> LuanOri LuanOri MrFunk</h1>
  <p><b>Xem anime và donghua có phụ đề tiếng Indonesia — tại một nơi, từ tất cả các nhà cung cấp.</b></p>

  ![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
  ![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)
  ![Vercel](https://img.shields.io/badge/Deployed-Vercel-000?logo=vercel)
  ![License](https://img.shields.io/badge/License-MIT-green)
  [![Trakteer](https://img.shields.io/badge/Trakteer-Donasi-red?logo=buymeacoffee&logoColor=white)](https://teer.id/anrizz)

  <br/>
  <a href="https://FunkOriAnime.vercel.app"><b>🌐 Live Site</b></a> &nbsp;·&nbsp;
  <a href="https://fb.com/LuanOri"><b>☕ Trakteer</b></a> &nbsp;·&nbsp;
  <a href="https://fb.com/LuanOri"><b>🐛 Report Bug</b></a>
</div>

---

## Đây là gì?

LuanOri MrFunk lấy dữ liệu từ nhiều nhà cung cấp anime (Otakudesu, Samehadaku, v.v.) thông qua một API duy nhất và hiển thị tất cả trên một trang web thân thiện với người dùng. Vì vậy, bạn không cần phải mở nhiều trang web để tìm anime.

Các tính năng chính:

- **Hỗ trợ nhiều nhà cung cấp** — tự động chuyển đổi nếu một máy chủ gặp sự cố
- **Phim hoạt hình** — không chỉ anime, mà còn cả phim hoạt hình
- **Tiếp tục xem** — lưu tiến trình đến phút và giây cuối cùng
- **Không cần đăng nhập** — sử dụng ngay, không rắc rối

## Ảnh chụp màn hình

> _sắp ra mắt_

## Công nghệ

| | |
|---|---|
| Giao diện người dùng | React 19 + Vite 8 |
| Định tuyến | React Router v7 |
| Lưu trữ | Vercel (không máy chủ) |
| Dữ liệu | [API Sankavollerei](https://luanori.com) |
| Ủng hộ | [API Trakteer](https://fb.com/LuanOri) |

## Chạy cục bộ

```bash
git clone https://github.com/7i67ihmj/FunkOriAnime.git
cd FunkOriAnime
npm install
npm run dev
```
Bản dựng sản phẩm:

```bash
npm run build
```

## Cấu trúc

```
src/
├── components/ # tất cả các trang & thành phần
├── contexts/ # ngữ cảnh chủ đề
├── hooks/ # useDebounce, useInfiniteScroll
├── services/ # api.js (tìm nạp + bộ nhớ cache + giới hạn tốc độ)
├── utils/ # xem lịch sử (localStorage)
└── main.jsx # điểm vào
```

## Các tính năng đầy đủ

- 🔍 Tìm kiếm kết hợp (Otakudesu + Samehadaku)
- 📺 Phát trực tuyến đa máy chủ với bộ chọn chất lượng
- 🐉 Phim hoạt hình (đang chiếu, đã hoàn thành, thể loại, A-Z)
- 📅 Lịch phát sóng hàng ngày
- 🎭 Duyệt thể loại từ 2 nhà cung cấp
- 🔤 Danh sách A-Z (anime & donghua)
- 🕐 Lịch sử xem + tiếp tục từ phút cuối
- ☕ Quyên góp qua Trakteer + bảng xếp hạng người quyên góp hàng đầu
- 🛡️ Tích hợp chống quảng cáo cho iframe phát trực tuyến
- 📱 Tương thích (điện thoại, máy tính bảng, máy tính để bàn)
- 🎨 Chủ đề tối + giao diện người dùng màu tím theo phong cách tân Brutalism

## Nguồn

- **API** — [Sankavollerei](https://luanori.com) (miễn phí, giới hạn 50 yêu cầu/phút)

- **Quyên góp** — [Trakteer](https://fb.com/LuanOri)

- **Biểu tượng** — Emoji gốc

## Hỗ trợ Dự án này

LuanOri MrFunk là phần mềm mã nguồn mở miễn phí. Nếu bạn thích và muốn giúp trang trải chi phí máy chủ và tên miền:

[![Trakteer](https://img.shields.io/badge/Trakteer-Donasi_sekarang-red?style=for-the-badge&logo=buymeacoffee&logoColor=white)](https://fbcom/LuanOri)

Hoặc chỉ cần đánh dấu sao cho kho lưu trữ này — đó cũng là một sự giúp đỡ lớn.

## Tuyên bố miễn trừ trách nhiệm

Dự án này dành cho mục đích giáo dục. Tất cả nội dung anime được cung cấp bởi bên thứ ba; LuanOri MrFunk không lưu trữ bất kỳ tệp video nào.

---

<div align="center">

<sub>Được tạo ra bằng 💜 bởi <a href="https://github.com/LuanOri">LuanOri</a></sub>

</div>
