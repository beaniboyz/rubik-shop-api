# Rubik Shop API

## Mục tiêu
Xây dựng backend cho shop bán Rubik, hỗ trợ khách mua và admin quản lý.

## Người dùng
- Khách hàng: xem sản phẩm, thêm giỏ, đặt hàng COD.
- Admin: quản lý sản phẩm, tồn kho và đơn hàng.

## Phạm vi bản 1.0
- Danh sách sản phẩm và chi tiết.
- Giỏ hàng.
- Đặt hàng COD.
- Quản lý tồn kho.
- Quản lý đơn hàng.
- Hủy đơn và hoàn tồn.
- Test, Docker Compose, CI.

## Chưa làm
- Thanh toán online.
- Voucher.
- Đánh giá.
- Redis.
- Nhiều kho.

## Quy tắc tồn kho
- Giỏ không giữ hàng.
- Đặt hàng thành công mới trừ tồn.
- Hủy trước khi giao mới hoàn tồn.
- Không cho bán vượt tồn.
