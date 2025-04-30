# OpenStack
<img src="https://github.com/user-attachments/assets/47a04ec4-4526-435e-8cec-66b7c3df1984" alt="Description" width="500"/>

## Giới thiệu 
OpenStack là một nền tảng phần mềm mã nguồn mở được sử dụng để xây dựng và quản lý các môi trường điện toán đám mây (cloud computing). Nó cung cấp một bộ công cụ cho phép các tổ chức triển khai các dịch vụ như hạ tầng dưới dạng dịch vụ (IaaS - Infrastructure as a Service), nơi người dùng có thể tạo, quản lý và sử dụng tài nguyên như máy ảo, lưu trữ, và mạng thông qua giao diện web hoặc API.

OpenStack được xây dựng từ nhiều dự án con, mỗi dự án đảm nhiệm một chức năng cụ thể. Dưới đây là các thành phần chính:
1. Nova (Compute)
   * Quản lý máy ảo (VM) và các tài nguyên tính toán.
   * Hỗ trợ các hypervisor phổ biến như KVM, VMware, Xen, và Hyper-V.
2. Neutron (Networking)
   * Cung cấp khả năng quản lý mạng ảo, định tuyến, cân bằng tải, và tường lửa.
   * Cho phép cấu hình mạng linh hoạt cho các máy ảo.
3. Cinder (Block Storage)
   * Cung cấp dịch vụ lưu trữ dạng khối (block storage).
   * Thích hợp để lưu trữ dữ liệu liên tục hoặc sử dụng làm ổ đĩa cho máy ảo.
4. Swift (Object Storage)
   * Cung cấp lưu trữ đối tượng (object storage) để lưu trữ dữ liệu phi cấu trúc, như tệp, hình ảnh, hoặc bản sao lưu.
5. Glance (Image Service)
   * Quản lý và lưu trữ các image (hệ điều hành) được sử dụng để tạo máy ảo.
   * Hỗ trợ nhiều định dạng image như RAW, VHD, VMDK.
6. Keystone (Identity Service)
   * Quản lý xác thực và phân quyền cho người dùng.
   * Cung cấp dịch vụ nhận dạng và hỗ trợ xác thực đa yếu tố.
7. Horizon (Dashboard)
   * Giao diện web để quản lý tài nguyên OpenStack một cách trực quan.
   * Dành cho quản trị viên và người dùng.

## Cài đặt
ss
