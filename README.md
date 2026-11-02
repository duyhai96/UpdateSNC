# UpdateSNC - Snapchat Auto Reg Online Update Repository

Kho luu tru ban cap nhat truc tuyen cho cong cu Snapchat Auto Reg ADB.

- **Phien ban:** v1.8.6
- **Ngay phat hanh:** 2026-11-02
- **Tieu de:** Ban cap nhat v1.8.6 - Khac phuc triet de loi treo ung dung (Not Responding) va dong bo View sieu toc

### Noi dung cap nhat:
- Khac phuc triet de loi treo ung dung (Not Responding) do Watchdog va Scrcpy Reconnect chay tren UI thread
- Chuyen Watchdog kiem tra ket noi sang Background Thread khong chan giao dien WinForms
- Su dung ConcurrentDictionary O(1) thay cho viec duyet toan bo cay Controls cua flowScreens
- Loai bo spam ToolTip.SetToolTip tren luong UI tranh gay ngheo Windows API message queue
- Chuyen UpdateGridButton sang BeginInvoke bat dong bo tranh deadlock cross-thread
