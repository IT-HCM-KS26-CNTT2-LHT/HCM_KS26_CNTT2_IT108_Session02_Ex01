Nguyên nhân : ram đầy do chrome nhiều tab/extension , VSCode kiểu electron , tiến trình nền, startup mà nhân (kernel) phải đẩy dữ liệu xuống swap file, đĩa quá tải nên máy giật lag .
Kernel và Shell: Shell nhận yêu cầu, Kernel điều phối CPU, RAM, đĩa.
IPO: Input là nhấp đúp file .exe trên Storage. Process là Kernel tạo process, cấp RAM, đọc đĩa vào RAM, cấp CPU. Output là cửa sổ ứng dụng chạy trong RAM.
End Task System: thường bị từ chối, nếu dừng được thì máy sập (BSOD).
SSD và HDD khi RAM đầy: SSD nhanh hơn nhiều khi swap nên chỉ giật nhẹ, HDD gây thrashing, đĩa 100%.
Sơ đồ: User → Shell → System call → Kernel → Hardware.
Giải pháp: đóng bớt tab, tắt startup, nâng RAM, dùng SSD.
