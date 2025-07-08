# Moodle

<p align="center"><a href="https://moodle.org" target="_blank" title="Moodle Website">
  <img src="https://raw.githubusercontent.com/moodle/moodle/main/.github/moodlelogo.svg" alt="The Moodle Logo">
</a></p>

[Moodle][1] is the World's Open Source Learning Platform, widely used around the world by countless universities, schools, companies, and all manner of organisations and individuals.

Moodle is designed to allow educators, administrators and learners to create personalised learning environments with a single robust, secure and integrated system.

## Documentation

- Read our [User documentation][3]
- Discover our [developer documentation][5]
- Take a look at our [demo site][4]

## Community

[moodle.org][1] is the central hub for the Moodle Community, with spaces for educators, administrators and developers to meet and work together.

You may also be interested in:

- attending a [Moodle Moot][6]
- our regular series of [developer meetings][7]
- the [Moodle User Association][8]

## Installation and hosting

Moodle is Free, and Open Source software. You can easily [download Moodle][9] and run it on your own web server, however you may prefer to work with one of our experienced [Moodle Partners][10].

Moodle also offers hosting through both [MoodleCloud][11], and our [partner network][10].

## License

Moodle is provided freely as open source software, under version 3 of the GNU General Public License. For more information on our license see

[1]: https://moodle.org
[2]: https://moodle.com
[3]: https://docs.moodle.org/
[4]: https://sandbox.moodledemo.net/
[5]: https://moodledev.io
[6]: https://moodle.com/events/mootglobal/
[7]: https://moodledev.io/general/community/meetings
[8]: https://moodleassociation.org/
[9]: https://download.moodle.org
[10]: https://moodle.com/partners
[11]: https://moodle.com/cloud
[12]: https://moodledev.io/general/license


---------------------------------------------------------------------------------------------------------------------------------------

# 🎓 Final Project - Sistem E-Learning Berbasis Moodle

Proyek akhir ini merupakan pengembangan sistem e-learning berbasis **Moodle** yang digunakan untuk mendukung proses pembelajaran daring di lingkungan sekolah.

## 📁 Struktur Proyek

projek-akhir/
├── moodle/ # ✅ Source code utama Moodle (diupload ke GitHub)
├── moodledata/ # ❌ Folder data Moodle (tidak diupload)
├── database.sql # ❌ Backup database (tidak diupload)

## ✅ Yang Di-upload ke GitHub
- Folder `moodle/` yang berisi:
  - Source code utama Moodle.
  - Modifikasi atau penyesuaian (jika ada), seperti plugin, tema, atau pengaturan lainnya.
- File `.gitignore` untuk mengecualikan file sensitif atau besar.
- File `README.md` sebagai dokumentasi proyek.

## ❌ Yang Tidak Di-upload
- `moodledata/`: berisi file upload pengguna, cache, dan data runtime lainnya. Folder ini sangat besar dan tidak cocok untuk disimpan di GitHub.
- `config.php`: mengandung informasi sensitif seperti koneksi ke database.
- File `.sql` (backup database): berisi data pengguna dan pengaturan penting, tidak diupload untuk menjaga privasi dan keamanan.

## 🧪 Cara Menjalankan Proyek (Secara Lokal)
1. Download folder `moodle/` dari repository ini.
2. Siapkan web server lokal seperti **XAMPP**, **Laragon**, atau **MAMP**.
3. Buat folder `moodledata/` secara manual di luar `moodle/` dan pastikan memiliki permission **writable**.
4. Import database `.sql` yang akan dikirim secara terpisah jika diperlukan.
5. Buat file `config.php` sendiri atau sesuaikan dari `config-dist.php`.
