# reportcallbot-new — Mockup Báo cáo & Dashboard Callbot (MAFC Happy Call)

Mockup nâng cấp màn **Báo cáo** của một phiên Callbot (OMICRM) theo yêu cầu **FR-030** cho dự án **MAFC VoiceBot Happy Call** — bổ sung góc quản trị vận hành.

## Nội dung
- `index.html` — mockup tương tác (tự chứa, mở bằng trình duyệt là chạy).
- `MAFC-BaoCao-Dashboard-FR030.html` — bản sao cùng nội dung (tên mô tả).

## Phần nâng cấp (đánh dấu viền vàng "NÂNG CẤP" + mã FR)
- **KPI vận hành**: Tổng hợp đồng / Đã gọi / Đang pending (+ thời gian) / Tỉ lệ kết nối / Hoàn thành xác minh / TAT — FR-030 (i)(ii), FR-033
- **Báo cáo theo Action Code & Reason Code** — bảng 2 tầng đầy đủ 16 mã (kèm Chuyển NV / Spin) — FR-030 (iii)
- **Theo trạng thái cuộc gọi** (RONA/NCON/voicemail…) — FR-030 (v), FR-009
- **Theo nhóm sản phẩm** (Tiền mặt / Trả góp / Dịch vụ)
- **Pending chi tiết** theo mốc thời gian — FR-033
- **Lịch sử theo Hợp đồng/SĐT + số lần gọi** — FR-030 (iv), FR-031

> Phạm vi: báo cáo mức **một phiên**. Số liệu trong mockup là minh họa. Giữ nguyên 4 sub-tab phân tích hội thoại hiện có của OMICRM.

## Xem online
Bật **GitHub Pages** (Settings → Pages → branch `main`) rồi mở `https://dnq98.github.io/reportcallbot-new/`.
