🌐 NLP with Hugging Face Transformers
<div align="center"> 
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"> 
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">
</div>

Explore and deploy powerful NLP models using the Hugging Face Transformers library! 🚀

This repository demonstrates how to use Hugging Face's transformers library for various NLP tasks.

🔧 NLP Tasks
1. Klasifikasikan seluruh kalimat : Menentukan apakah kalimat tersebut benar secara tata bahasa/mendapatkan sentimen ulasan
2. Klasifikasi setiap kata : NLP mengidentifikasi per kata dari sebuah kalimat seperti nama orang, lokasi atau nama organisasi
3. Membuat konten teks : NLP melengkapi kalimat input dengan memberikan beberapa output
4. Ekstrak jawaban dari teks : NLP akan mengambil jawaban dari input yang sudah kita masukkan
5. Membuat kalimat baru dari teks masukan : NLP mennerjemah kalimat kita ke bahasa lain, atau meringkas kalimat yang di masukkan


✨ Analisis model yang dapat digunakan ✨

1. Klasifikasikan seluruh kalimat : 
    - sentiment analysis : mengklasifikasikan seluruh kalimat, apakah kalimat tersebut positive atau negative, namun terkadang output yang dikeluarkan tidak sesuai dengan yang diharapkan.

2. Klasifikasi setiap kata
    - zero shot classification : mengklasifikasikan setiap kata, dengan memberikan label kadidat di bawahnya, maka dia akan memilah setiap kata dalam kalimat untuk menentukan berapa persen kalimat tersebut relate dengan label yang kita input. Kita dapat memberikan lebih dari 3 label.
    - group entities : mengklasifikasi setiap kata seperti nama orang, lokasi, atau nama organisasinya, output nya juga menghitung urutan kata tersebut ke berapa, dan terakhir berapa.

3. Membuat konten teks 
    - text generation : NLP menyelesaikan perintah dengan teks yang dibuat secara otomatis. mungkin text akan diisi dengan lebih baik apabila kita memberikan clue lebih pada kalimat input kita.Walaupun terkadang jawaban yang diberikan agak aneh.
    - fill mask : NLP mengisi bagian yang kosong dalam teks dengan kata-kata, kita juga diberikan beberapa keyword.

4. Ekstrak jawaban dari teks
    - question answering : menjawab pertanyaan yang diberikan berdasarkan konteks yang sudah kita beri.

5. Membuat kalimat baru dari teks masukan
    - summarization : membuat kalimat baru dari teks input dengan meringkas teks input yang diberikan, kita juga dapat mengatur berapa kata yang akan dibuat sebagai input.
    - translation : menerjemah bahasa input ke bahasa lain, dengan cara kita mengganti modelnya.


For more explore 🚀 https://huggingface.co/
