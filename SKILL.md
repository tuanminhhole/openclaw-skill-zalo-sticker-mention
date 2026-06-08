---
name: zalo-sticker-mention
description: Tự động tag người gửi trong group chat Zalo và gửi sticker theo từ khóa.
---

## Tự động Tag và gửi sticker Zalo

- **Trong group chat Zalo (Tự động Tag)**: Hệ thống tự động tag người gửi tin nhắn gần nhất bằng cách chèn `@Tên` ở đầu câu trả lời. AI không cần tự chèn `@Tên` của người gửi ở đầu câu nữa (hệ thống tự làm). Nhưng nếu muốn nhắc đến một người khác hoặc tag ở giữa câu, hãy viết `@TênHiểnThị`.

## 🎭 Rules sử dụng Sticker Zalo

Để câu trả lời thêm phần sinh động và cà khịa tự nhiên, AI có thể gửi kèm Sticker Zalo bằng cách viết mã `[Sticker: <từ_khóa>]` ở **CUỐI** tin nhắn.

Cơ chế hoạt động: Zalo sẽ tự động tìm kiếm sticker theo `<từ_khóa>` và gửi đi. Hãy sử dụng từ khóa ngắn gọn, rõ ràng bằng tiếng Việt hoặc tiếng Anh phù hợp với ngữ cảnh và cảm xúc hiện tại.

Ví dụ các từ khóa gợi ý:

- `love` hoặc `ôm tim` (khi cảm ơn, bắn tim, thể hiện tình cảm)
- `ca khia` hoặc `leu leu` (khi cà khịa, lêu lêu trêu chọc user)
- `haha` (khi cười vui vẻ, đập bàn cười)
- `khóc` hoặc `sad` (khi buồn bã, khóc ròng, tội nghiệp)
- `tuc gian` hoặc `angry` (khi tức giận, bị trêu chọc)
- `thank you` (khi cảm ơn hoặc chào tạm biệt)
- `hi` hoặc `chào` (khi bắt đầu trò chuyện)

_Lưu ý: Chỉ chèn tối đa 1 Sticker ở cuối tin nhắn khi thực sự phù hợp với ngữ cảnh (ví dụ chào hỏi, lêu lêu, khóc lóc hoặc cà khịa). Không lạm dụng._

## 🛠️ LỆNH THỰC THI (PATCH)

Để cài đặt bản vá hỗ trợ Sticker & Auto-Tag cho Zalo, hãy chạy lệnh sau:
`node skills/zalo-sticker-mention/mentions.js`

Để hoàn tác (restore) bản vá:
`node skills/zalo-sticker-mention/mentions.js --restore`

## Related
- [Hành động](../../TOOLS.md)
