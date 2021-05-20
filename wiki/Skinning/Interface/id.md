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
- Elemen ini melipat keeluar, membesar, dan memudar.

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

- Mod ini hanya tersedia di aliran stream cuttingedge.
- Elemen ini adalah spesifik [osu!](/wiki/Game_mode/osu!).

---

`selection-mod-freemodallowed.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

- Mod ini tidak memiliki gambar dalam game.
- Mod ini tidak muncul dalam pemilihan mod atau papan peringkat.
- Indikator untuk permainan dengan mod dan kombinasi tertentu.
  - Tidak muncul jika hanya 'Score V2', 'Auto', 'Double Time', 'Nightcore', atau 'Half Time' dengan sendirinya digunakan, kombinasi dengan mod lain termasuk mereka akan menampilkan mod tersebut.

---

`selection-mod-touchdevice.png`

| Versi | Dapat Dianimasikan | Beatmap Skinnable | Mode Blend | Asal | Ukuran SD Direkomendasikan |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Semua | ![No][false] | ![Yes][true] | Normal | Tengah | 64x64 |

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

Notes:

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

Notes:

- Digunakan ketika memainkan beatmap dengan storyboard 4:3 di widescreen.
- Ketika beatmapping, nonaktifkan `Widescreen support` di [song setup](/wiki/Beatmap_Editor/Song_Setup) untuk memunculkannya.
- Elemen ini diregangkan sesuai panjang kebutuhan.
- Pilar kanan dibalik secara horizontal.

---

`multi-skipped.png`

![](img/multi-skipped.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Bottom Right | 60x30 |

Notes:

- This element is used in multi games, seen next to the player's score (on the sides) when the player votes to skip the intro of a beatmap.

---

`section-fail.png`

![](img/section-fail.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- This element is seen when the player has a low amount of HP, about less than 50%, during a long enough break.

---

`section-pass.png`

![](img/section-pass.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- This element is seen when the player has a high amount of HP, about more than 50%, during a long enough break.

### Countdown

`count1.png`

![](img/count1.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Centre | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- This should either say "1" or "3".

---

`count2.png`

![](img/count2.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Right | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- This should say "2".

---

`count3.png`

![](img/count3.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Left | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- This should either say "3" or "1".

---

`go.png`

![](img/go.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- This should say "Go!".

---

`ready.png`

![](img/ready.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- This should say "Are You Ready?" or "Ready?".

### Hit bursts

*Main page: [Skinning/FAQ § Ranking screen hierarchy](/wiki/Skinning/FAQ#ranking-screen-hierarchy)*

---

`hit0.png`

![](img/hit0.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centre | - |

Notes:

- Animation name: `hit0-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit50.png`

![](img/hit50.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centre | - |

Notes:

- Animation name: `hit50-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit100.png`

![](img/hit100.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centre | - |

Notes:

- Animation name: `hit100-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit100k.png`

![](img/hit100k.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centre | - |

Notes:

- Animation name: `hit100k-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300.png`

![](img/hit300.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centre | - |

Notes:

- Animation name: `hit300-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300g.png`

![](img/hit300g.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centre | - |

Notes:

- Animation name: `hit300g-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300k.png`

![](img/hit300k.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centre | - |

Notes:

- Animation name: `hit300k-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.
- This element is not shown on the ranking screen.

### Input overlay

`inputoverlay-background.png`

