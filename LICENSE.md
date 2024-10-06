# Hasil Analisis

## Tujuan 
Analisis kualitas layanan untuk situs https://akademik.unsri.ac.id menggunakan Wireshark.

## Metrik QoS
- *Latency*: Waktu respons rata-rata.
- *Packet Loss*: Persentase paket yang hilang.
  

| Permintaan  | Waktu Permintaan (ms) | Waktu Respons (ms) | Latency (ms) |
|-------------|------------------------|---------------------|---------------|
| Request 1   | 30.151735             | 30.172080          | 0,02         |
| Request 2   | 30.172080            | 182.420179         | 152,2          |
| Request 3    | 182.420179            | 184.444906         |2,0         |
| Request 4   | 184.444906         | 1098.250874           | 913,8         | 
| Request 5   | 1098.250874       | 1098.358144            |   0,1          |

## Packet Loss
Packet Loss Rate= Jumlah Paket Hilang : Jumlah Paket Dikirim x 100% 
                = 519 : 4122 x 100% = 5,9 %


## Througputh
![Screenshot 2024-10-06 192017](https://github.com/user-attachments/assets/0b42953a-b4c4-4023-a16c-e445402ef982)



