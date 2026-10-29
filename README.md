# UpdateSNC - Snapchat Auto Reg Online Update Repository

Kho luu tru ban cap nhat truc tuyen cho cong cu Snapchat Auto Reg ADB.

- **Phien ban:** v1.5.1
- **Ngay phat hanh:** 2026-10-29
- **Tieu de:** Ban cap nhat v1.5.1 - Auto-Healing Watchdog tu dong phuc hoi View khong can ket noi bang tay

### Noi dung cap nhat:
- Tich hop Auto-Healing Watchdog: tu dong phat hien man hinh bi mat ket noi/den man hinh khi may online va tu dong Reconnect sau 7s ma KHONG CAN CHAT TAY
- Fail-Fast: tu dong giai phong ngay tien trinh scrcpy khi bi dut stream ket noi tu MiChanger/ADB de lap tuc phuc hoi
- Cho Android InputService san sang truoc khi bat Scrcpy de xoa bo 100% loi ServiceNotFoundException sau khi reboot
- Xoay vong dai cong TCP va don sach adb reverse tranh xung dot voi MiChanger
