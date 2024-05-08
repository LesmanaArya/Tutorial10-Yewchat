# Tutorial 3: WebChat using yew

## 3.1 Original code
### Running yewchat
![websocket](img/Screenshot%20(1592).png)

### Running chat app + websocket
![1](img/Screenshot%20(1593).png)
![2](img/Screenshot%20(1594).png)
![3](img/Screenshot%20(1595).png)
Pada tutorial ini, terdapat dua komponen utama yang dibutuhkan, yaitu websocket serta Yewchat itu sendiri. Websocket disini sama seperti pada tutorial sebelumnya, yaitu seperti ```server.rs``` serta memberikan hubungan komunikasi antara server dan client. Yewchat disini akan berfungsi seperti ```client.rs```, dimana kita memberikan username serta mengirim message. Message yang dikirim nanti akan terlihat oleh client-client yang lain serta ditampilkan pula username dari client tersebut. Dalam contoh ini, saya membuat tiga buah client dengan nama user yang berbeda-beda. Pesan yang dikirimkna oleh client akan diteruskan oleh server dan tampil di client lain.