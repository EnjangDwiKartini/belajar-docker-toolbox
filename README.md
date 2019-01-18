# Installasi Docker for Windows 

Dalam proses belajar Docker ini saya menggunakan sistem Operasi Windows, sehingga untuk mempelajari Docker menggunakan Docker ToolBox dimana tool ini menyediakan semua komponen yang harus di-install agar Docker dapat berjalan di Windows, seperti VirtualBox, Boot2Docker dan access terminal. Meski bukan merupakan port, dengan Docker Toolbox memudahkan kita untuk menjalankan Docker pada mesin Windows. Docker Tool tersedia gratis untuk pengguna Windows . Karena disini saya belum punya pengalaman untuk  men-setup dan menjalankan server Linux, maka saya berusaha untuk belajar dan mencoba Docker dengan mudah di komputer Windows menggunakan Docker Toolbox ini.
Untuk menginstall Docker Toolbox ini dapat  diakses di dokumentasi resmi Docker dengan alamat sebagai berikut :
https://docs.docker.com/toolbox/toolbox_install_windows/ 


Langkah installnya cukup mudah seperti menginstall software di windows pada umumnya. Berikut beberapa dokumentasi langkah install Docker Toolbox :


 ![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/img-2.JPG "Enjang DK")
 
 ![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/img-3.JPG "Enjang DK")
 
 ![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/img-4.JPG "Enjang DK")
 
Setelah selesai install, kita dapat mencoba perintah untuk mengetahui versi Docker yang terinstal dengan perintah :

	~~~
	docker -v
	~~~

	~~~
	docker -v
	~~~

	
 ![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/img-5.JPG "Enjang DK")
	
Kemudian kita juga bisa melihat versi docker compose dan docker-machine dengan perintah :
	~~~
	docker-compose -version
	~~~

	~~~
	docker-machine -version
	~~~

![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/img-6.JPG "Enjang DK")


Untuk memudahkan proses pertama konfigurasi dapat menggunakan Docker Quickstart 

![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/dockerQuick.JPG "Enjang DK") 

![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/img-7.JPG "Enjang DK")

Tunggu beberapa saat sampai proses selesai dan muncul tampilan seperti berikut :

![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/img-8.JPG "Enjang DK")

Untuk percobaan pertama saya mencoba menjalankan hello world dengan perintah 
~~~
docker run hello-world
~~~

Dari perintah tersebut maka akan menampilkan hasil sebagai berikut :

![alt text](https://github.com/EnjangDwiKartini/belajar-docker-toolbox/blob/master/img-9.JPG "Enjang DK")







