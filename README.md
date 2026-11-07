# ESP32 Interactive Learning Studio — Zero to Hero

Aplikasi pembelajaran interaktif ESP32 berbahasa Indonesia. Dibuat sebagai jalur belajar bertahap dengan inspirasi topik dari Random Nerd Tutorials.

## Jalur pembelajaran

1. **Fondasi:** mengenal ESP32, struktur program, Serial Monitor, variabel, operator dan kondisi.
2. **GPIO:** digital output, push button/input pull-up, PWM.
3. **Sensor dan data:** ADC, DHT, millis() dan debouncing.
4. **Wi-Fi dan web:** Station/Access Point, web server, HTTP request/API.
5. **IoT:** MQTT, data logging, dashboard.
6. **Capstone:** mini smart monitoring.

## Fitur

- 16 materi bertingkat dengan tujuan belajar dan komponen.
- Contoh sketch Arduino C++ yang dapat diedit.
- Wiring text untuk setiap materi.
- Animasi alur dan penyorotan instruksi secara bertahap.
- Virtual LED, input tombol dan slider analog.
- Panel Serial Monitor visual.
- Kuis per materi dan indikator progres.

## Menjalankan

Aplikasi berupa static website. Buka index.html atau aktifkan GitHub Pages dari branch main, folder /(root).

URL GitHub Pages: https://lamonecampa.github.io/esp32-interactive-studio/

## Batasan simulasi

Visualizer saat ini adalah alat bantu belajar, **bukan compiler C++ atau emulator ESP32**. Tombol Run/Step menelusuri baris kode dan memvisualisasikan beberapa pola output umum; belum mengeksekusi semua sintaks, percabangan, loop bersarang, library sensor, jaringan, atau timing perangkat keras secara akurat. Untuk menguji firmware sebenarnya, compile dan upload sketch menggunakan Arduino IDE atau PlatformIO pada board fisik.

## Referensi belajar

- Random Nerd Tutorials — Getting Started with ESP32: https://randomnerdtutorials.com/getting-started-with-esp32/
- ESP32 Digital Inputs and Digital Outputs: https://randomnerdtutorials.com/esp32-digital-inputs-outputs-arduino/
- ESP32 Tutorials and Projects: https://randomnerdtutorials.com/projects-esp32/
- Building an ESP32 Web Server: https://randomnerdtutorials.com/esp32-web-server-beginners-guide/

Materi dan urutan pembelajaran di repository ini disusun ulang. Kode contoh merupakan latihan edukatif, bukan salinan artikel.
