# Skinning Antarmuka

*Lihat juga: [Tutorial Skinning Antarmuka](/wiki/Skinning_Interface_Tutorial) and [Antarmuka](/wiki/Interface)*

Elemen skinning antarmuka digunakan dalam beberapa mode permainan atau bagian dari antarmuka pengguna klien.

## Menu utama

`menu-background.jpg`

![](img/menu-background.jpg)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | 1366x768 (lihat catatan) |

Catatan:

- [osu!supporter](/wiki/osu!supporter) dibutuhkan.
- Elemen ini diposisikan di tengah dan disetel untuk menutupi (isi seluruh lebar dan tinggi sambil mempertahankan rasio aspeknya, tetapi pangkas apa pun yang ada di luar jendela permainan).
- Biasanya, osu! mempunyai set background yang banyak dan berganti-ganti.
  - Jika elemen ini diskinkan dan pengguna mempunya tag osu!supporter, elemen ini akan menggantikan perilaku ini.
- Elemen ini digunakan sebagai arena bermain jika beatmap tidak memiliki latar belakang.
- Opsi latar belakang musiman dapat memengaruhi visibilitas elemen ini.
  - Jika ini diatur ke `Selalu` latar belakang musiman akan mengganti elemen ini.
  - Jika ini diatur ke `Kadang` latar belakang musiman akan mengganti elemen ini saat mereka sedang digunakan secara aktif.
- hanya menggunakan extensi `.jpg`.
  - Jika tipe elemen ini adalah `.png` ubah extensinya ke `.jpg`.
    - Jika backgroundnya transparan, background akan menjadi hitam.
- Pengguna bisa drag & drop elemen untuk menimpa gambar skin. **Ini akan menimpa gambar background di Folder!**

---

`welcome_text.png`

