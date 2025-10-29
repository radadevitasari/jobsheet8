Jawaban percobaan 1
1. Jika pada perulangan for, inisialisasi i=1 diubah menjadi i=0, apa yang akibatnya? Mengapa bisa demikian?
jawab= Kalau i dimulai dari 0, maka bintang yang muncul lebih banyak satu karena perulangannya berjalan dari 0 sampai N, jadi dihitung N+1 kali

2. Jika pada perulangan for, kondisi i <= N diubah menjadi i > N, apa akibatnya? Mengapa bisa demikian?
jawab= Kalau kondisi i > N, maka perulangan tidak berjalan sama sekali karena sejak awal syaratnya sudah salah (1 > 5 tidak benar)

3. Jika pada perulangan for, kondisi step i++ diubah menjadi i-- apa akibatnya? Mengapa bisa demikian?
jawab= Jika i++ (naik 1 tiap putaran) diubah menjadi i-- (turun 1 tiap putaran), maka perulangan akan menjadi tidak berhenti (infinite loop)

Jawaban percobaan 2
1. Perhatikan perulangan luar. Jika pada sintaks for, inisialisasi iOuter=1 diubah menjadi ¡Outer=0, apa yang akibatnya? Mengapa bisa demikian?
jawab= Bintang tetap tercetak 5 baris (karena N = 5), tapi urutan perulangannya dimulai dari 0 sampai 4,Artinya, hasil tampilan sama, tapi cara menghitung iterasinya berbeda (dimulai dari 0 bukan 1)

2. Kembalikan program semula dimana inisialisasi iOuter=1. Kemudian perhatikan perulangan dalam, Jika pada sintaks for, inisialisasi i=1 diubah menjadi i=0, apa yang akibatnya? Mengapa bisa demikian?
jawab= Setiap baris akan berisi 6 bintang, bukan 5,Karena perulangan dimulai dari 0 sampai 5 → totalnya jadi 6 kali

3. Jadi, apakah perbedaan kegunaan antara perulangan luar dengan perulangan yang berada didalamnya?
jawab=Perulangan luar (outer loop): Mengatur jumlah baris
Perulangan dalam (inner loop): Mengatur jumlah bintang per baris

4. Mengapa perlu ditambahkan sintaks System.out.println(); di bawah perulangan dalam? Apa akibatnya jika sintaks tersebut dihilangkan?
jawab= Digunakan untuk pindah ke baris baru setelah satu baris bintang selesai.
Kalau dihapus, semua bintang akan tercetak dalam satu baris panjang

Jawaban percobaan 3 
1. Perhatikan, apakah output yang dihasilkan dengan nilai N = 5 sesuai dengan tampilan

berikut?

*
**
***
****
*****
jawab= Belum sesuai,Program menampilkan bintang tanpa pindah baris (semua bintang muncul dalam satu baris)

2. Jika tidak sesuai, bagian mana saja yang harus diperbaiki/ditambahkan? Jelaskan setiap bagian yang perlu diperbaiki/ditambahkan.
jawab= Kesalahan 1:
Tidak ada perintah untuk pindah ke baris baru setelah satu baris bintang selesai,tambahkan System.out.println(); setelah perulangan while (j < i) selesai


