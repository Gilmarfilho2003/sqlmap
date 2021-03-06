# sqlmap

[![Build Status](https://api.travis-ci.org/sqlmapproject/sqlmap.svg?branch=master)](https://travis-ci.org/sqlmapproject/sqlmap) [![Python 2.6|2.7|3.x](https://img.shields.io/badge/python-2.6|2.7|3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/sqlmapproject/sqlmap/master/LICENSE) [![PyPI version](https://badge.fury.io/py/sqlmap.svg)](https://badge.fury.io/py/sqlmap) [![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/sqlmapproject/sqlmap.svg?colorB=ff69b4)](https://github.com/sqlmapproject/sqlmap/issues?q=is%3Aissue+is%3Aclosed) [![Twitter](https://img.shields.io/badge/twitter-@sqlmap-blue.svg)](https://twitter.com/sqlmap)

sqlmap merupakan alat _(tool)_ bantu _open source_ dalam melakukan tes penetrasi yang mengotomasi proses deteksi dan eksploitasi kelemahan _SQL injection_ dan pengambil-alihan server basis data. sqlmap dilengkapi dengan pendeteksi canggih, fitur-fitur handal bagi _penetration tester_, beragam cara untuk mendeteksi basis data, hingga mengakses _file system_ dan mengeksekusi perintah dalam sistem operasi melalui koneksi _out-of-band_. 

Tangkapan Layar
----

![Tangkapan Layar](https://raw.github.com/wiki/sqlmapproject/sqlmap/images/sqlmap_screenshot.png)

Anda dapat mengunjungi [koleksi tangkapan layar](https://github.com/sqlmapproject/sqlmap/wiki/Screenshots) yang mendemonstrasikan beberapa fitur dalam wiki.

Instalasi
----

Anda dapat mengunduh tarball versi terbaru [di sini](https://github.com/sqlmapproject/sqlmap/tarball/master) atau zipball [di sini](https://github.com/sqlmapproject/sqlmap/zipball/master).

Sebagai alternatif, Anda dapat mengunduh sqlmap dengan men-_clone_ repositori [Git](https://github.com/sqlmapproject/sqlmap):

    git clone --depth 1 https://github.com/sqlmapproject/sqlmap.git sqlmap-dev

sqlmap berfungsi langsung pada [Python](http://www.python.org/download/) versi **2.6**, **2.7** dan **3.x** pada platform apapun.

Penggunaan
----

Untuk mendapatkan daftar opsi dasar gunakan:

    python sqlmap.py -h

Untuk mendapatkan daftar opsi lanjut gunakan:

    python sqlmap.py -hh

Anda dapat mendapatkan contoh penggunaan [di sini](https://asciinema.org/a/46601).
Untuk mendapatkan gambaran singkat kemampuan sqlmap, daftar fitur yang didukung, deskripsi dari semua opsi, berikut dengan contohnya, Anda disarankan untuk membaca [Panduan Pengguna](https://github.com/sqlmapproject/sqlmap/wiki/Usage).

Tautan
----

* Situs: https://sqlmap.org
* Unduh: [.tar.gz](https://github.com/sqlmapproject/sqlmap/tarball/master) atau [.zip](https://github.com/sqlmapproject/sqlmap/zipball/master)
* RSS feed dari commits: https://github.com/sqlmapproject/sqlmap/commits/master.atom
* Pelacak Masalah: https://github.com/sqlmapproject/sqlmap/issues
* Wiki Manual Penggunaan: https://github.com/sqlmapproject/sqlmap/wiki
* Pertanyaan yang Sering Ditanyakan (FAQ): https://github.com/sqlmapproject/sqlmap/wiki/FAQ
* Twitter: [@sqlmap](https://twitter.com/sqlmap)
* Video Demo [#1](http://www.youtube.com/user/inquisb/videos) dan [#2](http://www.youtube.com/user/stamparm/videos)
* Tangkapan Layar: https://github.com/sqlmapproject/sqlmap/wiki/Screenshots
