# wastelesscms
This is cms for wasteless platform
# Dự án được kế thừa từ Wagtail CRX (Phần mở rộng CodeRed)

Tài liệu dùng để lập trình dự án này.

[Trang web](https://www.coderedcorp.com/cms/)
|

[Tài liệu](https://docs.coderedcorp.com/wagtail-crx/)
|
[Blog](https://www.coderedcorp.com/blog/tag/django-wagtail/)

## Trạng thái

| | |
|-----------------------|----------------------|
| Gói Python | [![PyPI - Phiên bản Python](https://img.shields.io/pypi/pyversions/coderedcms)](https://pypi.org/project/coderedcms/) [![PyPI - Phiên bản Django](https://img.shields.io/pypi/djversions/coderedcms)](https://pypi.org/project/coderedcms/) [![PyPI - Bánh xe](https://img.shields.io/pypi/wheel/coderedcms)](https://pypi.org/project/coderedcms/) [![PyPI - Tải xuống](https://img.shields.io/pypi/dm/coderedcms)](https://pypi.org/project/coderedcms/) [![PyPI](https://img.shields.io/pypi/v/coderedcms)](https://pypi.org/project/coderedcms/) |
| Xây dựng | [![Trạng thái bản dựng](https://dev.azure.com/coderedcorp/cr-github/_apis/build/status/coderedcms?branchName=main)](https://dev.azure.com/coderedcorp/coderedcms/_build/latest?definitionId=1&branchName=main) [![Kiểm tra Azure DevOps (nhánh)](https://img.shields.io/azure-devops/tests/coderedcorp/cr-github/1/main)](https://dev.azure.com/coderedcorp/cr-github/_build/latest?definitionId=1&branchName=main) [![Phạm vi bao phủ Azure DevOps (nhánh)](https://img.shields.io/azure-devops/coverage/coderedcorp/cr-github/1/main)](https://dev.azure.com/coderedcorp/cr-github/_build/latest?definitionId=1&branchName=main) |

## Hướng dẫn chạy dự án
1. Cấu hình db trong setting.py

2. Chạy `python manage.py migrate` để tạo các mô hình cốt lõi.

3. Chạy `python manage.py createsuperuser` để tạo người dùng quản trị ban đầu.

4. Chạy `python manage.py runserver` để khởi chạy máy chủ phát triển và truy cập `http://localhost:8000` trên trình duyệt của bạn, hoặc `http://localhost:8000/admin/` để đăng nhập bằng tài khoản quản trị của bạn.

Xem [tài liệu](https://docs.coderedcorp.com/wagtail-crx/) để biết các bước tiếp theo và cách tùy chỉnh trang web mới của bạn.


## Thông tin thêm

Các tệp biểu tượng trong `coderedcms/templates/coderedcms/icons/`:

* Được lấy từ dự án Fork Awesome tại
https://github.com/ForkAwesome/Fork-Awesome.
https://creativecommons.org/licenses/by/3.0/

* Đã được chỉnh sửa từ nguồn gốc.