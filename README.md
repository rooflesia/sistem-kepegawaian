# 🚀 Employee & Attendance Management System (Laravel 8 + Blade)

Sistem Manajemen Kepegawaian (HRM) berbasis **Laravel 8 + Blade**, yang dirancang untuk **mengelola pegawai, absensi, cuti, lembur, payroll, keuangan, dan evaluasi kinerja pegawai dalam satu sistem**. Sistem ini dilengkapi dengan **role-based access control (RBAC), absensi berbasis QR Code, serta fitur laporan & notifikasi real-time**.


## 🎯 **Key Features**
### 🔹 **Authentication & Role Management**
✅ Laravel Sanctum (API Authentication)  
✅ RBAC (Role-based Access Control) dengan Spatie  
✅ Multi-role: Admin, HRD, Karyawan, Supervisor, Manajer  
✅ 2FA Authentication (opsional)  
✅ Switch User untuk multi-akun  

### 🔹 **Employee & HR Management**
✅ CRUD Pegawai, Jabatan, Golongan, & Kontrak  
✅ Manajemen Pegawai Keluar (Resign/PHK)  
✅ Profil Pegawai & Self-service Dashboard  

### 🔹 **Attendance & Shift Management**
✅ Absensi Harian berbasis QR Code & Geolocation  
✅ AutoShift & Pengaturan Shift Kerja  
✅ Approval Absen, Dinas Luar, & Pengajuan Cuti  
✅ Patroli & Monitoring Pegawai di Lapangan  

### 🔹 **Leave & Overtime Management**
✅ Manajemen Cuti & Reset Cuti  
✅ Lembur & Approval Lembur oleh Supervisor  
✅ Tracking Dinas Luar & Pengajuan Izin  

### 🔹 **Payroll & Financial Management**
✅ Perhitungan Gaji Otomatis  
✅ Kasbon, Reimbursement, & Status PTKP  
✅ Payroll Slip (Download PDF & Email)  
✅ Pajak PPh 21 & Perhitungan THR  

### 🔹 **Reporting & Export Data**
✅ Laporan Kehadiran & Absensi Karyawan  
✅ Export Data ke Excel & PDF  
✅ Laporan Kinerja Pegawai  

### 🔹 **Event, Meeting, & Task Management**
✅ Manajemen Rapat & Penugasan  
✅ Manajemen Kunjungan & Agenda Kerja  

### 🔹 **Notifications & Communication**
✅ Live Notification dengan Pusher  
✅ Notifikasi Approval Cuti, Lembur, & Absensi  
✅ Pemberitahuan Otomatis via Email & SweetAlert  

---

## 🛠 **Tech Stack**
### 🔹 **Backend**
- Laravel 8 (PHP 7.3+)
- Laravel Sanctum (API Authentication)
- Spatie Permissions (RBAC)
- MySQL
- Redis (Queue & Caching)
- GuzzleHTTP (API Requests)

### 🔹 **Frontend**
- Blade Template Engine
- Bootstrap 5 
- Livewire (opsional)
