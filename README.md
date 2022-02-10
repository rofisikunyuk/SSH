# SSH
<p>Secure Shell (SSH) adalah sebuah protokol jaringan kriptografi untuk komunikasi data yang aman, login antarmuka baris perintah, perintah eksekusi jarak jauh, dan layanan jaringan lainnya antara dua jaringan komputer.</p>
<h3>Cara menginstal SSH</h3>
<p>1. Update Debian.</p>
<p><li><code>apt-get update</code></li></p>
<p><li><code>apt-get upgrade</code></li></p>
<p>2. Install SSH.</p>
<p><li><code>apt-get install openssh-server</code></li></p>
<p>3. Edit file konfigurasi SSH</p>
<p><li><code>nano /etc/ssh/sshd_config</code></li></p>
<p>4. Akan muncul tampilan seperti berikut.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_57_43.png" width="350" height="175">
<p>5. Hilangkan tanda pagar pada tulisan port 22 menjadi seperti ini.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_58_02.png" width="350" height="175">
<p>6. Kemudian Kalian save dengan menekan tombol <code>ctrl+x</code> tekan <code>y</code> tekan <code>enter</code>.</p>
<p><Li><code>systemctl restart ssh</code> untuk merestart SSH.</li></p>
<p><li><code>systemctl start ssh</code> untuk mengaktifkan SSH.</li></p>
<p><li><code>systemctl status ssh</code> untuk mengecek status SSH.</Li></p>
<p>7. Berikut ini adalah tampilan SSH yang sedang aktif.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_58_27.png" width="350" height="175">
<p>8. Cara menggunakan service SSH lewat terminal.</p>
<p><li><code>ssh username@host</code></li></p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/ssh%20terminal.png" width="350" height="175"><hr>
<p>"Kalau gambarnya kurang jelas di zoom aja ya broo"</p>
