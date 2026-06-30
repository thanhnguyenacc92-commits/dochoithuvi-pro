HƯỚNG DẪN UPLOAD GITHUB - DOCHOITHUVI-PRO
=======================================

Repo cần upload:
https://github.com/thanhnguyenacc92-commits/dochoithuvi-pro

Upload toàn bộ file trong gói này lên nhánh main:

- Dochoithuvi-Pro_v4.4_ReportUploader_GitHubReady.zip
- manifest.txt
- manifest.sig
- blacklist.txt
- dochoithuvi_manifest_public.pem
- HUONG_DAN_UPLOAD_GITHUB.md

Raw URL đã cấu hình trong tool khách:

MANIFEST_URL:
https://raw.githubusercontent.com/thanhnguyenacc92-commits/dochoithuvi-pro/main/manifest.txt

MANIFEST_SIG_URL:
https://raw.githubusercontent.com/thanhnguyenacc92-commits/dochoithuvi-pro/main/manifest.sig

Sau khi upload xong, trên Kindle vào:
Dochoithuvi-Pro_v4.4 -> Cập nhật Online bảo mật -> Kiểm tra bản mới có chữ ký

Lưu ý:
- Không upload file SELLER_ONLY/private key lên GitHub public.
- Mỗi lần sửa manifest.txt phải ký lại manifest.sig bằng private key.
- Nếu chỉ sửa blacklist.txt thì không cần ký lại manifest.sig.
- Nếu ra bản mới, sửa version/url/sha256/note trong manifest.txt rồi ký lại manifest.sig.

SHA256 của tool GitHub-ready:
827706f60690d5f1099620704006a1637d6ad3e3000462ea0d8bf47e9ee96bbc
