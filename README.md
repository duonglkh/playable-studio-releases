# 🎮 Playable Studio

Công cụ desktop dựng **playable ad HTML5 một-file** từ brief — cho team UA, **không cần biết code**. App lái AI coding CLI (Claude / Codex) chạy ngầm sinh playable theo chuẩn từng network, tự **kiểm tra (validate + responsive)** và cho **xem thử / chỉnh sửa** ngay trong app.

## ⬇️ Tải về

👉 **[Tải bản mới nhất »](../../releases/latest)**

| Hệ điều hành | File | Ghi chú |
|---|---|---|
| **Windows 10/11 (64-bit)** | `PlayableStudio-Setup.exe` | Trình cài — khuyên dùng |
| Windows (không cài) | `PlayableStudio-portable.zip` | Giải nén → chạy `PlayableStudio.exe` |
| **macOS (Apple Silicon)** | `PlayableStudio.dmg` | Mở → kéo app vào Applications |

## 📦 Cài đặt

### Windows
1. Tải `PlayableStudio-Setup.exe` → chạy.
2. Nếu SmartScreen báo *"Windows protected your PC"* → **More info → Run anyway** (app chưa mua chứng chỉ ký số — vẫn an toàn).
3. Mở **Playable Studio** từ Start Menu / Desktop.

### macOS (chip Apple M1/M2/M3…)
1. Tải `PlayableStudio.dmg` → mở → **kéo icon app vào thư mục Applications**.
2. Lần đầu mở bị chặn: **chuột phải vào app → Open → Open**. (Hoặc *System Settings → Privacy & Security → "Open Anyway"*.)

## 🚀 Dùng lần đầu — 3 bước

1. **Cài AI CLI** (nếu máy chưa có): mở app → bấm nút **"⬇️ Cài Claude CLI"** ở góc trên. *(Muốn dùng ChatGPT: đổi provider sang Codex rồi cài Codex CLI — cần Node.js.)*
2. **Đăng nhập**: ⚙️ **Cài đặt → Tài khoản → Đăng nhập**.
   - **Claude** → trình duyệt mở → đăng nhập Claude.ai → tự hoàn tất.
   - **Codex** → terminal hiện **1 link + 1 mã** → mở link, đăng nhập ChatGPT, **nhập mã**.
   - Xong bấm **"Kiểm tra lại"**.
3. **Chọn Model** (tiết kiệm chi phí): ⚙️ Cài đặt → Tài khoản → **Model = Sonnet** (rẻ ~5× so với Opus).

## 🧩 Yêu cầu tài khoản

| AI | Cần gói | Đăng ký |
|---|---|---|
| **Claude** (mặc định) | **Claude.ai Pro hoặc Max** — *Free không dùng được* | https://claude.ai |
| **ChatGPT (Codex)** | **ChatGPT Plus/Pro** + Node.js | https://chatgpt.com · https://nodejs.org |

> Đăng nhập bằng **gói thuê bao** = không tính tiền theo token, nhưng có **giới hạn theo cửa sổ 5 giờ / tuần**. Cần volume lớn → Claude **Max** hoặc **API key**.

## ✨ Tạo playable (tóm tắt)

1. **➕ Tạo dự án mới** → nhập **Tên app** + **Brief** (mô tả: flow, end card, link store…).
2. Chọn **Network đích** (Mintegral / Unity / TikTok / Google AdMob/AdWords…).
3. Chọn **Nguồn thiết kế**: **Figma** (đọc qua MCP) · **Storyboard** (ảnh từng màn) · **Tự động**.
4. *(Tùy chọn)* **📋 Phân tích brief** — xem AI chia màn + "cần bổ sung" trước khi tạo.
5. **⚡ Tạo Playable** → đợi → **👁 Xem thử** → **✏️ Chỉnh sửa thêm** nếu chưa ưng.
6. File kết quả ở thư mục output của dự án — bấm **📂 Mở thư mục**.

Mỗi dự án được **lưu lại** → mở lại chỉnh sửa tiếp, không phải nhập lại từ đầu.

## ❓ Xử lý sự cố nhanh

- **Nút "⚡ Tạo" bị xám** → chưa đăng nhập, hoặc còn thiếu Tên app / Brief / Network.
- **Login Codex "không xong"** → phải **nhập đúng MÃ** trong terminal vào trang web đăng nhập, rồi bấm **"Kiểm tra lại"**.
- **Báo hết hạn mức** → gói thuê bao giới hạn theo cửa sổ 5h/tuần → đợi reset hoặc nâng gói.
- **Xem thử trống/lỗi** → một số network (Unity) chèn SDK lúc chạy thật, xem thử có thể thiếu — bản tải lên network vẫn đúng.

---

*Bản cài chưa ký số nên lần đầu mở sẽ có cảnh báo "unknown publisher" (Windows) / Gatekeeper (macOS) — bình thường.*

**© duonglkh (Hidev)**
