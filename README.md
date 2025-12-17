# AndroidBackupADB
Tools For Copy File From Android Without Using MTP Copy. It Using Android Debugging Bridge For Faster Transfering Rate


#### Commandnya
    PortableDevicesIncrementalCopy.exe "S23 FE Milik Mahmud" IgnoreSize Excl *cache*\  Excl *files*\ Excl *Stickers*\  *1849125221-PEMANGGILAN*.pdf
### Penjelasan Commandnya
  |Command|Deskripsi|
  |------|----------|
  |"S23 FE Milik Mahmud"|Nama Folder Penyimpanan|
  |IgnoreSize|Jika File Sudah ada di SKip|
  |Excl *cache*\ |Mengecualikan Folder cache|
  |Excl *files*\ |Mengecualikan Folder files|
  |Excl *1849125221-PEMANGGILAN*.pdf |Mengecualikan file yang ada kata *1849125221-PEMANGGILAN*.pdf ber ekstensi .pdf|


#### Command Seharusnya
    PortableDevicesIncrementalCopy.exe "S23 FE Milik Mahmud" IgnoreSize Excl *cache*\ *files*\ *Stickers*\ *1849125221-PEMANGGILAN*.pdf *0824054001013000-04002500348910545*.pdf *Kurasi*.pdf
