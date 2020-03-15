Corona Tracker
===
Script sederhana untuk membuat tracking kasus untuk COVID19 Indonesia.
Data utama diambil dari kawan-kawan KawalCovid19 


Requirements
---
- Python 3
- matplotlib
- pandas
- pipenv

Installation
---
- `git clone https://github.com/lantip/coronatracking.git`
- `cd coronatracking`
- Jika belum punya pipenv, jalankan `pip install pipenv`
- Jalankan `pipenv install`

Usage
---
    Untuk menampilkan grafik tracking, tentukan layout yang akan dipakai. Pilihannya: kawai, spring, random, shell, planar
    $ python draw.py -l spring

Thanks To
---
- kawan-kawan di KawalCovid19

TO DO
---
- Mengumpulkan data untuk clustering berdasar wilayah