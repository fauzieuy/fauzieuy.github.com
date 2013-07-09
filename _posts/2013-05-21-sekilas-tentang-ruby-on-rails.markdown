---
layout: post
title: "Sekilas Tentang Ruby On Rails"
description: ""
category: ruby on rails
tags: [ruby-on-rails, ruby]
year: 2013
month: 5
day: 21
published: true
summary: Mengenal sedikit tentang Ruby On Rails
image: rails.jpg
---


<h3>Ide Dibalik Rails</h3>

<div class="span5" id="image-post">
<a href="#" class="thumbnail"><img src="/img/posts/21-05-2013/ruby-on-rails.jpg" title="Ruby On Rails"/></a>
</div>
<p>
Ruby on Rails diciptakan oleh David Heinemeier Hansson sebagai semacam produk  dari Basecamp’s development di 37signals pada tahun 2004. Basecamp dibangun menggunakan Ruby karena Hansson merasa PHP dan Java tidak kuat atau cukup fleksibel.  Hal ini cukup mengaburkan bahasa, tanpa eco-system besar yang tersedia pada saat itu. Untuk membuat pengembangan lebih mudah, Hansson membuat web framework sendiri, didasarkan pada ide-ide sederhana yang telah terbukti berhasil. Rails didasarkan pada pragmatisme dan mendirikan ide-ide baru yang eksotis. Dan itulah yang membuatnya begitu sukses.</p>


<p>Rails didasarkan pada pola <b>Model-View-Controller</b> yang membagi aplikasi menjadi tiga bagian:</p>

<ol>
	<li>
		<b>Model</b>, Model mewakili <a href="http://id.wikipedia.org/wiki/Struktur_data">struktur data</a>. Biasanya model berisi fungsi-fungsi yang membantu seseorang dalam pengelolaan <a href="http://id.wikipedia.org/wiki/Basis_data">basis data</a> seperti memasukkan data ke basis data, pembaruan data dan lain-lain.
	</li>
	<li>
		<b>View</b>, View adalah bagian yang mengatur tampilan ke pengguna. Bisa di katakan berupa halaman web.
	</li>
	<li>
		<b>Controller</b>, Controller merupakan bagian yang menjembatani model dan view. Controller berisi perintah-perintah yang berfungsi untuk memproses suatu data dan mengirimkannya ke halaman web.
	</li>
</ol>
<div class="span5" id="image-post">
<a href="#" class="thumbnail"><img src="/img/posts/21-05-2013/mvc.jpg" title="Ruby On Rails"/></a>
</div>

<p>Rails adalah "opinionated software", artinya ia tidak ingin menjadi segalanya bagi semua orang. Lebih memfokuskan pada salah satu cara dalam melakukan sesuatu dan merampingkan semua komponen yang ada. Itu bukan berarti tidak ada kemungkinan jika anda perlu untuk melakukan sesuatu yang berbeda. Tetapi anda pasti akan mudah jika anda melakukan hal-hal yang mengikuti aturan pada rails (the Rails Way).</p>

<p>Meskipun benar bahwa Ruby on Rails lebih lambat dibandingkan dengan PHP atau Python, Tentu saja tidak jika menggunakan skala yang besar, terbukti sekarang sudah banyak web aplikasi yang sukses menggunakan Ruby on Rails. Anda hanya perlu menggunakan skala yang cepat dan berpikir untuk melakukan sesuatu untuk aplikasi anda agar lebih cepat kinerjanya. Ingat juga bahwa implementasi yang standar saat pada ruby sangat tidak efisien, gunakan alternatif lain. Pada dasarnya tidak ada bahasa pemrograman yang lambat, meskipun ada yang bilang Smalltalk (bahasa yang sangat mirip dengan Ruby) cepat. Ruby hanya akan mendapatkan lebih cepat jika anda menggunakannya secara benar. Seperti kata pepatah "you don’t have a performance problem until you have a performance problem", dan semua pembicaraan ini seharusnya tidak menakut-nakuti Anda. Anda bahkan belum mencobanya. ;)</p>

<p>Jika Anda ingin menjelajahi sedikit Ruby, Anda bisa mencoba tutorial interaktif di <a href="http://tryruby.org/">try ruby</a>, atau Anda bisa membaca di salah satu buku yang tercantum pada akhir artikel ini. Jika Anda hanya ingin melihat contoh kode, bisa lihat pada halaman <a href="http://id-ruby.org/learnruby/">Learn Ruby</a> (Bahasa Indonesia).</p>

<p>Pada postingan selanjutnya saya akan mencoba memberikan cara untuk menginstall ruby on rails pada beberapa OS (Windows, Ubuntu, Centos) dan akan mencoba mengenalkan  lebih dekat tentang Rails dan menemukan "sesuatu yang wah" dari Ruby on Rails. :D</p>

<p><strong>Sumber :</strong> <a href="http://coding.smashingmagazine.com/2009/03/19/getting-started-with-ruby-on-rails/">Getting Started With Ruby On Rails</a></p>

