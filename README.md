# reportcallbot-new — Mockup Báo cáo Callbot (MAFC Happy Call)

Mockup màn **Báo cáo** của phiên Callbot (OMICRM) cho dự án **MAFC VoiceBot Happy Call** — cấu trúc **3 dashboard** theo góp ý đối tác (FR-030).

## Nội dung
- `index.html` — mockup tương tác (tự chứa, mở bằng trình duyệt là chạy).
- `MAFC-BaoCao-Dashboard-FR030.html` — bản sao cùng nội dung (tên mô tả).

## 3 Dashboard (chuyển tab)
1. **CDR — Lịch sử cuộc gọi** (mức cuộc gọi · 25 trường): ID cuộc gọi, Mã hợp đồng, SĐT, Đầu số gọi ra, Mã chiến dịch, CLI, Trạng thái, SIP, thời điểm bắt đầu/bắt máy/kết thúc, thời lượng gọi/đàm thoại, Call Result, Person Contacted, Action Code, Reason Code, số tiền/mục đích bóc tách, thời gian hẹn gọi lại, Transcript, Recording URL, số lần gọi, Spin, Human T+1.
2. **Theo Khách hàng** (mức KH · 12 trường): Họ tên, Mã KH, SĐT, Số lần gọi, **Last action code** (trạng thái kết thúc trong flow — nhiều cuộc lấy "xa" nhất theo thứ tự khai báo trong bộ trạng thái khách hàng), **Best action code** (trạng thái đánh dấu "best"; không có thì lấy Last) — cả hai gồm Action + Reason, ngày sinh, giới tính, loại SP, tên SP/DV, ngày giải ngân, số tiền giải ngân.
3. **Báo cáo Callbot (NLU)**: usersay (Speech-to-Text), intent, entity, độ tương thích intent/entity từng câu, WER (% sai STT), tốc độ phản hồi bot (≤ 3s) — bám NFR-001..004.

> Số liệu trong mockup là minh họa. Bộ trạng thái khách hàng (2 cấp Action/Reason, thứ tự + cờ "best") do đối tác khai báo ở module Khách hàng của OMI.

## Xem online
Bật **GitHub Pages** (Settings → Pages → branch `main`) rồi mở `https://dnq98.github.io/reportcallbot-new/`.
