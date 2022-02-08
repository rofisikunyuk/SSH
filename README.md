# SSH
Secure Shell (SSH) adalah sebuah protokol jaringan kriptografi untuk komunikasi data yang aman, login antarmuka baris perintah, perintah eksekusi jarak jauh, dan layanan jaringan lainnya antara dua jaringan komputer.
<h3>Cara menginstal SSH</h3>
<p>1. Update Debian.</p>
<p><code>apt-get update</code></p>
<p><code>apt-get upgrade</code></p>
<p>2. Install SSH.</p>
<p><code>apt-get install openssh-server</code></p>
<p>3. <code>nano /etc/ssh/sshd_config</code></p>
<p>Akan muncul tampilan seperti berikut.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_57_43.png" width="250" height="150">
<p>4. Hilangkan tanda pagar pada tulisan port 22 menjadi seperti ini.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_58_02.png" width="250" height="150">
<p>5. Kemudian Kalian save dengan menekan tombol <code>ctrl+x</code> tekan <code>y</code> tekan <code>enter</code>.</p>
<p>6. <code>systemctl restart ssh</code> untuk merestart SSH.</p>
<p>7. <code>systemctl start ssh</code> untuk mengaktifkan SSH.</p>
<p>8. <code>systemctl status ssh</code> untuk mengecek status SSH.</p>
<p>9. Berikut ini adalah tampilan SSH yang sedang aktif.</p>
<img src="https://github.com/rofisikunyuk/SSH/blob/main/Screenshot/VirtualBox_DEBIAN10%5BSERVER%5D_07_02_2022_13_58_27.png" width="250" height="150">
<p>10. Cara menggunakan service SSH lewat terminal <code>ssh username@host</code>.</p><hr>
<p>"Kalau gambarnya kurang jelas di zoom aja ya broo"</p>