![](img/welcome_text.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |
Catatan:

- [osu!supporter](/wiki/osu!supporter) dibutuhkan.
- Elemen ini muncul ketika mengawali permainan klien.
- Elemen ini melipat keluar, membesar, dan memudar.

---

`menu-snow.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Aditif | Tengah | 32x32 |

Catatan:

- Jika tidak diskin, permainiannya akan menggunakan ikon mode kecil untuk menggantikannya.
- Harus dinyalakan di [pengaturan](/wiki/Options) untuk melihatnya.
  - Opsi ini mungkin diinyalakan otomatis pada hari liburan (Natal).

## Tombol

`button-left.png`

![](img/button-left.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Perkalian | Atas Kanan | - |

Catatan:

- Gunakan lebar yang sama dengan bagian tombol lainnya.
- Pewarnaan bervariasi menurut status tombol.

---

`button-middle.png`

![](img/button-middle.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Perkalian | Atas | - |

Catatan:

- Elemen ini diregangkan untuk memenuhi panjang tombol.
- Gunakan lebar yang sama dengan bagian tombol lainnya.
- Pewarnaan bervariasi menurut status tombol.

---

`button-right.png`

![](img/button-right.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Perkalian | Atas Kiri | - |

Notes:

- Gunakan lebar yang sama dengan bagian tombol lainnya.
- Pewarnaan bervariasi menurut status tombol.

## Kursor

`cursor.png`

![](img/cursor.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Biasanya, elemen ini akan memutar dan membesar (saat diklik).
- Perintah [skin.ini](/wiki/Skinning/skin.ini) :
  - Untuk menonaktifkan pembesaran (saat diklik), atur `CursorExpand` menjadi `0`.
  - Untuk menonaktifkan rotasi, atur `CursorRotate` menjadi `0`.

---

`cursormiddle.png`

![](img/cursormiddle.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Elemen ini tidak memutar dan membesar (saat diklik).
- Elemen ini ada diatas elemen `cursor.png`.

---

`cursor-smoke.png`

![](img/cursor-smoke.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Notes:

- Elemen ini muncul ketika Pemain menekan tombol Smoke.
  - Biasanya, tombol default Smoke adalah `C`.

---

`cursortrail.png`

![](img/cursortrail.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Elemen ini berada di bawah elemen `cursor.png`.
- Jika `cursormiddle.png` ada, jejak yang lebih panjang digunakan.
- Secara default, elemen ini tidak berputar.
- Perintah [skin.ini] (/wiki/Skinning/skin.ini) :
   - Untuk mengaktifkan putaran cursortrail, ubah `CursorTrailRotate` ke` 1`.

---

`cursor-ripple.png`

![](img/cursor-ripple.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Elemen ini digunakan saat pemain menekan tombol Klik Kiri atau Klik Kanan pada keyboard atau mouse mereka.
   - Secara default, tombol Klik Kiri terikat ke `Z`.
   - Secara default, tombol Klik Kanan terikat ke `X`.

## Ikon Mod

*Page Utama [Game Modifiers](/wiki/Game_modifier)*

---

`selection-mod-autoplay.png`

![](img/selection-mod-autoplay.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-cinema.png`

![](img/selection-mod-cinema.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Klik ikon Automod untuk melihat mod ini.

---

`selection-mod-doubletime.png`

![](img/selection-mod-doubletime.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-easy.png`

![](img/selection-mod-easy.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-fadein.png`

![](img/selection-mod-fadein.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-flashlight.png`

![](img/selection-mod-flashlight.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-halftime.png`

![](img/selection-mod-halftime.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-hardrock.png`

![](img/selection-mod-hardrock.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-hidden.png`

![](img/selection-mod-hidden.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Untuk [osu!mania](/wiki/Game_mode/osu!mania), Klik mod Fade in untuk melihat ikon ini.

---

`selection-mod-key1.png`

![](img/selection-mod-key1.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).
- Siklus melalui mod xK untuk melihat.

---

`selection-mod-key2.png`

![](img/selection-mod-key2.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).
- Siklus melalui mod xK untuk melihat.

---

`selection-mod-key3.png`

![](img/selection-mod-key3.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).
- Siklus melalui mod xK untuk melihat.

---

`selection-mod-key4.png`

![](img/selection-mod-key4.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-key5.png`

![](img/selection-mod-key5.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).
- Siklus melalui mod xK untuk melihat.

---

`selection-mod-key6.png`

![](img/selection-mod-key6.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).
- Siklus melalui mod xK untuk melihat.

---

`selection-mod-key7.png`

![](img/selection-mod-key7.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).
- Siklus melalui mod xK untuk melihat.

---

`selection-mod-key8.png`

![](img/selection-mod-key8.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).
- Siklus melalui mod xK untuk melihat.

---

`selection-mod-key9.png`

![](img/selection-mod-key9.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).
- Siklus melalui mod xK untuk melihat.

---

`selection-mod-keycoop.png`

![](img/selection-mod-keycoop.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-mirror.png`

![](img/selection-mod-mirror.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-nightcore.png`

![](img/selection-mod-nightcore.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Klik ikon mod DoubleTime untuk melihat ikon mod ini.

---

`selection-mod-nofail.png`

![](img/selection-mod-nofail.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-perfect.png`

![](img/selection-mod-perfect.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Klik ikon mod SuddenDeath untuk melihat ikon mod ini.

---

`selection-mod-random.png`

![](img/selection-mod-random.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!mania](/wiki/Game_mode/osu!mania).

---

`selection-mod-relax.png`

![](img/selection-mod-relax.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!](/wiki/Game_mode/osu!), [osu!taiko](/wiki/Game_mode/osu!taiko), dan [osu!catch](/wiki/Game_mode/osu!catch).
- This element is [osu!](/wiki/Game_mode/osu!), [osu!taiko](/wiki/Game_mode/osu!taiko), and [osu!catch](/wiki/Game_mode/osu!catch)-specific mod.

---

`selection-mod-relax2.png`

![](img/selection-mod-relax2.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!](/wiki/Game_mode/osu!).
- Mod ini akan otomatis memindahkan kursor dan pemain hanya butuh menekan tombol saja.

---

`selection-mod-scorev2.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-spunout.png`

![](img/selection-mod-spunout.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Elemen ini adalah spesifik [osu!](/wiki/Game_mode/osu!).

---

`selection-mod-suddendeath.png`

![](img/selection-mod-suddendeath.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

---

`selection-mod-target.png`

![](img/selection-mod-target.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Mod ini hanya tersedia di aliran stream cuttingedge.
- Elemen ini adalah spesifik [osu!](/wiki/Game_mode/osu!).

---

`selection-mod-freemodallowed.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Mod ini tidak memiliki gambar dalam game.
- Mod ini tidak muncul dalam pemilihan mod atau papan peringkat.
- Indikator untuk permainan dengan mod dan kombinasi tertentu.
  - Tidak muncul jika hanya 'Score V2', 'Auto', 'Double Time', 'Nightcore', atau 'Half Time' dengan sendirinya digunakan, kombinasi dengan mod lain termasuk mereka akan menampilkan mod tersebut.

---

`selection-mod-touchdevice.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

Catatan:

- Mod ini tidak memiliki gambar dalam game.
- Mod ini tidak muncul dalam pemilihan mod atau papan peringkat.
Indikator untuk permainan yang dilakukan menggunakan layar sentuh.
  - Klien menggunakan algoritme latar belakang untuk menghitung apakah permainan dilakukan dengan layar sentuh, jika terjadi terlalu banyak lengkungan kursor, hal itu mungkin diterapkan pada permainan.

## Offset wizard

*Halaman utama: [Offset Wizard](/wiki/Guides/How_to_Use_the_Offset_Wizard)*

---

`options-offset-tick.png`

![](img/options-offset-tick.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Perkalian | Tengah | - |

Catatan:

- Pewarnaan bervariasi menurut status centang.

## Playfield

`play-skip.png`

![](img/play-skip.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![Yes][true] | ![Yes][true] | Perkalian | Bawah Kanan | - |

Catatan:

- Nama Animasi: `play-skip-{n}.png`

---

`play-unranked.png`

![](img/play-unranked.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Multiplicative | Tengah | - |

Catatan:

- Elemen ini muncul ketika Pemain menonaktifkan submisi score.

---

`play-warningarrow.png`

![](img/play-warningarrow.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Multiplicative | Tengah | - |

Catatan:

- Status skinnable Beatmap diduga bug.
- Pewarnaan bervariasi menurut versi.
   - layar jeda:
     - semua versi: berwarna biru
   - istirahat keluar:
     - v1.0: berwarna putih
     - v2.0 +: berwarna merah

---

`arrow-pause.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Multiplicative | Tengah | - |

Catatan:

- Status skinnable Beatmap diduga bug.
- Jika diskin, elemen ini menimpa `play-warningarrow.png`.
- Elemen ini digunakan di menu pause dan layar gagal.
- Tidak diwarnai.

---

`arrow-warning.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] (lihat catatan) | Normal | Tengah | - |

Catatan:

- Status skinnable Beatmap diduga bug.
- Jika diskin, elemen ini menimpa `play-warningarrow.png`.
- Digunakan pada peringatan akhir istirahat.
- Tidak diwarnai.

---

`masking-border.png`

![](img/masking-border.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Kanan | maximal lebar: 768px |

Catatan:

- Digunakan ketika memainkan beatmap dengan storyboard 4:3 di widescreen.
- Ketika beatmapping, nonaktifkan `Widescreen support` di [song setup](/wiki/Beatmap_Editor/Song_Setup) untuk memunculkannya.
- Elemen ini diregangkan sesuai panjang kebutuhan.
- Pilar kanan dibalik secara horizontal.

---

`multi-skipped.png`

![](img/multi-skipped.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Bawah Kanan | 60x30 |

Catatan:

- Elemen ini digunakan saat permainan multi, terlihat di sebelah skor pemain (di samping) saat pemain memilih untuk melewati intro dari sebuah beatmap.

---

`section-fail.png`

![](img/section-fail.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Elemen ini terlihat ketika pemain memiliki jumlah HP yang rendah, sekitar kurang dari 50%, selama jeda yang cukup lama.

---

`section-pass.png`

![](img/section-pass.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Elemen ini terlihat ketika pemain memiliki jumlah HP yang tinggi, sekitar lebih dari 50%, selama jeda yang cukup lama.

### Hitung Mundur

`count1.png`

![](img/count1.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Tengah | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Ini harusnya bertuliskan "1" atau "3".

---

`count2.png`

![](img/count2.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Tengah | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Ini harusnya bertuliskan "2"

---

`count3.png`

![](img/count3.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Tengah | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Ini harusnya bertuliskan "3" atau "1".

---

`go.png`

![](img/go.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Ini harusnya bertuliskan "Go!".

---

`ready.png`

![](img/ready.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Ini harusnya bertuliskan "Are You Ready?" atau "Ready?".

### Semburan hit

*Halaman utama: [Skinning/FAQ § Ranking screen hierarchy](/wiki/Skinning/FAQ#ranking-screen-hierarchy)*

---

`hit0.png`

![](img/hit0.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (lihat catatan) | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Nama animasi: `hit0-{n}.png`
- Kecepatan animasi ditetapkan menjadi 60 FPS.
- Jika menggunakan animasi:
  - animasi tidak berputar, tetapi bingkai terakhir tetap ada hingga menghilang.
  - perilaku bingkai tunggal tidak digunakan.
---

`hit50.png`

![](img/hit50.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (lihat catatan) | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Nama animasi: `hit50-{n}.png`
- Kecepatan animasi ditetapkan menjadi 60 FPS.
- Jika menggunakan animasi:
  - animasi tidak berputar, tetapi bingkai terakhir tetap ada hingga menghilang.
  - perilaku bingkai tunggal tidak digunakan.

---

`hit100.png`

![](img/hit100.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (lihat catatan) | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Nama animasi: `hit100-{n}.png`
- Kecepatan animasi ditetapkan menjadi 60 FPS.
- Jika menggunakan animasi:
  - animasi tidak berputar, tetapi bingkai terakhir tetap ada hingga menghilang.
  - perilaku bingkai tunggal tidak digunakan.

---

`hit100k.png`

![](img/hit100k.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (lihat catatan) | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Nama animasi: `hit100k-{n}.png`
- Kecepatan animasi ditetapkan menjadi 60 FPS.
- Jika menggunakan animasi:
  - animasi tidak berputar, tetapi bingkai terakhir tetap ada hingga menghilang.
  - perilaku bingkai tunggal tidak digunakan.

---

`hit300.png`

![](img/hit300.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (lihat catatan) | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Nama animasi: `hit300-{n}.png`
- Kecepatan animasi ditetapkan menjadi 60 FPS.
- Jika menggunakan animasi:
  - animasi tidak berputar, tetapi bingkai terakhir tetap ada hingga menghilang.
  - perilaku bingkai tunggal tidak digunakan.

---

`hit300g.png`

![](img/hit300g.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (lihat catatan) | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Nama animasi: `hit300g-{n}.png`
- Kecepatan animasi ditetapkan menjadi 60 FPS.
- Jika menggunakan animasi:
  - animasi tidak berputar, tetapi bingkai terakhir tetap ada hingga menghilang.
  - perilaku bingkai tunggal tidak digunakan.

---

`hit300k.png`

![](img/hit300k.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (lihat catatan) | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Nama animasi: `hit300k-{n}.png`
- Kecepatan animasi ditetapkan menjadi 60 FPS.
- Jika menggunakan animasi:
  - animasi tidak berputar, tetapi bingkai terakhir tetap ada hingga menghilang.
  - perilaku bingkai tunggal tidak digunakan.

### Input overlay

`inputoverlay-background.png`

![](img/inputoverlay-background.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Atas Kanan | 193x55 |

Catatan:

- Elemen ini diposisikan pada ketinggian 320px.
- Karena gambar diputar, asal gambar itu sendiri adalah Kiri Atas.
- Elemen ini digunakan dalam [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch).
- Elemen ini diputar 90 derajat searah jarum jam dan diregangkan sebesar 1,05x dalam game.
- Harus diaktifkan [Pengaturan](/wiki/Options) untuk menggunakannya.

---

`inputoverlay-key.png`

![](img/inputoverlay-key.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Perkalian | Tengah | 43x46 |

Catatan:

- Elemen ini digunakan dalam [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch).
- Pemosisian bervariasi untuk setiap kunci:
   - Jarak 24px dari screenborder
   - K1 / L: pada tinggi 350px
   - K2 / R: pada ketinggian 398px
   - M1 / D: pada tinggi 446px
   - M2: pada tinggi 492px
- Dapat diaktifkan di [Pengaturan](/wiki/Options).
- Menyusut sebentar saat tombol ditekan.
- Pewarnaan bervariasi berdasarkan lokasi dan status tombol:
   - Putih, jika tombol tidak ditekan.
   - Kuning, jika tombol ditekan dan terletak di setengah bagian atas.
   - Ungu, jika tombol ditekan dan terletak di setengah bagian bawah.

### Layar Jeda

`pause-overlay.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 1366x768 |

Catatan:

- Saat game dijeda, playfield akan diredupkan dan file ini akan dihamparkan di atasnya.
- Elemen ini tidak akan meregang agar pas.
- Tinggi gambar penuh adalah 768px.
- Gambar yang lebih kecil ditampilkan dengan bingkai transparan sementara gambar yang lebih besar ditampilkan sebagian.
- Ini juga bisa menjadi file `.jpg` (dan bisa memiliki ekstensi` .jpg`).
   - osu! lebih memilih `.png` daripada` .jpg`.

---

`fail-background.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 1366x768 |

Catatan:

- Saat pemain gagal, playfield akan diredupkan dan file ini akan dihamparkan di atasnya.
- Elemen ini tidak akan meregang agar pas.
- Ini juga bisa menjadi file `.jpg` (dan bisa memiliki ekstensi` .jpg`).
   - osu! lebih memilih `.png` daripada` .jpg`.

---

`pause-back.png`

![](img/pause-back.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- Elemen ini diposisikan pada ketinggian 576px.
- Elemen ini terlihat di layar gagal dan jeda.

---

`pause-continue.png`

![](img/pause-continue.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

- Elemen ini diposisikan pada ketinggian 224px.
- This element is seen in the pause screen.

---

`pause-replay.png`

![](img/pause-replay.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Kanan | - |

Catatan:

- Elemen ini muncul di layar peringkat (setelah menyelesaikan peta atau melihat skor).
- Elemen ini diposisikan pada tinggi 672 piksel atau pada tinggi 576 piksel, jika `pause-retry.png` tidak tersedia.

---

`pause-retry.png`

![](img/pause-retry.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | - |

Catatan:

- Pemosisian bervariasi:
   - layar jeda atau gagal:
     - Center, diposisikan pada ketinggian 400px
   - layar peringkat:
     - Kanan, diposisikan pada ketinggian 576px
- Elemen ini muncul di layar peringkat setelah menyelesaikan peta dan di layar jeda dan gagal.

### Scorebar

`scorebar-bg.png`

![](img/scorebar-bg.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Atas Kiri | - |

Catatan:

- Elemen ini tidak memiliki batasan ukuran.
- Ketika digunakan di [osu!mania](/wiki/Game_mode/osu!mania), elemen ini diputar 90 derajat berlawanan jarum jam dan ditempatkan di bawah kanan dari panggung.

---

`scorebar-colour.png`

![](img/scorebar-colour.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![Yes][true] | ![Yes][true] | (Bervariasi) | Atas Kiri | - |

Catatan:

- Nama Animasi: `scorebar-colour-{n}.png`.
- Variasi mode Blend:
  - Dikalikan, jika `scorebar-marker.png` digunakan.
    - Berwarna hitam seiring waktu ketika mendekati zona kritis dan berwarna merah di zona kritis.
  - Normal, jika tidak.
- Variasi posisi:
  - jika marker digunakan, diposisikan di (12, 12).
  - Jika tidak, diposisikan di (5,16).
- Elemen ini tidak memiliki batasan ukuran.
- Ketika digunakan di [osu!mania](/wiki/Game_mode/osu!mania), elemen ini diputar 90 derajat berlawanan jarum jam dan ditempatkan di bawah kanan dari panggung.

---

`scorebar-ki.png`

![](img/scorebar-ki.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- `scorebar-marker.png` punya prioritas tinggi.
- element ini mewakili zona "passing".
- Elemen ini tidak digunakan dalam [osu!mania](/wiki/Game_mode/osu!mania).
- posisi-Y di 16; posisi-X ditempatkan di ujung dari `scorebar-colour.png` yang di-crop.

---

`scorebar-kidanger.png`

![](img/scorebar-kidanger.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- `scorebar-marker.png` punya prioritas tinggi.
- element ini mewakili zona "bahaya".
- Elemen ini tidak digunakan dalam [osu!mania](/wiki/Game_mode/osu!mania)
- posisi-Y di 16; posisi-X ditempatkan di ujung dari `scorebar-colour.png` yang di-crop.

---

`scorebar-kidanger2.png`

![](img/scorebar-kidanger2.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | - |

Catatan:

- `scorebar-marker.png` punya prioritas tinggi.
- element ini mewakili zona "kritis".
- Elemen ini tidak digunakan dalam [osu!mania](/wiki/Game_mode/osu!mania).
- posisi-Y di 16; posisi-X ditempatkan di ujung dari `scorebar-colour.png` yang di-crop.

---

`scorebar-marker.png`

![](img/scorebar-marker.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Aditif | Tengah | - |

Notes:

- If skinned, this element overrides the `scorebar-ki.png`, `scorebar-kidanger.png`, and `scorebar-kidanger2.png` elements.
- Jika diskin, elemen ini menimpa elemen `scorebar-ki.png`, `scorebar-kidanger.png`, dan `scorebar-kidanger2.png`.
- Marker ini memudar ketika pemain masuk ke zona kritis.
- Elemen ini tidak digunakan dalam [osu!mania](/wiki/Game_mode/osu!mania).
- posisi-Y di 16; posisi-X ditempatkan di ujung dari `scorebar-colour.png` yang di-crop.

### Nomor nilai

`score-0.png`

![](img/score-0.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-1.png`

![](img/score-1.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-2.png`

![](img/score-2.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-3.png`

![](img/score-3.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-4.png`

![](img/score-4.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-5.png`

![](img/score-5.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-6.png`

![](img/score-6.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-7.png`

![](img/score-7.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-8.png`

![](img/score-8.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-9.png`

![](img/score-9.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | - |

Catatan:

- Secara default, ini juga digunaakan di nomor kombo.
- Variasi mode blend:
  - Jika di gunakan di kounter kombo:
    - Di [osu!](/wiki/Game_mode/osu!) dan [osu!catch](/wiki/Game_mode/osu!catch), aditif untuk memperluas setelah gambar.
    - Selain itu di osu!catch, gambar setelahnya diwarnai menggunakan warna kombo buah
    - Di osu!mania, dikalikan.

---

`score-comma.png`

![](img/score-comma.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 5x14 |

Catatan:

- Secara default, Ini juga digunakan di nomor kombo.
- Elemen ini untuk akurasi.
- Penggunaannya tergantung pada bahasa yang Anda pilih.

---

`score-dot.png`

![](img/score-dot.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 5x14 |

Catatan:

- Secara default, Ini juga digunakan di nomor kombo.
- Elemen ini untuk akurasi.
- Penggunaannya tergantung pada bahasa yang Anda pilih.

---

`score-percent.png`

![](img/score-percent.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 12x14 |

Catatan:

- Elemen ini untuk akurasi.

---

`score-x.png`

![](img/score-x.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | (Bervariasi) | (Bervariasi) | 10x14 |

Catatan:

- Elemen ini adalah untuk kombo, hanya digunakan di [osu!](/wiki/Game_mode/osu!).
- Variasi mode blend:
  - Jika digunakan di kounter kombo:
    - Aditif untuk memperluas setelah gambar.


## Nilai Peringkat

`ranking-XH.png`

![](img/ranking-XH.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |

Catatan:

- Variasi posisi:
  - 192px jauh dari screenborder kanan
  - v1.0: di kelebaran 272px
  - v2.0+: di kelebaran 320px

---

`ranking-XH-small.png`

![](img/ranking-XH-small.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 34x40 |

Catatan:

- Variasi pusat:
  - Istirahat: Tengah
  - Panel pemilihan lagu: Left
  - Nilai pengguna: Centre

---

`ranking-X.png`

![](img/ranking-X.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |

Catatan:

- Variasi posisi:
  - 192px jauh dari screenborder kanan
  - v1.0: di kelebaran 272px
  - v2.0+: di kelebaran 320px

---

`ranking-X-small.png`

![](img/ranking-X-small.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 34x40 |

Catatan:

- Variasi pusat:
  - Istirahat: Tengah
  - Panel pemilihan lagu: Left
  - Nilai pengguna: Centre

---

`ranking-SH.png`

![](img/ranking-SH.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |

Catatan:

- Variasi posisi:
  - 192px jauh dari screenborder kanan
  - v1.0: di kelebaran 272px
  - v2.0+: di kelebaran 320px

---

`ranking-SH-small.png`

![](img/ranking-SH-small.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 34x40 |

Catatan:

- Variasi pusat:
  - Istirahat: Tengah
  - Panel pemilihan lagu: Left
  - Nilai pengguna: Centre

---

`ranking-S.png`

![](img/ranking-S.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |

Catatan:

- Variasi posisi:
  - 192px jauh dari screenborder kanan
  - v1.0: di kelebaran 272px
  - v2.0+: di kelebaran 320px

---

`ranking-S-small.png`

![](img/ranking-S-small.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 34x40 |

Catatan:

- Variasi pusat:
  - Istirahat: Tengah
  - Panel pemilihan lagu: Left
  - Nilai pengguna: Centre

---

`ranking-A.png`

![](img/ranking-A.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |

Catatan:

- Variasi posisi:
  - 192px jauh dari screenborder kanan
  - v1.0: di kelebaran 272px
  - v2.0+: di kelebaran 320px

---

`ranking-A-small.png`

![](img/ranking-A-small.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 34x40 |

Catatan:

- Variasi pusat:
  - Istirahat: Tengah
  - Panel pemilihan lagu: Left
  - Nilai pengguna: Centre

---

`ranking-B.png`

![](img/ranking-B.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |

Catatan:

- Variasi posisi:
  - 192px jauh dari screenborder kanan
  - v1.0: di kelebaran 272px
  - v2.0+: di kelebaran 320px

---

`ranking-B-small.png`

![](img/ranking-B-small.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 34x40 |

Catatan:

- Variasi pusat:
  - Istirahat: Tengah
  - Panel pemilihan lagu: Left
  - Nilai pengguna: Centre

---

`ranking-C.png`

![](img/ranking-C.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |

Catatan:

- Variasi posisi:
  - 192px jauh dari screenborder kanan
  - v1.0: di kelebaran 272px
  - v2.0+: di kelebaran 320px

---

`ranking-C-small.png`

![](img/ranking-C-small.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 34x40 |

Catatan:

- Variasi pusat:
  - Istirahat: Tengah
  - Panel pemilihan lagu: Left
  - Nilai pengguna: Centre

---

`ranking-D.png`

![](img/ranking-D.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Tengah | - |

Catatan:

- Variasi posisi:
  - 192px jauh dari screenborder kanan
  - v1.0: di kelebaran 272px
  - v2.0+: di kelebaran 320px

---

`ranking-D-small.png`

![](img/ranking-D-small.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | (Bervariasi) | 34x40 |

Catatan:

- Variasi pusat:
  - Istirahat: Tengah
  - Panel pemilihan lagu: Left
  - Nilai pengguna: Centre

## Ranking screen

`ranking-accuracy.png`

![](img/ranking-accuracy.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] (lihat catatan) | ![No][false] | Normal | Atas Kiri | - |

Catatan:

- Bisa dianimasikan, tapi hanya frame ke-0 yang digunakan.
  - Nama animasi: `ranking-accuracy-{n}.png`
- Variasi posisi:
  - v1.0: (291,500)
  - v2.0+: (291,480)

---

`ranking-graph.png`

![](img/ranking-graph.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Atas Kiri | min: 308x156 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Atas Kiri | min: 308x148 |

Catatan:

- Variasi posisi:
  - v1.0: (256,576)
  - v2.0+: (256,608)
- Kotaknya sendiri berukuran 301x141.
- 7 piksel pertama di atas dan di kiri harus transparan.
  - Di v1 itu digeser ke bawah sebesar 8px.

---

`ranking-maxcombo.png`

![](img/ranking-maxcombo.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] (see notes) | ![No][false] | Normal | Atas Kiri | - |

Catatan:

- Bisa dianimasikan, tapi hanya frame ke-0 yang digunakan.
  - Nama animasi: `ranking-maxcombo-{n}.png`
- Variasi posisi:
  - v1.0: (8,500)
  - v2.0+: (8,480)

---

`ranking-panel.png`

![](img/ranking-panel.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Atas Kiri | max height: 694px |
| 2.0+ | ![No][false] | ![No][false] | Normal | Atas Kiri | max height: 666px |

Catatan:

- Variasi posisi:
  - v1.0: (0,74)
  - v2.0+: (0,102)

---

`ranking-perfect.png`

![](img/ranking-perfect.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] (see notes) | ![No][false] | Normal | Tengah | - |

Notes:

- Bisa dianimasikan, tapi hanya frame ke-0 yang digunakan.
  - Nama animasi: `ranking-perfect-{n}.png`
- Variasi posisi:
  - v1.0: (320,688)
  - v2.0+: (416,688)

---

`ranking-title.png`

![](img/ranking-title.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Atas Kanan | - |

Catatan:

- 32px posisi-x jauh dari sisi kanan

---

`ranking-replay.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Kanan | - |

Catatan:

- Variasi posisi:
  - di lebar 672px.
  - di lebar 576px, Jike retry tidak tersedia.

---

`ranking-retry.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Kanan | - |

Catatan:

- Diposisikan di kelebaran 576px.
- Jika diskin, elemen ini mengganti `pause-retry.png`.

---

`ranking-winner.png`

![](img/ranking-winner.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![No][false] | Normal | Atas Kiri | 200x214 |

Catatan:

- Elemen ini hanya digunakan di [multi](/wiki/multi).

## Entri skor

`scoreentry-0.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-1.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Multiplicative | (varies) | 11x14 |

Notes:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-2.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-3.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-4.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-5.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-6.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-7.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-8.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-9.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 11x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam permainan dan cadangan masukan.
   - Untuk overlay input, label tombol awal tidak dapat di-skin.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
   - Overlay input: gunakan nilai `InputOverlayText` dari [skin.ini](/wiki/Skinning/skin.ini) atau hitam, jika tidak ditentukan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas
   - Peringkat: Kanan Atas
   - Hamparan masukan: Atas

---

`scoreentry-comma.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | (bervariasi) | 5x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam game.
- Elemen ini digunakan sebagai pemisah desimal.
   - Penggunaan tergantung pada bahasa yang Anda pilih.
- Pewarnaan tergantung penggunaan:
   - Skor: putih
   - Kombo: cyan
- Asal bervariasi pada penggunaan:
   - Skor: Kiri Atas
   - Kombo: Kanan Atas

---

`scoreentry-dot.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | Atas Kiri | 5x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam game.
- Elemen ini digunakan sebagai pemisah desimal.
   - Penggunaan tergantung pada bahasa yang Anda pilih.
- Berwarna putih.

---

`scoreentry-percent.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | Atas Kiri | 12x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam game.
- Elemen ini digunakan di game [Multi](/wiki/Multi) saat kondisi menang diatur ke Akurasi.
- Berwarna putih.

---

`scoreentry-x.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Dikalikan | Kanan Atas | 10x14 |

Catatan:

- Elemen ini digunakan untuk papan peringkat dalam game.
- Elemen ini digunakan sebagai simbol pengali.
- Warna cyan.

## Pemilihan Lagu

`menu-back.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![Yes][true] | ![No][false] | Normal | Kiri Bawah | 200x214 |

Catatan:

- Nama animasi: `menu-back-{n}.png`.
- Tombol kembali asli tidak dapat dikuliti.
   - Jika elemen ini dikuliti, elemen ini akan menimpa yang baru di mana-mana, kecuali untuk [options](/wiki/Options).

---

`menu-button-background.png`

![](img/menu-button-background.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Perkalian | Bawah Kiri | min: 690x85 |

Catatan:

- Skin versi 2.2+ dapat mendukung thumbnail (harus diaktifkan di [options](/wiki/Options)) untuk pemilihan lagu
   - Thumbnail diposisikan 9px dari batas gambar kiri
   - Ukuran thumbnail adalah 115x85
- Elemen ini digunakan di berbagai tempat:
   - papan skor dalam pemilihan lagu
   - tombol untuk kesulitan beatmap dalam pemilihan lagu
   - papan skor di sebelah kiri saat bermain
   - tombol yang menampilkan peta ketukan yang dipilih sambil menunggu di ruangan dalam multipemain
- Pewarnaan bervariasi menurut status tombol.
- 
---

`selection-mode.png`

![](img/selection-mode.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Atas Kiri | 92x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bawah Kiri | 92x90 |

Catatan:

- Di v1.0, pemosisian berjarak 87px dari bawah.

---

`selection-mode-over.png`

![](img/selection-mode-over.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Atas Kiri | 92x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bawah Kiri | 92x90 |

Catatan:

- Arahkan kursor ke `selection-mode.png` untuk melihat.
- Di v1.0, pemosisian berjarak 87px dari bawah.

---

`selection-mods.png`

![](img/selection-mods.png)

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notes:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-mods-over.png`

![](img/selection-mods-over.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notes:

- Hover over `selection-mods.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-random.png`

![](img/selection-random.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notes:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-random-over.png`

![](img/selection-random-over.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notes:

- Hover over `selection-random.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-options.png`

![](img/selection-options.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notes:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-options-over.png`

![](img/selection-options-over.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notes:

- Hover over `selection-options.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-tab.png`

![](img/selection-tab.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Multiplicative | Top Left | 142x24 |

Notes:

- Depending on the client's window size, 4 to 5 tabs will be displayed.

---

`star.png`

![](img/star.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Multiplicative | Centre | 50x50 |

Notes:

- This element is used for difficulty star ratings (seen in song selection).
  - v2.2+ will scale down the last star, if necessary
  - v2.1- will crop the last star, if necessary
- Tinting depends on the state of `menu-button-background.png`

---

`star2.png`

![](img/star2.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Additive | Centre | 24x24 |

Notes:

- This element is used for song selection (the stars that fly from right to left), cursor, kiai time, combobursts.

### Mode select

`mode-osu.png`

![](img/mode-osu.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Additive | Centre | 256x256 |

Notes:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!](/wiki/Game_mode/osu!) for this to see.

---

`mode-taiko.png`

![](img/mode-taiko.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Additive | Centre | 256x256 |

Notes:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!taiko](/wiki/Game_mode/osu!taiko) for this to see.

---

`mode-fruits.png`

![](img/mode-fruits.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Additive | Centre | 256x256 |

Notes:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!catch](/wiki/Game_mode/osu!catch) for this to see.

---

`mode-mania.png`

![](img/mode-mania.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Additive | Centre | 256x256 |

Notes:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!mania](/wiki/Game_mode/osu!mania) for this to see.

---

`mode-osu-med.png`

![](img/mode-osu-med.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | 128x128 |

Notes:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-taiko-med.png`

![](img/mode-taiko-med.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | 128x128 |

Notes:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-fruits-med.png`

![](img/mode-fruits-med.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | 128x128 |

Notes:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-mania-med.png`

![](img/mode-mania-med.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | 128x128 |

Notes:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-osu-small.png`

![](img/mode-osu-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Additive | Centre | 32x32 |

Notes:

- This element is on top of the `selection-mode.png` element.
- Select [osu!](/wiki/Game_mode/osu!) for this to see.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-taiko-small.png`

![](img/mode-taiko-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Additive | Centre | 32x32 |

Notes:

- This element is on top of the `selection-mode.png` element.
- Select [osu!taiko](/wiki/Game_mode/osu!taiko) for this to see.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-fruits-small.png`

![](img/mode-fruits-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Additive | Centre | 32x32 |

Notes:

- This element is on top of the `selection-mode.png` element.
- Select [osu!catch](/wiki/Game_mode/osu!catch) for this to see.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-mania-small.png`

![](img/mode-mania-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Additive | Centre | 32x32 |

Notes:

- This element is on top of the `selection-mode.png` element.
- Select [osu!mania](/wiki/Game_mode/osu!mania) for this to see.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

[true]: /wiki/shared/true.png
[false]: /wiki/shared/false.png
