#instalasi map server di virtual box
menggunakan centos 6.8 <br>
<img src="../../img/map.jpg">
langkah: <br>
1. add repo epel & elgis<br>
.#rpm -Uvh http://download.fedoraproject.org/pub/epel/6/x86_64/epel:release-6-8.noeurch.rpm <br>
.#rpm Uvh http://elgis.argeo.org/repos/6/elgis-release-6-6-0.noeurch.rpm <br>
2. exclude = armadillo dan edit file <br>
.#vi /etc/yum.repos.d/epel.repo <br>
tambahan exclude = armadillo * <br>
3. instalasi armadillo <br>
.#wget http://elgis.argeo.org/repos/6/elgis/x86_64/gdal-1.9.2-4.e16.x86_64.rpm <br>
.#ym install armadillo -3.8002-1.e16.x86_64.rpm <br>
4. install depedensi <br>
.#yum install gpsbabel <br>
.#yum install gdal <br>
.#yum install mapserver <br>
.#yum install glibc <br>
.#yum install libpng libpng-devel <br>
.#yum install giflib-devel <br>
.#yum install proj-epsg <br>
5. selesai, cek instalasi <br>
.#rpm -almapserver <br>

.#yum install python-pip python devel
.#pip install map proxy
.#install Vwsql
.#pip instal Vwsql

Nama : gentur ariyadi siddiq p.y. <br>
NPM : 1144025 <br>
Kelas : 3B <br>
Prodi : D4 Teknik Informatika <br>
Mata Kuliah : Sistem Informasi Geografis <br>

Link Github : https://github.com/FirmanMFK/GIS--Geographic-Information-Systems <br>
kambing.ui.ac.id/iso/Centos <br>

scan plagiarisme <br>
1. https://drive.google.com/open?id=0B7e_luHkgYYMcFFoN2N3YkVteEU <br>
2. https://drive.google.com/open?id=0B7e_luHkgYYMcl9wNDF2STBxazQ <br>