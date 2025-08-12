# LAB-3
Selasa 12 Agustus 2025

# Blank Configuration di Mikrotik  
  Untuk mengakses Mikrotik yang blank, kita bisa mengakses melalui ether1. Dan kita harus mengunakan MACAddress untuk login, karna Mikrotik belum memiliki IP. Untuk mendapat blank configuration di Mikrotik ada beberapa cara,  
  **1. Reset Configuration**  
    Reset configuration bisa mendapatkan blank configuration, caranya, dengan men-checklist bagian **No Default Configuration**  
    ![nodef](ros.PNG)  
  **2. Reset Configuration di tampilan awal**  
    Bisa juga di Reset Configuration saat opo up awal memakai Default Configuration  
    ![yauda](reset.PNG)  
# Blank konfigurasi**  
  Pada konfigurasi blank ini, kita bisa lihat bahwa:  
  **2. Interface WLAN Mati/Disable**  
  **3. Addresses Kosong**
    Jadi untuk login ke Mikrotik harus mengunakan MAC Address, karna IP Addressnya belum di set.
  **4. Firewall kosong**
# Kesimpulan  
  Blank configuration sangat cocok untuk yang ingin memulai mikrotik bersih/kosong dan bisa mengakses mengunakan ether1 karna belum terkonfigurasi sebagai WAN.  
    
