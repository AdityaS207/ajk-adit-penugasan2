# Project Title

A brief description of what this project does and who it's for.

## Table of Contents

- [Capaian](#capaian)
- [Penjelasan](#penjelasan)
- [Kesulitan](#kesulitan)


## Capaian
Untuk tugas kali ini saya hannya mampu untuk menyelesaikan deployment hingga backend karena pada saat melakuakn deployment frontend saya mengalami kendala dalam proses clone FE repository. Saya juga mengalamin kendala dalam membuka hasil deploymentnya karena pada saat saya buka "localhost:8000" terjadi bad gateway.

## Penjelasan
Dalam penugasan kali ini, hal pertama yang saya lakukan adalah membuat repository baru untuk penugasan.

Setelah membuatnya, maka saya akan langsung melakukan clone dan menyusun struktur repository sesuai yang diinginkan.

Setelah itu pada folder roles, saya akan menjalankan perintah berikut: 
![image](https://cdn.discordapp.com/attachments/1087703394954793022/1233660044902662185/Screenshot_2024-04-27_033902.png?ex=662de6f3&is=662c9573&hm=6adf2924a9e2ce5ee202c0b74cdd9b03d57b1b8324da190927b98e9f6a391c21&)

Setelah itu, saya akan mengisi tiap ansible dengan task-task yang sudah pernah dijalan kan pada pelatihan deployment. Saya juga menyesuaikannya seperti penjelasan yang sudah diberikan.

Setelah semua selesai, saya akan menjalankan perintah "ansible-playbook main.yml" dengan hasil sebagai berikut ini:
![image](https://cdn.discordapp.com/attachments/1087703394954793022/1233660965799723068/Screenshot_2024-04-27_123156.png?ex=662de7ce&is=662c964e&hm=8cee771254082e728ba0c8b1f3e4bea2241e4eb5f796997ef42ae9f97af1ae63&)

Adapun dari hasil tersebut semuanya sudah berhasil dijalankan dengan baik, namun pada saat saya mencoba membuka localhost dengan port 8000 sesuai dengan program ansiblenya, teerjadi error bad gateway seperti pada gambar berikut:
![image](https://cdn.discordapp.com/attachments/1087703394954793022/1233661414393122837/Screenshot_2024-04-27_122543.png?ex=662de839&is=662c96b9&hm=fa86b579031b5ac9bbecca29dd8cd32f331f5f4d44b8027ff3a98ee2e0aecc33&)

Saya masih belum dapat menyelesaikannya semua, karena terdapat error seperti yang saya katakan sebelumnya.

## Kesulitan
Kesulitan yang saya hadapi adalah:
1. Akses backend-nya
Saya masih tidak dapat mengakses backendnya melalui localhost:8000

2. Clone repo FE
Saya mengalami error seperti ini pada saat melakukan clone repo FE
![image](https://cdn.discordapp.com/attachments/1087703394954793022/1233662464269357137/image.png?ex=662de933&is=662c97b3&hm=b211eec4756812c450857b1340b8520c97baed3094778db6be3f694b88b254f4&)

3. Push ke github
Saya mengalami kesulitan pada saat melakukan push ke github karena adanya autentikasi