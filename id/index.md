---
layout: cv
title: Ruben Juliarto
lang: id
updated: 17 September 2019
---
# Ruben Juliarto
_Performance Test_, _DevOps_ Otomasi Kontruksi Perangkat Lunak

{% include links.html %}

## Sekarang

Bekerja di Jenius/BTPN dan bertanggung jawab untuk menguji kinerja aplikasi
_backend_ sebelum naik ke sistem _production_. Juga mengurus perangkat otomasi
untuk mendukung kontruksi aplikasi _mobile_ dan _backend_.

### Otomasi & CICD

 - __Jenkins__: [fastlane](http://fastlane.tools) yang membantu konstruksi aplikasi _mobile_ _iOS_ dan _Android_.
 - __Ansible__: deklarasi kode infrastruktur yang meyediakan _toolchains_: npm, Xcode dan Android SDK.
 - __Kubernetes__: _rolling update_ atau menambah jumlah replika selama eksekusi _performance test_.
 - __Gradle__: alat kontruksi pilihan pertama untuk semua proyek saya.
 - __Newrelic__: melihat _stack trace_ untuk menganalisa dan mencari latensi yang dapat dibuang.

### Aplikasi Backend

 - __Java__: memimpin tim kecil untuk menambah fitur WebApp menggunakan [Spring Framework](http://springframework.org).
 - __NodeJS__: semua proyek Jenius menggunakannya sehingga saya belajar sedikit.
 - __Golang__: menulis _WebApp_ kecil untuk diukur pada proyek [web frameworks benchmark](http://github.com/rubenjoy/webapps-rave).
 - __MongoDB__: melakukan _query_ kecil atau _upsert_ guna mendukung skrip JMeter.
 - __Groovy__: membuat [jmeter HMAC plugin](http://github.com/rubenjoy/jmeter-hmac-plugin).
 - __Python__: belajar otodidak dengan tujuan menjalankan simulasi Locust.io.

### Pengujian Perangkat Lunak

 - __Apache JMeter__: semua _performance test_ di Jenius menggunakannya.
 - __Locust.io__: riset skala kecil untuk mengganti Apache JMeter.
 - __[Blazemeter](http://gettaurus.org)__: menulis deklarasi YAML tanpa perlu membuat skrip JMeter.
 - __Unit test__: sangat penting untuk _clean code_.
 - __[Burpsuite](http://portswigger.net/burp)__: menggunakan _proxy_ agar dapat melihat _request HTTP_ yang mendukung skrip JMeter.

## Pendidikan

`2013`
__Magister Sains Manajemen__, Institut Teknologi Bandung.

`2010`
__Teknik Informatika__, Institut Teknologi Bandung.

## Pekerjaan

`2018 till now`
__[BTPN Jenius](http://jenius.com)__, Jakarta.

- Mengumpulkan _request REST-API_ untuk tiap skenario pengguna, lalu menulis skrip JMeter.
- Eksekusi _performance test_ dan kompilasi laporan akhir.
- Membuat _Jenkins job_ yang dapat mengeksekusi skrip JMeter dan kompilasi laporan dalam bentuk HTML.
- Riset Grafana dan InfluxDB untuk membangun sebuah _dashboard real-time_.

`2017`
__[Mitrais](http://mitrais.com)__, Bandung

- Menambahkan fitur pada _WebApp Spring Boot_ untuk klien New Zealand yang membutuhkan sistem informasi observasi dan pencatatan pengembangan diri karyawan.
- Melakukan analisa dan pengumpulan _requirements_ untuk sistem reservasi ruangan dan fasilitas milik klien New Zealand.

`2016`
__[Kresna Securities](http://kresnasecurities.com)__, Jakarta

- Studi komparatif sejumlah _online trading platform_ yang ada di Indonesia.

## Kursus

`2019`
__[Metodologi Agile pada Pengembangan Perangkat Lunak](https://courses.edx.org/courses/course-v1:ETHx+ASD.1x+1T2019/course/)__, EDX.org

`2019`
__[Mengerti Agile Lebih Jauh](https://www.udemy.com/course/understanding-agile-at-a-deeper-level/)__, Udemy.com

`2019`
__[Kuliah Singkat Machine Learning](https://developers.google.com/machine-learning/crash-course/)__, Google

`Ongoing`
__[Agile for Project Control](https://courses.edx.org/courses/course-v1:USMx+ENCE607.5x+1T2019/course/)__, EDX.org

`2017`
__[Scalable Microservices with Kubernetes](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)__, Udacity.com

`2017`
__[Redux untuk Pemula](https://egghead.io/courses/getting-started-with-redux)__, Egghead.io

`2017`
__[React untuk Pemula](https://egghead.io/courses/the-beginner-s-guide-to-react)__, Egghead.io

`2016`
__[Pemrograman Fungsional di Scala](https://www.coursera.org/learn/progfun1)__, Coursera.org

`Plan`
__[Responsive Web Design Fundamentals](https://www.udacity.com/course/responsive-web-design-fundamentals--ud893)__, Udacity.com

### pemutakhiran: {{ page.updated }}

{% include short-links.html %}