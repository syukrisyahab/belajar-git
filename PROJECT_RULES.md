# PROJECT RULES & GOVERNANCE: BELAJAR-GIT
# File: PROJECT_RULES.md
# Standard: AI-DEVELOPMENT-STANDARDS (Cluster: Tools, Utilities & Learning)

---

## 1. IDENTITAS & PERAN ARSITEKTUR
- **Repository**: `belajar-git`
- **Cluster**: Tools, Utilities & Learning
- **Teknologi Utama**: HTML
- **Deskripsi**: Tutorial Git dalam Bahasa Indonesia
- **Default Branch**: `master`

---

## 2. ATURAN PENGEMBANGAN MUTLAK (IMMUTABLE LOGIC)
1. **Preservasi Logika Eksisting**:
   - Dilarang menghapus atau mengubah logika atau konfigurasi yang sudah berfungsi tanpa persetujuan eksplisit.
2. **Kerahasiaan Kredensial**:
   - Dilarang menyimpan API keys, tokens, file `.env`, atau secrets ke dalam Git repository.
3. **Penyelarasan dengan Standar Master**:
   - Seluruh AI agent wajib merujuk ke repository master `AI-DEVELOPMENT-STANDARDS` untuk konvensi global.

---

## 3. STANDAR MULTI-AGENT HANDOFF
1. **Single Source of Truth**:
   - GitHub repository `belajar-git` adalah satu-satunya referensi sah. AI berikutnya wajib membaca `PROJECT_RULES.md` dan `AI_HANDOFF.md` sebelum menyentuh kode.
2. **Kepatuhan AI Handoff**:
   - Setiap akhir sesi yang memodifikasi kode atau dokumentasi wajib memperbarui `AI_HANDOFF.md` dan `CHANGELOG.md`.
