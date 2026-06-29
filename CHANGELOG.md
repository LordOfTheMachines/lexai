# LexAI — Sürüm Notları

## v0.9.0 (beta) — 2026-06-29

İlk genel beta. Native C++ TensorRT OCR + Python doküman katmanı + Tauri arayüz.

**Özellikler**
- Dijital + tarama OCR; sayfa-bazlı dijital/OCR kararı (UYAP bozuk-font sezgisi dahil).
- PDF · UDF (UYAP) · Görsel · Office; tür filtresi/gruplama.
- ABBYY-tarzı iki-fazlı inceleme: yön + alan düzelt → onayla → OCR. Zone editörü (poligon/palet, fit-to-page).
- Tablo çıkarma: kenarlıklı + kenarlıksız (metin-hizası) + taranmış tablolar; konumlu hücre render.
- Dijital sayfada olası veri-kaybı uyarısı (mürekkep-kaplama kontrolü).
- Yan-yana QC, konumlu render, zoom/pan, klavye ←/→ + mouse ileri/geri, Ctrl+Z/Ctrl+Y.
- Lisans (makineye bağlı, trial), telemetri ve imzalı otomatik güncelleme.

**Gereksinim:** Windows 10/11 x64 + NVIDIA GPU (güncel sürücü).
