## Phần 1

**1.** chrome lưu mật khẩu mà không có master password, khóa giải mã nằm ngay trên máy. infostealer copy file Login Data và giải mã được hết, nên mất cả github, aws, stripe.

**2.** zero-knowledge là server không biết mật khẩu của mình. dữ liệu được mã hóa aes-256 và giải mã ngay trên máy mình (client-side). server bitwarden bị hack thì két vẫn không bị giải mã, vì hacker chỉ lấy được dữ liệu đã mã hóa, không có khóa.

## Phần 2

**3.** chọn 4 đến 5 từ ngẫu nhiên, nối bằng dấu gạch, thêm 1 số. dài từ 20 ký tự, dễ nhớ nhưng máy vét cạn rất lâu.
ví dụ: `Purple-Tiger-Eats-9-Green-Moon`

**4.**

| mục | cấu hình |
|---|---|
| độ dài | 24 (tài khoản quan trọng 32) |
| chữ hoa, chữ thường | bật |
| số | bật, ít nhất 2 |
| ký tự đặc biệt | bật, ít nhất 2 |
| tránh ký tự dễ nhầm | bật |

**5.** auto-fill chỉ điền khi tên miền khớp chính xác với tên miền đã lưu. githúb.com hay steampowered.xyz khác tên miền nên không điền, còn người thì dễ nhìn nhầm.

**6.** in emergency kit ra giấy (email, master password, mã khôi phục), bỏ phong bì niêm phong, trưởng nhóm cất trong két sắt. bật emergency access cho trưởng nhóm. không lưu file trên máy.