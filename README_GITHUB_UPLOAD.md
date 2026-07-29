# Dochoithuvi-Pro v6.8.6 FinalGate Fix2 Watchdog

## 1. Tạo GitHub Release

Tạo tag chính xác:

`v6.8.6-finalgate-fix2`

Upload duy nhất file release asset:

`Dochoithuvi-Pro_v6.8.6_FinalGate_MicroShield_RC1_Fix2_Watchdog_GitHub_Public.zip`

SHA-256:

`5576a171d14ab07fa2b1403337223ea93e1fd082f383048b84cbc0f6ebb7a778`

## 2. Cập nhật nhánh main

Đưa hai file sau vào thư mục gốc của nhánh `main`:

- `manifest.txt`
- `manifest.sig`

Secure updater đang đọc:

- `https://raw.githubusercontent.com/thanhnguyenacc92-commits/dochoithuvi-pro/main/manifest.txt`
- `https://raw.githubusercontent.com/thanhnguyenacc92-commits/dochoithuvi-pro/main/manifest.sig`

## 3. Không được upload

Không upload private signing key hoặc OWNER KEEP PRIVATE ZIP. Upload pack này
không chứa private key. `update_public_rsa3072.pem` chỉ là public key để audit.

## 4. Đường nâng cấp

Bản Fix1 có OTA version 8.2 có thể cập nhật online lên Fix2 version 8.3.
Các bản cũ hơn 8.2 nên cài ZIP thủ công một lần.
