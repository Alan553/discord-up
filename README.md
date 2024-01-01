# Penjelasan Metode Bot
1. metode_1.py = Script chat otomatis ke channel discord. Isi chat diambil dari file pesan.txt secara BERURUTAN, untuk chat-nya TIDAK DIHAPUS.
2. metode_2.py = Script chat otomatis ke channel discord. Isi chat diambil dari file pesan.txt secara BERURUTAN, untuk chat-nya DIHAPUS.
3. metode_3.py = Script chat otomatis ke channel discord. Isi chat diambil dari file pesan.txt secara RANDOM/ACAK, untuk chat-nya TIDAK DIHAPUS.
4. metode_4.py = Script chat otomatis ke channel discord. Isi chat diambil dari file pesan.txt secara RANDOM/ACAK, untuk chat-nya DIHAPUS.

# Setting
- Edit CHannel ID sesuai target chat.
- Edit Token API Discord.
- Edit Delay / Jeda Chat ( dalam satuan detik )


# Discord Push Level ( Isntall via Termux Android) 
```
pkg install git
```
```
git clone https://github.com/Alan553/discord-up
```
```
pkg install python
```
```
apt upgrade && update
```
```
pkg install openssl
```
```
pip install requests colorama
```
```
cd discord-up
```
```
python metode_1.py
```
```
python metode_2.py
```
```
python metode_2.py
```
```
python metode_4.py
```
- Pilih Metode Yang di Inginkan