![](img/inputoverlay-background.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Top Right | 193x55 |

Notes:

- This element is positioned at 320px height.
- Since the image is rotated, the origin on the image itself is Top Left.
- This element is used in [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch).
- This element is rotated 90 degrees clockwise and stretched by 1.05x in-game.
- Must be enabled in the [options](/wiki/Options) to see.

---

`inputoverlay-key.png`

![](img/inputoverlay-key.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Multiplicative | Centre | 43x46 |

Notes:

- This element is used in [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch).
- Positioning varies for each key:
  - 24px away from screenborder
  - K1/L: at 350px height
  - K2/R: at 398px height
  - M1/D: at 446px height
  - M2: at 492px height
- Toggleable in the [options](/wiki/Options).
- Shrinks briefly when the keys are pressed.
- Tinting varies by button location and state:
  - White, if key is not pressed.
  - Yellow, if the key is pressed and located on the top half.
  - Purple, if the key is pressed and located on the bottom half.

### Pause screen

`pause-overlay.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | 1366x768 |

Notes:

- When the game is paused, the playfield will be dimmed and this file will overlay on top of it.
- This element will not stretch to fit.
- Full image height is 768px.
- Smaller images are shown with transparent borders while larger images are partially shown.
- This can also be a `.jpg` file (and can have the `.jpg` extension).
  - osu! prefers `.png` over `.jpg`.

---

`fail-background.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | 1366x768 |

Notes:

- When the player has failed, the playfield will be dimmed and this file will overlay on top of it.
- This element will stretch to fit.
- This can also be a `.jpg` file (and can have the `.jpg` extension).
  - osu! prefers `.png` over `.jpg`.

---

`pause-back.png`

![](img/pause-back.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- This element is positioned at 576px height.
- This element is seen in the fail and pause screens.

---

`pause-continue.png`

![](img/pause-continue.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

- This element is positioned at 224px height.
- This element is seen in the pause screen.

---

`pause-replay.png`

![](img/pause-replay.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Right | - |

Notes:

- This element appears on the ranking screen (after finishing a map or viewing a score).
- This element is positioned at 672px height or at 576px height, if `pause-retry.png` is not available.

---

`pause-retry.png`

![](img/pause-retry.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | - |

Notes:

- Positioning varies:
  - pause or fail screen:
    - Centre, positioned at 400px height
  - ranking screen:
    - Right, positioned at 576px height
- This element appears on the ranking screen after finishing a map and on the pause and fail screens.

### Scorebar

`scorebar-bg.png`

![](img/scorebar-bg.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Top Left | - |

Notes:

- This element has no size restrictions.
- When used in [osu!mania](/wiki/Game_mode/osu!mania), this element is rotated 90 degrees anti-clockwise and is placed at the bottom right of stage.

---

`scorebar-colour.png`

![](img/scorebar-colour.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] | ![Yes][true] | (Varies) | Top Left | - |

Notes:

- Animation name: `scorebar-colour-{n}.png`.
- Blend mode varies:
  - Multiplicative, if `scorebar-marker.png` is used.
    - Tinted black over time when near critical zone and tinted red in the critical zone.
  - Normal, otherwise.
- Positioning varies:
  - If a marker is used, positioned at (12,12).
  - Otherwise, positioned at (5,16).
- This element has no size restrictions.
- When used in [osu!mania](/wiki/Game_mode/osu!mania), this element is rotated 90 degrees anti-clockwise and is placed at the bottom right of stage.

---

`scorebar-ki.png`

![](img/scorebar-ki.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- `scorebar-marker.png` has higher priority.
- This element represents the "passing" zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania).
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`

---

`scorebar-kidanger.png`

![](img/scorebar-kidanger.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- `scorebar-marker.png` has higher priority.
- this element represents the "warning" zone
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania)
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`

---

`scorebar-kidanger2.png`

![](img/scorebar-kidanger2.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | Centre | - |

Notes:

- `scorebar-marker.png` has higher priority.
- This element represents the "critical" zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania)
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`

---

`scorebar-marker.png`

![](img/scorebar-marker.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Additive | Centre | - |

Notes:

- If skinned, this element overrides the `scorebar-ki.png`, `scorebar-kidanger.png`, and `scorebar-kidanger2.png` elements.
- The marker fades out if the player reaches the critical zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania).
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`.

### Score numbers

`score-0.png`

![](img/score-0.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-1.png`

![](img/score-1.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-2.png`

![](img/score-2.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-3.png`

![](img/score-3.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-4.png`

![](img/score-4.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-5.png`

![](img/score-5.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-6.png`

![](img/score-6.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-7.png`

![](img/score-7.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-8.png`

![](img/score-8.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-9.png`

![](img/score-9.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notes:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-comma.png`

![](img/score-comma.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 5x14 |

Notes:

- By default, this is also used for the combo numbers.
- This element is for the accuracy.
- The usage is dependent on your selected language.

---

`score-dot.png`

![](img/score-dot.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 5x14 |

Notes:

- By default, this is also used for the combo numbers.
- This element is for the accuracy.
- The usage is dependent on your selected language.

---

`score-percent.png`

![](img/score-percent.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 12x14 |

Notes:

- This element is for the accuracy.

---

`score-x.png`

![](img/score-x.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | (Varies) | (Varies) | 10x14 |

Notes:

- This element is for the combo, only used in [osu!](/wiki/Game_mode/osu!).
- Blend mode varies:
  - If used for combo counter:
    - Additive for the expanding after images.

## Ranking grades

`ranking-XH.png`

![](img/ranking-XH.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | - |

Notes:

- Positioning varies:
  - 192px away from right screenborder
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-XH-small.png`

![](img/ranking-XH-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notes:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-X.png`

![](img/ranking-X.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | - |

Notes:

- Positioning varies:
  - 192px away from right screenborder
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-X-small.png`

![](img/ranking-X-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notes:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-SH.png`

![](img/ranking-SH.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | - |

Notes:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-SH-small.png`

![](img/ranking-SH-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notes:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-S.png`

![](img/ranking-S.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | - |

Notes:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-S-small.png`

![](img/ranking-S-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notes:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-A.png`

![](img/ranking-A.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | - |

Notes:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-A-small.png`

![](img/ranking-A-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notes:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-B.png`

![](img/ranking-B.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | - |

Notes:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-B-small.png`

![](img/ranking-B-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notes:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-C.png`

![](img/ranking-C.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | - |

Notes:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-C-small.png`

![](img/ranking-C-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notes:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-D.png`

![](img/ranking-D.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Centre | - |

Notes:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-D-small.png`

![](img/ranking-D-small.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notes:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

## Ranking screen

`ranking-accuracy.png`

![](img/ranking-accuracy.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] (see notes) | ![No][false] | Normal | Top Left | - |

Notes:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-accuracy-{n}.png`
- Positioning varies:
  - v1.0: (291,500)
  - v2.0+: (291,480)

---

`ranking-graph.png`

![](img/ranking-graph.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | min: 308x156 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Top Left | min: 308x148 |

Notes:

- Positioning varies:
  - v1.0: (256,576)
  - v2.0+: (256,608)
- The box itself is 301x141.
- The first 7 pixels at the top and at the left should be transparent.
  - In v1 it's shifted down by 8px.

---

`ranking-maxcombo.png`

![](img/ranking-maxcombo.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] (see notes) | ![No][false] | Normal | Top Left | - |

Notes:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-maxcombo-{n}.png`
- Positioning varies:
  - v1.0: (8,500)
  - v2.0+: (8,480)

---

`ranking-panel.png`

![](img/ranking-panel.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | max height: 694px |
| 2.0+ | ![No][false] | ![No][false] | Normal | Top Left | max height: 666px |

Notes:

- Positioning varies:
  - v1.0: (0,74)
  - v2.0+: (0,102)

---

`ranking-perfect.png`

![](img/ranking-perfect.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] (see notes) | ![No][false] | Normal | Centre | - |

Notes:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-perfect-{n}.png`
- Positioning varies:
  - v1.0: (320,688)
  - v2.0+: (416,688)

---

`ranking-title.png`

![](img/ranking-title.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Top Right | - |

Notes:

- x-position 32px away from the right side

---

`ranking-replay.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Right | - |

Notes:

- Position varies:
  - at 672px height.
  - at 576px height, if retry is not available.

---

`ranking-retry.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Right | - |

Notes:

- Positioned at 576px height.
- If skinned, this element overrides `pause-retry.png`.

---

`ranking-winner.png`

![](img/ranking-winner.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![No][false] | Normal | Top Left | 200x214 |

Notes:

- This element is used in [multi](/wiki/multi) only.

## Score entry

`scoreentry-0.png`

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

`scoreentry-3.png`

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

`scoreentry-4.png`

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

`scoreentry-5.png`

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

`scoreentry-6.png`

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

`scoreentry-7.png`

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

`scoreentry-8.png`

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

`scoreentry-9.png`

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

`scoreentry-comma.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Multiplicative | (varies) | 5x14 |

Notes:

- This element is used for the in-game leaderboards.
- This element is used as the decimal separator.
  - Usage depends on your selected language.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right

---

`scoreentry-dot.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Multiplicative | Top Left | 5x14 |

Notes:

- This element is used for the in-game leaderboards.
- This element is used as the decimal separator.
  - Usage depends on your selected language.
- Tinted white.

---

`scoreentry-percent.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Multiplicative | Top Left | 12x14 |

Notes:

- This element is used for the in-game leaderboards.
- This element is used in [Multi](/wiki/Multi) games when the win condition is set to Accuracy.
- Tinted white.

---

`scoreentry-x.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Multiplicative | Top Right | 10x14 |

Notes:

- This element is used for the in-game leaderboards.
- This element is used as the multiplier symbol.
- Tinted cyan.

## Song selection

`menu-back.png`

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![Yes][true] | ![No][false] | Normal | Bottom Left | 200x214 |

Notes:

- Animation name: `menu-back-{n}.png`.
- The native back button is not skinnable.
  - If this element is skinned, it will override the new one everywhere, except for the [options](/wiki/Options).

---

`menu-button-background.png`

![](img/menu-button-background.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| All | ![No][false] | ![Yes][true] | Multiplicative | Bottom Left | min: 690x85 |

Notes:

- Skin versions 2.2+ can support thumbnails (must be enabled in the [options](/wiki/Options)) for song selection
  - Thumbnails get positioned 9px away from the left image border
  - Thumbnail size is 115x85
- This element is used in various places:
  - scoreboards in song selection
  - button for the beatmap difficulty in song selection
  - scoreboards on the left while playing
  - button that shows the selected beatmap while waiting in a room in multiplayer
- Tinting varies by button state.

---

`selection-mode.png`

![](img/selection-mode.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | 92x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 92x90 |

Notes:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-mode-over.png`

![](img/selection-mode-over.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Top Left | 92x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 92x90 |

Notes:

- Hover over `selection-mode.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-mods.png`

![](img/selection-mods.png)

| Versions | Animatable | Beatmap Skinnable | Blend Mode | Origin | Suggested SD Size |
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
