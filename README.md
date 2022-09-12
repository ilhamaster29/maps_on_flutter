# Laporan Praktikum

## 1. Membuat Project Baru
![sreenshot](images/project_baru_maps.png)
> _Project_ baru pada praktikum kali ini saya beri nama **maps_on_flutter** sama seperti nama _repository_ di github.

## 2. Menambahkan Plugin Google Maps Flutter sebagai Dependensi 
- Menjalankan perintah **flutter pub add google_maps_flutter** pada terminal untuk menambahkan plugin google maps.
![sreenshot](images/flutter_pub.png)

- Running **flutter pub add google_maps_flutter** di terminal
![sreenshot](images/perubahan_pubspec.yaml.png)
> Ketika perintah **flutter pub add google_maps_flutter** selesai dijalankan, akan terjadi perubahan pada file **pubspec.yaml**.

- Running **flutter pub add google_maps_flutter_web** di terminal
![sreenshot](images/flutter_pub_web.png)
> Menjalankan perintah **flutter pub add google_maps_flutter_web** pada terminal untuk menambahkan plugin google maps versi web.

- Perubahan file **pubspec.lock** dan **pubspec.yaml**
![sreenshot](images/perubahan_pubspec.lock.png)
![sreenshot](images/perubahan_pubspec.yaml_2.png)
> Ketika perintah **flutter pub add google_maps_flutter_web** selesai dijalankan, akan terjadi perubahan pada file **pubspec.lock** dan **pubspec.yaml**.

## 3. Mengonfigurasi minSDK Android
![sreenshot](images/min_sdk_android.png)
> Menetapkan minSDK ke 20.

## 4. Menambahkan Google Maps ke aplikasi
- _Generate_ API Key
![sreenshot](images/api_key.png)

- Menambahkan API key untuk aplikasi Android
![sreenshot](images/api_key_androidmanifest.xml.png)
> _Input_ API key pada file **AndroidManifest.xml**.
