# MASTERKNOWLEDGE — Edit Video

Rumusan pengetahuan yang Claude guna untuk edit video. Sumber: plugin **Social Media Skills**
(Anthropic plugin directory) dan connector video yang disambung ke akaun ini.

> Harga, had dan ciri alat berubah setiap suku tahun. Semak dalam app sebelum langgan atau mula projek.

---

## 1. Peta laluan: alat mana untuk kerja apa

| Kerja | Alat | Skill / Framework |
|---|---|---|
| Video pendek (TikTok, Reels, Shorts), bawah ~15 minit | CapCut | `capcut` — **EDITS** |
| Podcast, temu bual, talking-head (edit ikut transkrip) | Descript | `descript` — **WORDS** |
| Video panjang → banyak klip pendek | OpusClip | `opus-clip` — **CLIPS** |
| Teknik umum klip + caption | Opus Clip / Submagic / CapCut | `captions-and-clipping` — **CLIP** |
| Jana video AI (B-roll, avatar, suara) | Veo, Kling, Luma, Runway, HeyGen, ElevenLabs | `ai-video` — **BRIEF** |

**Aliran biasa:** rakam → master dalam Descript → potong klip dalam OpusClip → gilap dalam CapCut
→ semakan manusia → jadual & publish.

---

## 2. EDITS — CapCut (video pendek)

- **E — Edit ikut skrip:** buang semua yang bukan dalam beat skrip. Hook dalam beberapa saat pertama; potongan terakhir jadi loop.
- **D — Drive the pace:** perubahan visual setiap ~2–4 saat (jump cut, punch-in, B-roll, teks). Sync dengan beat. Scrub untuk cari bahagian mati.
- **I — Ink the captions:** caption automatik + **semakan ketepatan wajib**. Simpan satu preset gaya. Reka untuk tonton tanpa bunyi. Export SRT/VTT bila perlu.
- **T — Tighten sound:** semak lesen muzik **sebelum** export. Muzik "Commercial use" CapCut biasanya hanya untuk TikTok/CapCut — YouTube/IG masih boleh kena claim.
- **S — Ship safe + to spec:** resolusi/fps ikut platform. Bahan klien/NDA **edit secara lokal, jangan sync** (ToS beri lesen kepada ByteDance atas fail yang di-upload).

Amaran: semak tier (Free/Standard/Pro) sebelum mula — ada ciri yang hanya boleh export dengan Pro.

---

## 3. WORDS — Descript (kandungan bercakap)

Prinsip: **transkrip ialah timeline — putuskan dalam teks, sahkan dengan telinga.**

- **W — Write the edit:** betulkan transkrip dahulu (nama, istilah). Potong tangent dan take buruk, buang filler + senyap (Underlord), susun semula dengan alih perenggan.
- **O — Overdub with consent:** suara sendiri sahaja, dengan pengesahan. Untuk satu dua perkataan; perenggan panjang = rakam semula.
- **R — Refine the sound:** Studio Sound sekali bagi setiap sumber. Seimbangkan aras suara. Bunyi bising teruk = rakam semula.
- **D — Dress the visuals:** Automatic Multicam, caption dari transkrip yang dah dibetulkan, B-roll yang diluluskan.
- **S — Ship the cuts:** satu transkrip → episod + klip + show notes + chapters + post teks.

Peraturan temu bual: **ringkaskan boleh, ubah maksud jangan.** Sejak Sept 2025, Descript guna minit media + kredit AI — import hanya apa yang akan diedit.

---

## 4. CLIPS — OpusClip (video panjang → klip)

- **C — Choose the source:** video perbualan paling sesuai (~8–12 calon/jam). Audio bersih, tiada sari kata terbakar. **Trim dulu** — 1 kredit = 1 minit video *sumber*.
- **L — Let AI find candidates:** set genre, panjang, AI hook. Guna carian momen bahasa biasa dan negative prompt (buang intro, iklan penaja).
- **I — Inspect and rank honestly:** Virality Score hanya untuk susun keutamaan, bukan kebenaran. Jangka ~40% klip dibuang. Setiap klip lulus 3 soalan: boleh berdiri sendiri? adil kepada penutur? berguna untuk penonton?
- **P — Polish the top few:** edit 3–5 terbaik sahaja. Betulkan ayat hook, caption, reframe, sempadan klip. Satu template jenama. Muzik auto **OFF**.
- **S — Ship on a drip:** jadualkan sepanjang minggu. Muat turun export segera. Banding retention sebenar dengan skor setiap bulan.

---

## 5. CLIP — Teknik umum klip & caption

- **C — Cut to the moment:** AI cari calon, manusia pilih yang lengkap dan bermula dengan hook.
- **L — Lay out vertical:** 9:16, subjek dijejak, dalam safe zone.
- **I — Inscribe captions:** caption perkataan demi perkataan, ~2 baris, semak transkrip.
- **P — Polish & publish clean:** tiada watermark platform lain (kena penalti Originality Score). Nyatakan jika diedit AI.

Corak biasa: **Opus Clip potong → Submagic caption → export bersih.** Setiap klip pendek arahkan semula ke video panjang asal.

---

## 6. BRIEF — Video AI

- **B — Brief the job, not the tool:** subjek, aksi, latar, cahaya/mood, kamera, aspek, durasi, audio, padanan jenama. Tiada nama vendor.
- **R — Route by fit:** B-roll → Veo 3.1 / Kling 3.0 / Luma / Runway. Avatar → HeyGen / Synthesia. Suara → ElevenLabs.
- **I — Iterate cheaply:** uji konsep pada alat murah, siapkan pada alat berkualiti.
- **E — Edit & assemble:** klip AI ialah bahan mentah; manusia yang sambung.
- **F — Finalize & disclose:** label AI ikut platform.

Jangan guna: **OpenAI Sora** (ditutup). Orang sebenar atau produk sebenar → **rakam**, jangan jana.

---

## 7. Garis merah (semua alat)

1. **Manusia semak dan lulus setiap edit** — AI tak boleh "tengok" video.
2. **Semak ketepatan caption** — caption salah = kesilapan yang diterbitkan.
3. **Lesen muzik/aset** disemak bagi setiap platform destinasi.
4. **Tiada deepfake / klon suara orang lain** tanpa izin.
5. **Nyatakan penggunaan AI** (EU AI Act, label TikTok, YouTube Altered Content).
6. **Klip kekalkan konteks** — jangan putar belit kata-kata orang.
7. **Jangan reka angka** — metrik dibaca dari dashboard platform sendiri.

---

## 8. Connector yang disambung (boleh edit terus)

| Connector | Fungsi |
|---|---|
| AI Producer by OpusClip | Transkripsi, caption, B-roll, kesan bunyi, framing speaker, export |
| Descript | Agent Underlord: trim, buang filler, caption, klip sosial, publish |
| HeyGen HyperFrames | Projek video HTML (compose/render tidak boleh dari Claude Code) |
| Epidemic Sound | Muzik & kesan bunyi berlesen |

---

## 9. Skill berkaitan

`short-form-video-script`, `reels-script`, `tiktok-script`, `youtube-shorts`, `youtube-long-form`,
`talking-head-and-piece-to-camera`, `ai-voiceover`, `ai-music-and-sound`, `thumbnail-design`,
`podcast-and-audiograms`, `heygen`, `veo-3`, `kling`, `luma`, `runway`, `synthesia`.
