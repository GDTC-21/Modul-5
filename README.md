# Modul-5

## Scenes !!
scene bisa dibilang sebagai layar/tampilan yang akan ditampilkan ke user. biasanya ketika user run game, maka akan tampil main menu yang bisaa kita sebut start scene, 
kemudian ada game scene dimana game utama kita akan dijalankan. kemudian ada game over scene yang akan ditampilkan ketika player mati/destoryed.

## Start Scene

start scene dibuat dengan membuat scene pada project folder 

kemudian menambahkan button pada scene lalu diberi script

script yang dibuat hanya untuk menjalankan fungsi dibawah untuk berpindah scene

```c#
  SceneManager.LoadScene();
```

## Game Scene

game scene adalah scene dimana kita sudah membuat game selama ini, dan pada saat player mati diberi fungsi dibawah untuk melanjutkan ke game over scene

```c#
  SceneManager.LoadScene();
```

## Game Over Scene

game over scene adalah scene dimana player sudah mati dan diberi pilihan untuk mengulang game ataupun kembali ke menu utama.
