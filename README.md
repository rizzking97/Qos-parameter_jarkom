Nama : Rizko Fahrezy

NIM : 09030582327094

Kelas : TK4B

QOS Parameter

Berikut langkah Langkah 

Masuk Ke Aplikasi WireShark

<img src="https://github.com/user-attachments/assets/9e4b4309-c8c0-4a2d-98c7-0022977dc30b" alt="image" width="200">

Pilih wifi lalu open

<img src="https://github.com/user-attachments/assets/3bf1a3e0-88e3-4e8c-9d25-58acf37d8864" alt="image" width="200">

Tampilan Awal Lalu Run TCP

<img src="https://github.com/user-attachments/assets/938e3ba6-8aa3-41ff-b131-1a0b0f2fab8b" alt="image" width="200">

Lalu Broswing apa yang di inginkan

<img src="https://github.com/user-attachments/assets/2388724b-33ff-408d-868e-514eb4d7a023" alt="image" width="200">

Masuk ke CMD untuk mengeping

<img src="https://github.com/user-attachments/assets/2d779bd1-3b3e-43a5-a0b2-eb95c32bd9d6" alt="image" width="200">

Pilih Ip.dst lalu masukan angka dari ping yg muncul

<img src="https://github.com/user-attachments/assets/e2974ef7-7017-4947-892d-c613bee4a611" alt="image" width="200">

Pilih stastistik lalu clik capture file propertise

<img src="https://github.com/user-attachments/assets/712cec97-1cd5-4b77-8a0a-ef8bb85ff8ef" alt="image" width="200">

Begini tampilanya dan bisa untuk menghitung Parameter QOS

<img src="https://github.com/user-attachments/assets/750d6990-c38d-4726-9cc5-ef2c6e92ec34" alt="image" width="200">

Ini hasil hitungan thoughut dan paket loss

<img src="https://github.com/user-attachments/assets/0c0f4e8c-d7d4-48fd-81c5-04fa5cc309ca" alt="image" width="200">

Proses Perhitungannya 

<img src="https://github.com/user-attachments/assets/c5a32fc6-25bc-419b-ae3d-944bf6286638" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/46b3ccc7-dd1a-4089-a921-f3703f19e6f8" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/ed36017e-bc2a-4336-9676-eab97aeff19a" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/03087469-e3d9-4f4c-96dd-ba6f15be2e8a" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/b6274c89-842c-4379-b465-a9ff6e6981b0" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/5dc130b0-7581-4a4d-8a15-cd6a8b121dd3" alt="image" width="200">


Klick file pilih export packet disection lalu pilih As csv

<img src="https://github.com/user-attachments/assets/886dd07f-9edf-41bd-84a2-b9e6ba5b95b8" alt="image" width="200">

Masuk ke exel lalu rapikan data nya dan ini hasilnya

<img src="https://github.com/user-attachments/assets/e41f624f-9933-42d8-92b4-6a1891e1ea8e" alt="image" width="200">

Dan inilah hasil hitungan total delay dan rata rata delay

<img src="https://github.com/user-attachments/assets/7225e919-fceb-41e9-90e2-46a4ffa67c59" alt="image" width="200">

Proses perhitunganya

<img src="https://github.com/user-attachments/assets/bae532ff-6a6d-4e87-ae98-35c19deaace8" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/db3d57c3-e339-4aeb-85fe-3605532a23cb" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/f7635184-5332-4c95-902c-99d4d459e4b5" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/402e24d9-9ded-4bfd-8f9b-14152e96acb2" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/9ecaebd3-83e0-4f75-b5c1-09b84429d9af" alt="image" width="200">
<img src="https://github.com/user-attachments/assets/0d8b3dae-160a-42ba-939f-563dae34d23a" alt="image" width="200">

Analisis QOS Parameter: 

Berdasarkan data parameter QoS yang dianalisis, ditemukan bahwa nilai delay rata-rata berada di angka 102,92 ms, dengan median sebesar 30,07 ms. Perbedaan antara rata-rata dan median ini menunjukkan bahwa terdapat beberapa lonjakan besar dalam delay yang menyebabkan distribusi data menjadi tidak merata. Standar deviasi delay yang tinggi (193,22 ms) mengindikasikan variasi yang signifikan dalam waktu tunda paket data. Dengan nilai maksimum delay mencapai 897 ms, jaringan ini mengalami lonjakan latensi yang cukup besar, yang dapat berdampak negatif terhadap aplikasi real-time seperti VoIP dan video streaming.

Parameter Delay1 dan Delay2 memiliki karakteristik yang serupa dengan rata-rata sekitar 20 ms dan standar deviasi yang tinggi, yaitu sekitar 183 ms. Nilai minimum yang sangat rendah (-407 ms) dan maksimum yang tinggi (996 ms) menunjukkan bahwa keterlambatan dalam transmisi data tidak stabil dan sering mengalami perubahan ekstrem. Hal ini dapat menyebabkan ketidakkonsistenan dalam performa jaringan, terutama saat menghadapi lalu lintas data yang tinggi.

Sementara itu, jitter sebagai indikator variasi delay memiliki rata-rata -13,95 ms dengan standar deviasi yang sangat tinggi (224,80 ms). Nilai minimum jitter mencapai -962,34 ms, sedangkan nilai maksimumnya mencapai 817,24 ms, yang menunjukkan adanya ketidakstabilan besar dalam pola keterlambatan paket. Perubahan yang drastis ini dapat menyebabkan gangguan signifikan dalam layanan berbasis waktu nyata, seperti suara yang terputus-putus dalam panggilan VoIP atau buffering dalam video streaming.

Kesimpulan : 

Berdasarkan hasil analisis, dapat disimpulkan bahwa jaringan ini mengalami fluktuasi besar dalam delay dan jitter, yang dapat berdampak buruk pada kualitas layanan, terutama dalam aplikasi real-time. Standar deviasi yang tinggi pada seluruh parameter QoS menunjukkan bahwa performa jaringan tidak konsisten dan sering mengalami lonjakan latensi. Delay yang tinggi (>800 ms) berpotensi menyebabkan komunikasi tidak responsif, sedangkan jitter yang ekstrem (>900 ms) dapat mengganggu stabilitas transmisi data.

Untuk meningkatkan kualitas jaringan, perlu dilakukan optimasi QoS, seperti penerapan traffic shaping, peningkatan bandwidth, dan pengelolaan prioritas paket data. Selain itu, pengurangan interferensi dan pemantauan performa jaringan secara berkala dapat membantu menjaga stabilitas koneksi. Dengan perbaikan ini, diharapkan jaringan dapat memberikan layanan yang lebih stabil dan responsif bagi pengguna.








