# PHẦN 1 – HYBRID WORKFLOW

**1.** Nếu file đã được Auto Sync lên Cloud thì laptop hỏng ổ cứng vẫn không mất dữ liệu. Nếu chưa đồng bộ xong, file mới nhất có thể bị mất.

**2. Ba bước thiết lập Auto Sync:**
1. Cài ứng dụng Cloud Drive và đăng nhập.
2. Chọn thư mục dự án SmartCampus và bật Auto Sync.
3. Kiểm tra trạng thái đồng bộ hoàn tất.

**3.** Mở file → `Version History` → chọn phiên bản trước khi xóa → khôi phục hoặc sao chép lại nội dung bị mất.

**4.**
- `node_modules`: Quá nhiều file nhỏ, gây chậm đồng bộ → loại trừ khỏi Cloud.
- Phim 4K: Dung lượng lớn, không phục vụ dự án → không đồng bộ.

# PHẦN 2 – PHÂN QUYỀN CHIA SẺ

**1. Bảng phân quyền**

| File | Mức quyền | Phạm vi | Lý do |
|---|---|---|---|
| `BaoCao_CuoiKy_SmartCampus.docx` | Viewer | Restricted | Giảng viên xem, không sửa. |
| `Slide_BaoCao.pptx` | Editor | Restricted | 5 thành viên cùng chỉnh sửa. |
| `GopY_BanNhap.docx` | Commenter | Restricted | Chỉ góp ý, không sửa trực tiếp. |
| `ThongTin_CaNhan_NhomVien.xlsx` | Viewer | Restricted | Bảo vệ thông tin cá nhân. |

**2. Quy tắc Cờ Đỏ Bảo mật:** Dữ liệu nhạy cảm phải giới hạn người truy cập. Không kết hợp `Anyone with the link` + `Editor` vì người có liên kết có thể truy cập và sửa đổi dữ liệu.

**3. Hai thao tác trong Settings:**
- Tắt quyền Editor chia sẻ hoặc thay đổi quyền truy cập.
- Bật thông báo hoạt động chia sẻ nếu nền tảng hỗ trợ.

# PHẦN 3 – GIAO TIẾP NHÓM

**1. Ba vấn đề:**
- **No-Hello:** Hỏi chung chung, thiếu ngữ cảnh.
- **Spam @all:** Nhắc việc lúc 23:47, ảnh hưởng giờ nghỉ.
- **Thiếu phân luồng:** Tin công việc lẫn với tin nhắn giải trí.

**2. Các Channel nên tạo:**
- `#thong-bao`: Deadline và thông báo quan trọng.
- `#du-an-smartcampus`: Trao đổi công việc và tiến độ.

**3. Viết lại tin nhắn của Lan:**

> Mọi người ơi, mình đang hoàn thiện báo cáo SmartCampus nhưng gặp khó khăn ở phần mô tả chức năng hệ thống. Bạn nào có kinh nghiệm giúp mình góp ý cách trình bày nhé. Mọi người phản hồi khi thuận tiện, mình cảm ơn!

**4. Tin nhắn Schedule Send lúc 08:00 ngày hôm sau:**

> Chào Nam và Hoa, hai bạn vui lòng hoàn thiện phần việc còn thiếu trước 10:00 hôm nay. Nếu gặp khó khăn, hãy phản hồi tại thread này để nhóm hỗ trợ nhé. Cảm ơn hai bạn!

*Lưu ý: Gắn thẻ đúng tài khoản Nam và Hoa, không dùng `@all`.*

# PHẦN 4 – THÔNG BÁO TỔNG HỢP

Đăng lên kênh `#thong-bao`:

> **[THÔNG BÁO SMARTCAMPUS]**
>
> Mình đã bật Auto Sync cho thư mục dự án để hạn chế mất dữ liệu. File `BaoCao_CuoiKy_SmartCampus.docx` đã được chia sẻ cho giảng viên với quyền **Viewer / Restricted**.
>
> **Nam và Hoa:** Vui lòng hoàn thiện phần việc còn thiếu trước 10:00 hôm nay và cập nhật tiến độ tại thread này.
>
> Mọi người nhớ kiểm tra trạng thái đồng bộ và chia sẻ file đúng quyền nhé!
