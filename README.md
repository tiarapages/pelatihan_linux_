1. mengunduh program wget, unzip, dan xxd, lalu mempersiapkan sebuah folder baru bernama “artists_who_can_sing” dan masuk ke dalam folder tersebut.
   ```sh
   sudo apt update && sudo apt install -y wget unzip xxd && mkdir artists_who_can_sing && cd artists_who_can_sing
   ```
2. mendownload file zip menggunakan wget
   ```sh
    wget "https://drive.usercontent.google.com/u/0/uc?id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut&export=download" -O song.zip
   ```
3. unzip ke dalam folder baru
  ```sh
unzip song.zip -d singing_tutorials
```
4. menampilkan list file yang tersembunyi
   ```sh
   ls -a
   ```
5. menampilkan satu baris yang berupa link yang benar
    ```sh
    find . -type f -iname "*opera*NBAYoungboy*" -exec grep -i "FLAG" {} \; > ../flag.txt
    ```
   
   
