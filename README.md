# Negatte mo Nai Tsuihou Go kara no Slow Life? ~Intai Shita Hazu ga Nariyuki de Bishoujo Gal no Shishou ni Nattara Naze ka Mechakucha Natsukareta~

> Reito Harukaze, yang telah naik hingga ranking tertinggi adventurer, telah pensiun. Saat ia berniat untuk hidup santai dan pensiun, suatu hari seorang gadis gal cantik bernama Karen Hiiragi muncul di hadapannya.'Hey, onii-san, traktir makan dong!'Mendengar bahwa Karen kesulitan uang, Reito memutuskan untuk memberinya pelatihan dasar tentang cara menaklukkan dungeon.'Berkatmu, aku berhasil menyelesaikan dungeon pertamaku! Sensei!'Padahal sebenarnya ia ingin pensiun dan menikmati hidup santai…

---

## Info

| | |
|---|---|
| Judul | Negatte mo Nai Tsuihou Go kara no Slow Life? ~Intai Shita Hazu ga Nariyuki de Bishoujo Gal no Shishou ni Nattara Naze ka Mechakucha Natsukareta~ |
| Judul Alternatif | 願ってもない追放後からのスローライフ？～引退したはずが成り行きで美少女ギャルの師匠になったらなぜかめちゃくちゃ懐かれた～ |
| Author | Sugar Spoon |
| Artist | Yamigo |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Adventurer · Comedy · Drama · Fantasy · Romance · Gyaru · Shounen |
| Chapter | 13 chapter |

## Link

- [MangaDex](https://mangadex.org/title/748d2aab-cea8-4ffb-89b3-e716872cb027/negatte-mo-nai-tsuihou-go-kara-no-slow-life-intai-shita-hazu-ga-nariyuki-de-bishoujo-gal-no-shishou)
- [Raw](https://comic-walker.com/detail/KC_006563_S)

---

## Struktur

```
NegattemoNai/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)