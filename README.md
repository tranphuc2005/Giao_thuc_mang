# **Tài liệu các giao thức mạng: TCP, UDP, ARP, DHCP, ICMP**

## **1. Giới thiệu**
Giao thức mạng là nền tảng quan trọng cho việc trao đổi dữ liệu giữa các thiết bị. Dưới đây là mô tả ngắn gọn về các giao thức:

- **TCP (Transmission Control Protocol)**: Giao thức đảm bảo truyền dữ liệu đáng tin cậy qua mạng.
- **UDP (User Datagram Protocol)**: Giao thức không kết nối, nhanh hơn nhưng không đảm bảo độ tin cậy.
- **ARP (Address Resolution Protocol)**: Chuyển đổi địa chỉ IP sang địa chỉ MAC.
- **DHCP (Dynamic Host Configuration Protocol)**: Tự động cấp phát địa chỉ IP cho thiết bị trong mạng.
- **ICMP (Internet Control Message Protocol)**: Được sử dụng để kiểm tra trạng thái của kết nối mạng và chẩn đoán lỗi.

---

## **2. Hướng dẫn cài đặt**
### **Môi trường yêu cầu**:
- Hệ điều hành hỗ trợ TCP/IP (Linux, Windows, macOS).
- Công cụ dòng lệnh như `ping`, `traceroute`, `arp`, `ipconfig`, hoặc `ifconfig`.

### **Cài đặt các công cụ kiểm tra**:
1. Trên Linux:
   ```bash
   sudo apt update
   sudo apt install net-tools iputils-ping traceroute
