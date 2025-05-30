# Automation Store

Kumpulan **template flow otomatisasi**, **base knowledge AI**, dokumentasi tools, dan best practice lintas platform (Pekerja.ai, Zapier, n8n, Make, dsb).

## 📦 Struktur Repo

```
/platforms/
  ├─ pekerja_ai/
  │    ├─ flows/           # Contoh YAML flow otomatisasi
  │    ├─ templates/       # Template siap pakai (misal invoice, onboarding)
  │    ├─ gpts/            # Kumpulan prompt & base knowledge untuk AI/GPT
  │    └─ docs/            # Panduan & troubleshooting khusus Pekerja.ai
  ├─ zapier/
  │    ├─ flows/
  │    ├─ templates/
  │    ├─ gpts/
  │    └─ docs/
  ├─ n8n/
  ├─ make/
  └─ (platform lain...)
/examples/
  └─ ascii/                # Contoh dashboard/menu ASCII
/shared/
  ├─ knowledge/            # Pengetahuan dasar & tips universal (AI, automation)
  └─ tools/                # Integrasi, koneksi API, tips penggunaan tools
```

## 🚀 Cara Pakai

1. **Baca panduan & format flow** di `/platforms/{platform}/docs/`
2. Pilih/duplikat **template atau flow** dari `/flows` atau `/templates`
3. Edit sesuai use case bisnismu
4. Untuk implementasi AI/chatbot, cek juga koleksi **prompt & base knowledge** di `/gpts`
5. Ikuti troubleshooting jika ada error (lihat `/docs`)
6. Saling share, kontribusi, dan update best practice barumu

## 🌟 Kontribusi

* Tambahkan contoh flow, template, atau prompt baru ke folder platform terkait
* Tambahkan tips/panduan di `/shared/knowledge` jika universal
* Saran/PR: gunakan format YAML/Markdown, deskriptif & siap dipakai

---

**Catatan:**
Automation Store ini dibuat untuk mempermudah adopsi otomatisasi di berbagai platform, dari agency profesional sampai pemilik UMKM/kreator.
Cocok juga untuk kebutuhan rapid prototyping, demo, maupun produksi.

---

**Jika ingin ada struktur tambahan, atau contoh file/folder, mention saja!**
Kalau perlu script generator, index, atau template README untuk tiap platform, tinggal request juga.
