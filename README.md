<div align="center">

# LexAI — Yerel Adli OCR

**Türkçe hukuk/adli belge OCR sistemi — tamamen yerel (offline), native C++ TensorRT motoru ile.**
UYAP UDF · PDF · Görsel · Office · dijital + tarama · yan-yana inceleme · konumlu render

[![İndir](https://img.shields.io/badge/İndir-Kay%C4%B1t%20ol%20%26%20indir-162F82?style=for-the-badge)](https://hukuk.giltec.com.tr/)
[![Sürüm](https://img.shields.io/badge/s%C3%BCr%C3%BCm-0.9.9%20beta-EE862B?style=for-the-badge)](https://hukuk.giltec.com.tr/)
![Platform](https://img.shields.io/badge/Windows-10%2F11%20x64-5B6472?style=for-the-badge)
![Lisans](https://img.shields.io/badge/lisans-Tescilli%20(EULA)-5B6472?style=for-the-badge)

<sub>Bir <b>GilTec Hukuk</b> ürünü · giltec.com.tr</sub>

</div>

---

## Nedir?

LexAI, hukuk/adli belgeleri **cihazınızda — buluta hiçbir veri göndermeden** işleyen bir OCR ve belge-inceleme
uygulamasıdır. Dijital PDF'lerde gömülü metni OCR'sız çıkarır; taranmış/bozuk sayfalarda native C++ **TensorRT**
motoruyla yüksek-kaliteli OCR yapar. ABBYY-tarzı iki-fazlı inceleme (yön + alan düzelt → onayla → OCR), tablo
yapısı çıkarma ve orijinaline yakın konumlu render sunar. **Bilirkişiler, avukatlar ve adli uzmanlar** için.

## Öne çıkanlar

- 🔒 **Gizlilik önce** — belgeler cihazdan çıkmaz; işlem tamamen yerel (adli delil için tasarlandı).
- ⚡ **Native TensorRT hızı** — sıcak/kalıcı motor; temiz dijital sayfa OCR'sız, anında.
- 📄 **Her sayfaya doğru yöntem — otomatik** — dijital/tarama/karma sayfa kararını kendi verir.
- 🧩 **UYAP UDF + çok biçim** — UDF (ana metin + ekler), PDF, görsel, Office (docx/xlsx/txt).
- 🔳 **Tablo yapısı** — kenarlıklı + kenarlıksız tabloları konumlu hücrelerle çıkarır.
- 🖥️ **Yan-yana inceleme** — solda orijinal + tespit, sağda konumlu render; zoom/pan, klavye/mouse nav.
- 🔄 **Kendini yönetir** — sistem tepsisi ajanı + SHA-256 doğrulamalı otomatik güncelleme.

## Sistem gereksinimleri

- **Windows 10/11 (x64)**
- **NVIDIA GPU + güncel sürücü** (TensorRT; ≥6–8 GB VRAM önerilir)
- ~6 GB boş disk (model + motor + çalışma zamanı)

## Deneme sürümü / kurulum

1. **[hukuk.giltec.com.tr](https://hukuk.giltec.com.tr/)** üzerinden kayıt olup **etkinleştirme anahtarınızı** alın (30 günlük deneme).
2. `LexAI_0.9.9_x64-setup.exe` (~3.14 GB) installer'ını indirin ve çalıştırın. Windows "bilinmeyen yayıncı" derse: **Daha fazla bilgi → Yine de çalıştır** (installer imzasızdır; işlev etkilenmez).
3. Uygulamayı açın, **anahtarınızı girin** → deneme başlar (makinenize bağlanır). İlk açılışta TensorRT motoru GPU'nuza göre bir kez hazırlanır.
4. Girdi klasörünü seçin → **Analiz Et** → inceleyin → **OCR Yap** (çıktı: metin + tablo + `.md`).

## Otomatik güncelleme

Uygulama (ve arka plan ajanı) yeni sürümü denetler; varsa **bildirim** gösterir. "Güncelle" ile installer indirilir,
**SHA-256** ile doğrulanır ve kurulur.

## Açık kaynak / üçüncü taraf bileşenler

LexAI, açık kaynak ve yeniden dağıtılabilir bileşenler içerir. Başlıcaları **Apache License 2.0** altındaki
**PaddleOCR** (PP-OCRv5, PP-DocLayout modelleri), **PaddlePaddle**, **PaddleX**, **OpenCV**, **ONNX**, **RapidOCR**;
**MIT/BSD** altındaki ONNX Runtime, FastAPI, NumPy vb.; **AGPL-3.0/ticari** PyMuPDF; **NVIDIA** CUDA/cuDNN/TensorRT
yeniden dağıtılabilirleri; ve **SIL OFL** yazı tipleri. Tam atıf ve lisans listesi:
**[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)**.

> **Bağımsızlık:** LexAI; PaddlePaddle, Baidu, NVIDIA, Microsoft, Artifex, **T.C. Adalet Bakanlığı (UYAP)** veya
> anılan diğer kurum/projelerle bağlantılı ya da onlar tarafından onaylanmış **değildir**. "UYAP", "UDF" ve diğer
> ürün/marka adları ilgili sahiplerine aittir; yalnızca uyumluluk/atıf amacıyla kullanılmıştır.

## Lisans

LexAI **tescilli (proprietary)** bir üründür; açık kaynak değildir. Kullanım, **Son Kullanıcı Lisans Sözleşmesi
(EULA)** şartlarına tabidir → **[LICENSE](LICENSE)**. Telif Hakkı © 2026 **GilTec** (Mehmet Gilik). Tüm hakları saklıdır.

## İletişim

**GilTec Hukuk** — lisans / hata / talep için: **<gilikmehmet@gmail.com>** · **<https://giltec.com.tr>**
(lisans kodunuzu ekleyin).

---

<div align="center"><sub>LexAI, <b>GilTec</b>'in tescilli bir ürünüdür. © 2026 GilTec — tüm hakları saklıdır. · Native C++ TensorRT + Python servis + Tauri</sub></div>
