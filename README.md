1. mengunduh program wget,unzip,xxd, membuat folder baru dan memasukan 
   "artists_who_can_sing”
   ```
   sudo apt install wget unzip xxd && mkdir  artists_who_can_sing && cd 
   artists_who_can_sing
   ```
2. mengunduh file 
   ```
   wget --no-check-certificate "https://docs.google.com/uc? 
   export=download&id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut" -O hana.zip

   ```
3. unzip ke folder singing_tutorials
   ```
   unzip hana.zip -d singing_tutorials
   ```
 4. memasukan kedalam folder dan menampilkan isi file yang tersembunyi 
    ```
    cd singing_tutorials/ && ls -la
    ```
 5. mencari file opera di buat oleh NBAYoungboy dan di masukan folder flag.txt
   ```
   find .*opera*NBAY* &&  strings .*opera*NBAY* | grep FLAG{ > flag.txt
   ```
 6. mundur ke directory sebelumnya dan download file baru dengan nama 
   plsrunmeiamnotmalwarefr
   ```
   cd .. &&  wget https://files.catbox.moe/9l4qu8 -O plsrunmeiamnotmalwarefr
   ```
 7. izin execute dan menjalankan program 
   ```
   chmod +x  plsrunmeiamnotma && ./plsrunmeiamnotma 
   ```
 8. melihat program yang di jalankan 
   ```
   ps aux 
   ```
 9. membuat sebuah file bernama ransom.moolah dan mengecek keadaan 
   ```
   touch ransom.moolah && ps aux
   ```
 10. mematikan proses program 
   ```
   kill -9 <PID>
   ```
 11. membuat user,set groups, dan login
   ```
   sudo adduser yabadabadoo && sudo usermod -aG sudo yabadabadoo && groups 
   yabadabadoo && su yabadabadoo
   ```
 12. membuat folder, dan set owner dan permassion
   ```
   ```
   13.a
   ```
   ```
   14.a
   ```
   ```
   15.a
   ```
   ```
   
