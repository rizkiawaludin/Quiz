## About
Quiz adalah game yang saya buat dengan bahasa pemrograman `Python` yang kemudian saya encrypt menjadi `.pyc` dengan tujuan untuk mengamankan source code, tidak bisa di recode orang lain, dan agar kunci jawaban tidak diketahui. Game ini berbasis **CLI(Command Line Interface)**.
Game ini saya buat dengan tujuan untuk mengisi waktu bagi teman-teman semua yang sedang menjalani _self-quarantine_. Agar tidak bosan dan semoga game ini bisa membuat jengkel dan menghibur teman-teman semua.

## Installation
### Android
* Install Termux dari Play Store
* Buka Termux
* Kemudian masukkan perintah berikut
    ```
    $ termux-setup-storage
    ```
  > Izinkan termux untuk mengakses penyimpanan anda
* Kemudian masukkan perintah berikut
    ```
    $ pkg install python2
    ```
    > pastikan anda terkoneksi dengan internet
* Install git terlebih dahulu
    ```
    $ pkg install git
    ```
* Kemudian download game Quiz dengan perintah berikut
    ```
    $ git clone https://github.com/rizkiawaludin/Quiz
    ```
    > pastikan anda terkoneksi dengan internet
* Setelah selesai terdownload, ubah directory
    ```
    $ cd Quiz
    ```
* Kemudian jalankan game-nya dengan perintah berikut
    ```
    $ python2 quiz.pyc
    ```
* Enjoy the game

### Linux Ubuntu
* Buka Terminal
* Check your python version
    ```
    SM-Geek@SM-Geek-X441UV:~$ python --version
    ```
* Install git
    ```
    SM-Geek@SM-Geek-X441UV:~$ sudo apt-get install git-core
    ```
* Check your git version
    ```
    SM-Geek@SM-Geek-X441UV:~$ git --version
    ```
* Get the repositories of game
    ```
    SM-Geek@SM-Geek-X441UV:~$ git clone https://github.com/rizkiawaludin/Quiz
    ```
* Change directory to Quiz
    ```
    SM-Geek@SM-Geek-X441UV:~$ cd Quiz
    ```
* Execute the program
    ```
    SM-Geek@SM-Geek-X441UV:~/Quiz$ python quiz.pyc
    ```
* Enjoy the game
