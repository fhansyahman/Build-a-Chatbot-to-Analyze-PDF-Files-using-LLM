# Build a Chatbot to Analyze PDF Files using LLM
### **Author : Sina Nazeri**

## Deskripsi Awal
Pada course kali ini kamu akan membuat sebuah Chatbot AI untuk menganalisis sebuah file PDF yang kamu upload sebagai fitur utama dari Chatbot ini, pemrosesan bahasa natural, dalam artian (NLP) yang dipakai dalam Chatbot ini adalah sebuah API LLM dari OpenAI GPT 3.5 yang akan menjadi pemroses bahasa dari PDF yang di upload.

- LLM (Large Language Model)
Large Language Models (LLM), atau Model Bahasa Besar, adalah pencapaian terkini dalam bidang kecerdasan buatan yang memanfaatkan teknologi pembelajaran mesin untuk memahami dan menghasilkan teks dengan tingkat kompleksitas yang tinggi. LLM menghadirkan kemampuan unik untuk memproses dan memahami konteks linguistik dalam berbagai bahasa, serta menghasilkan teks yang seringkali sulit dibedakan dari tulisan manusia.
Dengan menggunakan teknik deep learning dan arsitektur model yang sangat besar, LLM dapat mengatasi tugas-tugas seperti penerjemahan bahasa, generasi teks kreatif, dan pemahaman konteks dalam bahasa alami. Model ini dilatih dengan jumlah data yang luar biasa besar, memungkinkannya untuk mengenali pola-pola kompleks dan menyimpan pengetahuan lintas domain.

- Flask
Flask adalah kerangka kerja web yang ringan dan fleksibel untuk Python, dikenal karena kesederhanaan dan kecepatannya. Sebuah kerangka kerja web adalah kerangka kerja perangkat lunak yang dirancang untuk mendukung pengembangan aplikasi web, termasuk pembuatan server web, dan pengelolaan permintaan dan tanggapan HTTP.
Kita akan menggunakan Flask untuk membuat sisi server atau back-end dari chatbot ini. Ini melibatkan penanganan pesan masuk dari pengguna, memproses pesan-pesan, dan mengirim tanggapan yang sesuai kembali kepada pengguna.
Dalam Flask, rute dibuat menggunakan dekorator @app.route untuk menghubungkan suatu fungsi dengan rute URL. Ketika pengguna mengunjungi URL tersebut, fungsi terkait dieksekusi. Dalam proyek chatbot kami, kami akan menggunakan rute untuk menangani permintaan POST yang membawa pesan pengguna dan memproses data dokumen.

- Langchain
Langchain adalah alat serbaguna untuk membangun aplikasi bahasa berbasis kecerdasan buatan (AI). Ini menyediakan berbagai fungsionalitas seperti pencarian teks, ringkasan, terjemahan, dan banyak lagi, dengan memanfaatkan model bahasa yang telah dilatih sebelumnya. Dalam proyek ini, kami akan mengintegrasikan Langchain ke dalam chatbot kami, memberdayakannya untuk memahami dan merespons berbagai input pengguna dengan efektif.

- Chatbot
Chatbot adalah aplikasi perangkat lunak yang dirancang untuk berkomunikasi seperti manusia. Mereka dapat merespons input teks dari pengguna dan banyak digunakan dalam berbagai bidang, termasuk layanan pelanggan, e-commerce, dan pendidikan. Dalam proyek ini, Anda akan membangun chatbot yang mampu tidak hanya berinteraksi dengan pengguna dalam percakapan umum, tetapi juga menjawab pertanyaan berdasarkan dokumen tertentu.

- HTML - CSS - JavaScript
Kelas ini telah menyediakan antarmuka chatbot yang siap digunakan, dibangun dengan HTML, CSS, dan Javascript. HTML membangun struktur konten web, CSS menghiasinya, dan Javascript menambahkan interaktivitas. Teknologi-teknologi ini menciptakan antarmuka chatbot yang menarik secara visual dan interaktif.

Setelah menyelesaikan proyek ini, Anda akan memperoleh pemahaman yang lebih mendalam tentang chatbot, pengembangan aplikasi web menggunakan Flask dan Python, serta penggunaan kerangka kerja LangChain dalam menginterpretasikan dan merespons berbagai jenis input pengguna. Lebih penting lagi, Anda akan berhasil membangun aplikasi chatbot yang komprehensif dan pasti akan memberikan kesan yang mengesankan!

## Mentee Information
- **Name:** Farhan Firmansyah
- **Program:** IBM Advanced AI

## Kemampuan yang diperlukan
Siapapun dari latar belakang apapun dapat mengikuti kelas ini dengan baik. Kelas ini sudah dibuat sedemikian rupa dengan penjelasan yang cukup mudah dimengerti. Tetapi, keahlian berikut dapat membantu anda memahami kelas lebih baik lagi:

- Python
- Flask (Framework web berbasis Python)
- HTML, CSS, JavaScript dasar
