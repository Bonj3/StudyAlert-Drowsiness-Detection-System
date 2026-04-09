# StudyAlert-Drowsiness-Detection-System
StudyAlert-Drowsiness-Detection-System adalah sebuah sistem berbasis kecerdasan buatan yang dirancang untuk mendeteksi tingkat kantuk pengguna secara real-time selama aktivitas belajar. Dengan memanfaatkan teknologi computer vision dan analisis wajah, sistem ini mampu mengidentifikasi tanda-tanda kelelahan seperti mata tertutup, frekuensi kedipan, dan posisi kepala. Ketika tanda-tanda kantuk terdeteksi, sistem akan memberikan peringatan secara langsung untuk membantu pengguna tetap fokus dan produktif. Proyek ini ditujukan untuk meningkatkan efektivitas belajar, khususnya bagi mahasiswa atau pelajar yang sering mengalami kelelahan saat belajar dalam waktu lama.

📖 Penjelasan Detail
1. 🎯 Latar Belakang

Banyak pelajar dan mahasiswa mengalami penurunan konsentrasi akibat rasa kantuk saat belajar, terutama ketika belajar dalam durasi panjang atau di waktu malam. Hal ini dapat berdampak pada efektivitas belajar dan pemahaman materi. Oleh karena itu, diperlukan sebuah sistem otomatis yang mampu memonitor kondisi pengguna dan memberikan peringatan ketika terdeteksi tanda-tanda kelelahan.

2. 🧠 Tujuan Sistem
Mendeteksi kondisi kantuk pengguna secara real-time
Membantu pengguna menjaga fokus saat belajar
Mengurangi risiko kehilangan konsentrasi
Meningkatkan produktivitas dan efisiensi belajar
3. ⚙️ Cara Kerja Sistem

Sistem bekerja dengan menggunakan kamera (webcam) untuk memantau wajah pengguna. Proses utama meliputi:

Face Detection
Sistem mendeteksi wajah pengguna menggunakan model computer vision.
Eye Tracking & Blink Detection
Mengamati kondisi mata (terbuka/tertutup) dan menghitung durasi kedipan.
Drowsiness Detection
Jika mata tertutup dalam waktu tertentu atau terdeteksi pola kantuk, sistem mengklasifikasikan pengguna dalam kondisi mengantuk.
Alert System
Sistem akan memberikan notifikasi berupa suara atau visual sebagai peringatan.
4. 🛠️ Teknologi yang Digunakan
Python sebagai bahasa pemrograman utama
OpenCV untuk pengolahan citra dan video
Dlib / Mediapipe untuk facial landmark detection
NumPy untuk pengolahan data numerik
Alarm System (Sound/Popup) untuk notifikasi
5. 💡 Fitur Utama
Deteksi kantuk secara real-time
Monitoring mata dan wajah
Sistem peringatan otomatis
Ringan dan dapat dijalankan di laptop standar
Cocok untuk pelajar, mahasiswa, maupun pekerja
6. 📈 Manfaat
Membantu menjaga fokus saat belajar
Meningkatkan kualitas belajar
Mengurangi kebiasaan belajar sambil mengantuk
Dapat dikembangkan menjadi aplikasi edukasi yang lebih luas
7. 🚀 Pengembangan Selanjutnya
Integrasi dengan aplikasi e-learning
Dashboard statistik tingkat fokus pengguna
Notifikasi berbasis mobile
Penggunaan AI model yang lebih akurat (deep learning)
