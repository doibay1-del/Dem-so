
# Đếm Số & Tính Tiền | Count & Calculate

## 🇻🇳 Tiếng Việt

**Đếm Số & Tính Tiền** là công cụ web gọn nhẹ giúp đếm các giá trị số hợp lệ và tính thành tiền theo đơn giá. Giao diện tương thích với điện thoại và máy tính. Khi được xuất bản trên website HTTPS, công cụ có thể được thêm vào màn hình chính dưới dạng PWA.

### Tính năng

- Nhập danh sách các giá trị cần đếm.
- Chỉ tính các giá trị số hợp lệ vào số lượng hợp lệ và thành tiền.
- Tính tổng tiền theo đơn giá do người dùng nhập.
- Giao diện phù hợp với điện thoại và máy tính.
- Có thể thêm biểu tượng vào màn hình chính trên iPhone và Android.
- Hỗ trợ lưu bộ ứng dụng để sử dụng ngoại tuyến sau khi các tệp đã được lưu thành công.

### Cài đặt và xuất bản miễn phí

1. Giải nén gói dự án.
2. Tạo một repository **Public** trên GitHub.
3. Tải toàn bộ tệp trong gói lên thư mục gốc repository.
4. Mở **Settings → Pages**.
5. Chọn **Deploy from a branch**, branch `main`, thư mục `/(root)`, rồi nhấn **Save**.
6. Chờ GitHub Pages xuất bản website và mở đường dẫn HTTPS được cung cấp.

### Cài lên điện thoại

- **iPhone:** Mở website bằng Safari → **Share** → **Add to Home Screen**.
- **Android:** Mở website bằng Chrome → menu `⋮` → **Install app** hoặc **Add to Home screen**.

### Kiểm tra nhanh

Nhập `10, 20, abc, 40` và đặt đơn giá `23000`.

Kết quả mong đợi:
- 4 phần tử đầu vào.
- 3 giá trị số hợp lệ.
- Thành tiền: `69.000 đ`.

### Lưu ý

- GitHub Pages hỗ trợ lưu trữ website tĩnh và HTTPS miễn phí.
- Repository Public cho phép người khác xem mã nguồn.
- Đây là PWA, không phải ứng dụng native được phát hành qua App Store hoặc Google Play.
- Khả năng sử dụng ngoại tuyến phụ thuộc vào việc các tệp ứng dụng đã được lưu thành công.

---

## 🇬🇧 English

**Count & Calculate** is a lightweight web tool for counting valid numeric values and calculating totals using a user-defined unit price. It works on mobile devices and desktop browsers and can be added to the home screen as a PWA when hosted on an HTTPS website.

### Features

- Enter a list of values to count.
- Only valid numeric values are included in the valid count and total.
- Calculate the total using a user-defined unit price.
- Responsive interface for mobile and desktop.
- Add an app icon to the home screen on iPhone and Android.
- Supports caching app files for offline reuse after they have been successfully stored.

### Free Deployment

1. Extract the project ZIP.
2. Create a **Public** repository on GitHub.
3. Upload all project files to the repository root.
4. Open **Settings → Pages**.
5. Select **Deploy from a branch**, choose branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site, then open the provided HTTPS URL.

### Install on Mobile

- **iPhone:** Open the website in Safari → **Share** → **Add to Home Screen**.
- **Android:** Open the website in Chrome → tap the `⋮` menu → **Install app** or **Add to Home screen**.

### Quick Test

Enter `10, 20, abc, 40` and set the unit price to `23000`.

Expected result:
- 4 input items.
- 3 valid numeric values.
- Total: `69,000 VND`.

### Notes

- GitHub Pages provides free hosting for static websites with HTTPS.
- A Public repository makes its source code visible to others.
- This is a PWA, not a native app distributed through the App Store or Google Play.
- Offline availability depends on successful caching of the application files.
