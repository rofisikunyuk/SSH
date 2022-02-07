# SSH
Secure Shell (SSH) adalah sebuah protokol jaringan kriptografi untuk komunikasi data yang aman, login antarmuka baris perintah, perintah eksekusi jarak jauh, dan layanan jaringan lainnya antara dua jaringan komputer.
<h3>Cara menginstal SSH</h3>
<p><code>apt-get update</code></p>
<p><code>apt-get upgrade</code></p>
<p><code>apt-get install openssh-server</code></p>
<p><code>nano /etc/ssh/sshd_config</code></p>
<p>Akan muncul tampilan seperti berikut.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_57_43.png" width="250" height="150">
<p>Hilangkan tanda pagar pada tulisan port 22 menjadi seperti ini.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_58_02.png" width="250" height="150">
<p>Kemudian Kalian save dengan menekan tombol <code>ctrl+x</code> tekan <code>y</code> tekan <code>enter</code>.</p>
<p>Kemudian kalian restart SSH <code>systemctl restart ssh</code>.</p>
<p>Kemudian kalian aktifkan SSH <code>systemctl start ssh</code>.</p>
<p>Kemudian kalian cek status SSH <code>systemctl status ssh</code>.</p>
<p>Berikut ini adalah tampilan SSH yang sedang aktif.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_58_27.png" width="250" height="150">
