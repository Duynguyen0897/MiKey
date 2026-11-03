# MiKey

Bộ gõ tiếng Việt Telex cho người Việt ở Thụy Sĩ, Đức và Áo.

**[mikey.mikephung.com](https://mikey.mikephung.com)**

## Vấn đề

Telex thường không biết bạn đang viết tiếng gì:
- `text` → `tẽt`
- `über` → `ơber`
- `wir` → `ửi`

MiKey tự nhận ra tiếng Anh và tiếng Đức, giữ nguyên các từ đó.

## Tính năng

- **Telex** với đặt dấu hiện đại hoặc cổ điển (hoà / hòa)
- **Tự chuyển:** Nhận biết khi bạn gõ tiếng Anh hoặc tiếng Đức
- **Phím ä ö ü ß:** Gõ thẳng, không bị Telex làm hỏng (über, Grüße, Café)
- **~30.000 từ tiếng Đức:** wir, der, nur, dass, wissen giữ nguyên
- **~40.000 từ tiếng Anh:** text, server, deploy, osx giữ nguyên
- **Backspace hoàn tác:** Bấm ngay sau từ bị sửa để lấy lại đúng phím đã gõ

## Cài đặt

Tải bản mới nhất từ [Releases](https://github.com/mikephung/MiKey/releases).

**macOS 13+:** Mở file .dmg, kéo MiKey vào thư mục hiện ra. Lần đầu cần đăng xuất/đăng nhập lại.

## Phím Telex

| Phím | Kết quả |
|------|---------|
| aa | â |
| aw | ă |
| ee | ê |
| oo | ô |
| ow | ơ |
| uw | ư |
| dd | đ |
| s | sắc (´) |
| f | huyền (`) |
| r | hỏi (?) |
| x | ngã (~) |
| j | nặng (.) |
| z | bỏ dấu |

## Build từ source

Yêu cầu Xcode và [XcodeGen](https://github.com/yonaskolb/XcodeGen).

```sh
xcodegen generate
xcodebuild -project MiKey.xcodeproj -scheme MiKey -configuration Release build
```

## Ghi công

MiKey được fork từ [Vikey](https://github.com/trungdq88/Vikey) của [Tony Dinh](https://tonydinh.com), dựa trên [OpenKey](https://github.com/tuyenvm/OpenKey) của Tuyen Mai.

## Giấy phép

GNU General Public License v3.0. Xem [LICENSE](LICENSE).
