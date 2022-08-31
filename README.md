# flutter_fundamental_3

#18 | Flutter Fundamental - Bagian 3

Praktikum 1: Menerapkan Gesture Detector
- On Tap: Mengklik hanya satu kali
![Praktikum1_OnTap](images/Praktikum1_OnTap.png)
- On Double Tap: Mengklik 2 kali
![Praktikum1_OnDoubleTap](images/Praktikum1_OnDoubleTap.png)
- On Long Press: Menahan beberapa detik
![Praktikum1_OnLongPress](images/Praktikum1_OnLongPress.png)

Praktikum 2: Menerapkan Input Widget dan Forms
- Validasi inputan sangat bermanfaat untuk pengisian sebuah forms, pembuat aplikasi bisa menyesuaikan value apa yang ingin di input ke dalam forms tersebut.
- Jika tidak sesuai maka akan ada pemberitahuan. Contohnya jika inputan dibiarkan kosong, maka akan muncul warning seperti pada contoh praktikum ini.
![Praktikum2_1](images/Praktikum2_1.png)
![Praktikum2_2](images/Praktikum2_2.png)
![Praktikum2_3](images/Praktikum2_3.png)
![Praktikum2_4](images/Praktikum2_4.png)

Praktikum 3: Menerapkan Custom Input dan FormField Widget
- Custom input ini hanya memperbolehkan angka 1-9 saja untuk diinputkan
- Ini dapat terjadi karena pada bagin file input_fields.dart terdapat kode program yang mengatur.
- Contoh kode program: inputFormatters: [
        FilteringTextInputFormatter.allow(RegExp("[0-9]")),
        LengthLimitingTextInputFormatter(6),
      ],
- Jadi jika menginputkan huruf maka tidak bisa
![Praktikum3_1](images/Praktikum3_1.png)
![Praktikum3_2](images/Praktikum3_2.png)
![Praktikum3_3](images/Praktikum3_3.png)