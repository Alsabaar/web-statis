# web-statis
Responsi Teknologi Cloud
1. membuat repository baru
2. membuat git clone dari https://github.com/Alsabaar/web-statis.git
3. masuk ke direktori web-statis, sesuaikan nama dengan repositori yang dibuat
4. membuat dockerfile >> nano Dockerfile
5. membuat indexfile >> nano index.html
6. membuild docker images >> docker built -t webserver:v1 .
7. mengecek hasil docker images >> docker images
8. menjalankan docker iamge >> docker run -d -p 80:80 webserver:v1
9. membuka port 80:80 dan akan ditampilkan isi dari file index
selanjutnya
10. menambahkan >> git add .
11. menambahkan user name dan email github 
    git config --global user.email "emailuser.com"
    git config --global user.name "username"
12. melakukan commit >> git commit "responsi"
12. melakukan push >> git push -u origin main
selanjutnya cek pada github anda, sudah terjadi perubahan dengan adanya penambahan data baru yang berhasil di push

Berikutnya melakukan push dann pull ke Docker Hub
1. melakukan git clone https://github.com/Alsabaar/web-statis.git
2. masuk ke direktori web-statis
3. build >> docker build- -t webserver:responsi
4. login docker hub >> docker login
5. masukkin username dan password
6. melalukan setingan tag
7. docker tag image-id username/nama_repo:tag
8. melakukan push ke docker hub >> docker push username/nama_repo
9. selesai
