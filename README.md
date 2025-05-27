<h2>1. navigation</h2>
<img src ="https://github.com/user-attachments/assets/bdf8d38e-cd78-4f64-8209-8c62dc9e0705" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/6b05d648-6bc8-4c79-aabd-bc07bc1d3700" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/a0d1638c-1a8b-4ff4-9df2-59b74f67803f" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/33aa70ec-9c4c-4eb3-81c5-8ed2a8a78cff" width= "400px"><br>
<h2>Penjelsan</h2>
<h4>Aplikasi ini mendemonstrasikan navigasi antar layar (screen) di Flutter, menggunakan:<br>
1. Navigasi dasar (Navigator.push)<br>
2. Navigasi dengan named route (Navigator.pushNamed)<br>
3. Pengiriman data antar layar<br>
keterangan <br>
- Navigasi manual (MaterialPageRoute) cocok untuk kirim data langsung via konstruktor.<br>
- Named route (pushNamed) cocok untuk navigasi yang lebih terstruktur.<br>
- Data tambahan bisa dikirim via arguments.<br>
</h4>

<h2>2. deep_link_navigation</h2>
<img src ="https://github.com/user-attachments/assets/2cbdb76f-6f96-470d-b6d2-01041b0b1c74" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/be6cbab3-97af-42cc-bf71-9d50c949862c" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/f4980165-ceee-4a61-b8f6-4ab2f4bfe773" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/6ec7ff36-15a2-44d2-99ab-4831ff5c9f2e" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/fca67633-cdd4-48dc-9100-cf51a08aaeb3" width= "400px"><br>
<h2>Penjelsan</h2>
<h4>Kode ini menggunakan Flutter Router API untuk navigasi berbasis URL (deep linking). <br>
terdiri dari tiga layar: HomeScreen, DetailScreen, dan SettingsScreen.<br>
Saat URL seperti /, /detail/1, atau /settings diakses, parser (AppRouteInformationParser) mengubahnya menjadi objek RoutePath, lalu delegate (AppRouterDelegate) <br>
  menampilkan halaman yang sesuai dengan menggunakan Navigator. Di HomeScreen, pengguna bisa memilih item untuk melihat detailnya atau membuka halaman pengaturan. Navigasi antar halaman dilakukan tanpa context langsung, memungkinkan akses langsung via URL.<br>
</h4>

<h2>3. navigation_20</h2>
<img src ="https://github.com/user-attachments/assets/5571c474-8d0a-4512-840e-3da1e458e754" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/5106c4e6-d522-4fdb-aa5f-1f6df5566daf" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/4ccd790c-c3b3-43e4-bc91-3a33bc6a0b76" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/7ec3774d-d59b-4fcf-b89a-8bbd24a32db4" width= "400px"><br>
<h2>Penjelsan</h2>
<h4>Aplikasi Flutter ini menggunakan sistem navigasi deklaratif berbasis Navigator 2.0, di mana halaman-halaman ditentukan dalam <br>
  daftar pages yang disusun secara dinamis tergantung pada state aplikasi. Aplikasi menampilkan daftar item di HomeScreen, dan ketika <br>
  salah satu item dipilih, aplikasi akan memperbarui state _selectedItem lalu menampilkan DetailScreen untuk item tersebut. Di DetailScreen,<br>
  informasi detail seperti name, id, dan description ditampilkan. Navigasi kembali ke halaman utama (pop) juga akan membersihkan pilihan item dan menampilkan kembali HomeScreen.
</h4>

<h2>4. nested_navigation</h2>
<img src ="https://github.com/user-attachments/assets/7278916e-09b2-4ed3-80d0-e47ae3eaded6" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/464cf6d3-98d8-4ca3-a6b3-1ed811488b5a" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/62063d15-94ce-4615-812c-3ca11095d331" width= "400px"><br>
<img src ="https://github.com/user-attachments/assets/2a156c95-91b3-403d-8e45-71604ea5cf5d" width= "400px"><br>
<h2>Penjelsan</h2>
<h4>aplikasi Flutter yang menggunakan nested navigation untuk mengatur alur pengaturan perangkat. Aplikasi dimulai dari HomeScreen yang memiliki tombol<br>
  untuk memulai proses setup. Saat ditekan, pengguna diarahkan ke SetupFlowScreen yang berisi navigator bersarang. Dalam navigator ini, terdapat tiga <br>
  layar bertahap: FindDevicesScreen untuk mencari perangkat, ConfirmDeviceScreen untuk mengonfirmasi pilihan perangkat, dan ConnectDeviceScreen untuk<br>
  menyelesaikan proses koneksi. Transisi antar layar dikontrol menggunakan route names (pushNamed). Tombol "Back" disediakan untuk kembali ke layar sebelumnya,<br>
  dan tombol "Complete Setup" akan menutup alur dan kembali ke HomeScreen. Struktur ini berguna untuk membuat alur proses yang kompleks tetap terorganisir dengan baik.
</h4>

