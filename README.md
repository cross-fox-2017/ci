# ci
### Recap tugas dan penggunaan untuk travis CI
Akses travis menggunakan akun git
```
https://travis-ci.org
```
Travis akan mendeteksi repo pada akun git yang digunakan.
Tambahkan file '.travis.yaml' pada project yang akan kita gunakan untuk test travis, yang isi dari file .travis.yml tersebut adalah seperti berikut.
```
language: node_js
node_js:
  - 6
env:
- MY_VAR=EverythignIsAwesome
- NODE_ENV=TEST
- secure: "TsYgfDTXM9DhteoxruftAIm9qbcVFTfBbPmi/Mv9lGkDKZ/b4pputXgbfy2On7dsu5s9Bio/P4Nri61sgVHZm6AJIsNWf2D6Ggiz94oddr0r+7dPp9yqTziPQAKNmMSzCtLff9Dl4BSOiasy/aQy5M+NrD6kXex0xjZyTIEndzk="

//env hanya digunakan jika pada project kita menggunakan env
```
