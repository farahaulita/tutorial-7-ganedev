# 1. Apa saja hal-hal positif yang kamu identifikasi dari pengalaman para pemain ketika mencoba game kelompok?
  Salah satu hal positif yang didapatkan dari survei adalah gameplay yang unik, berupa tower defense dengan sistem command line interface untuk membeli bangunan.
# 2. Apa saja hal-hal negatif (atau, pain points) yang kamu identifikasi dari pengalaman para pemain ketika mencoba game kelompok? 
  Beberapa hal negatif yang dilaporkan adalah kurangnya sebuah guide atau tutorial mengenai command dan tujuan dari game. Terdapat juga isu mengenai daerah out-of-vounds yang masih dapat dijelajahi pemain, segi kekurangan dari musik dan visual. Selain itu, feedback negatif lain berupa kurangnya fail condition karena game belum sepenuhnya selesai dan pathfinding yang dapat menyebabkan musuh terjebak.
# 3. Dari feedback-feedback yang telah diperoleh, apakah ada isu yang terkait pencapaian kondisi flow oleh pemain? 
## Misalnya, apakah ada tantangan di dalam game yang masih kurang tepat dengan kemampuan pemain pada level tertentu?
Sepertinya masih terdapat kesulitan mengenai tidak adanya tutorial dan guide untuk command pada terminal di game. Selain itu, baru terdapat satu jenis enemy yang masih terjebak di rintangan yang dapat menggangu flow permainan.
## Atau, apakah ada rancangan level di dalam game yang dirasa terlalu membosankan bagi pemain?
Sepertinya jenis enemy yang masih basic dan kurangnya variasi membuat permanian bersifat linear tanpa adah penambahan tantangan.
# 4. Dari jawaban kamu terhadap pertanyaan 1 hingga 3, tuliskan secara singkat, dalam bentuk bullet points, apa saja hal yang ingin kamu polish dan balance? 
- Melalukan revisi untuk aset yang digunakan agar lebih sesuai
- Melakukan penambahan dalam segi grafik dan musik
- Memperbaiki pathfinding musuh
- Menambah sebuah tutorial dan command yang dapat menampilkan seluruh command yang ada di game
- Menambahkan jenis enemy
- Memperbaiki daerah out of bounds
# 5. Untuk masing-masing poin di jawaban pertanyaan 4, jabarkan secara singkat (1 - 3 kalimat) mengenai rencana kerja kamu untuk mengimplementasikan usulan tersebut.
- Revisi aset akan dilakukan agar tampilan menjadi lebih baik, khususnya dari segi grafis. Akan dilakukan penggunaan aset dengan dengan resolusi yang lebih rendah (16 atau 32 bit) agar lebih sesuai dan memperbaiki beberapa tampilan bangunan.
- Mencari musik yang sesuai. UI menu dan in-game akan diperbaiki agar terlihat lebih sesuai dengan aset yang ada. Jika waktu cukup, dapat ditambahkan animasi yang lebih kompleks serta efek partikel dan shader.
- Memperbaiki pathfinding pada enemy agar dapat berputar dan mencari jalan lain jika terjebak.
- Mengimplementasikan sebuah command yang akan mendaftarkan seluruh command yang dapat digunakan oleh pemain. Dapat dibuat juga sebuah mode tutorial untuk membantu pemain mempelajari mekanisme permainan
- Enemy akan terus ditambahkan bedasarkan rancangan yang ada di dokumen GDD kelompok
- Out of Bounds akan diberikan sebuah wall collision yang akan menghalangi pergerakan pemain. Agr tidak kosong, daerah ini dapat diisi texture atau warna untuk membedakannya.
