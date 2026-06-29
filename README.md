<div align="center">

# LexAI — Yerel Adli OCR

**Türkçe belge OCR sistemi — tamamen yerel (offline), C++ TensorRT motoru ile.**
PDF · UDF (UYAP) · Görsel · Office · dijital + tarama, yan-yana inceleme, konumlu render.

[![İndir](https://img.shields.io/badge/İndir-LexAI%20v0.9.0%20beta%20~2.9GB-2563eb?style=for-the-badge)](https://drive.google.com/uc?export=download&id=16VA4ngDw5SGiq6EHNNEYiLUVHTDXqFFo)

</div>

---

## Nedir?

LexAI, hukuk/adli belgeleri **yerelde** (buluta veri göndermeden) işleyen bir OCR ve belge-inceleme
uygulamasıdır. Dijital PDF'lerde gömülü metni OCR'sız çıkarır; taranmış/bozuk sayfalarda native C++
TensorRT motoruyla yüksek-kaliteli OCR yapar. ABBYY-tarzı iki-fazlı inceleme (yön + alan düzelt → onayla
→ OCR), tablo yapısı çıkarma ve orijinaline yakın konumlu render sunar.

- **Gizlilik:** Belgeler cihazdan çıkmaz. (Yalnız lisans/güncelleme kontrolü için anonim çağrı yapılır.)
- **Hız:** Sıcak/kalıcı TensorRT motoru; dijital sayfa OCR'sız.
- **Biçimler:** PDF, UDF (UYAP ZIP), görsel (PNG/JPG…), Office (docx/xlsx/txt).

## Sistem gereksinimleri

- **Windows 10/11 (x64)**
- **NVIDIA GPU + güncel sürücü** (TensorRT; ≥6–8 GB VRAM önerilir)
- ~? GB disk (model + motor + çalışma zamanı)

## Kurulum

1. [**LexAI v0.9.0 (beta) indir**](https://drive.google.com/uc?export=download&id=16VA4ngDw5SGiq6EHNNEYiLUVHTDXqFFo) → `LexAI_0.9.0_x64-setup.exe` (~2.9 GB).
2. Kurulumu çalıştır (yönetici/UAC). Windows "bilinmeyen yayıncı" derse: **Daha fazla bilgi → Yine de çalıştır**. İlk açılışta TensorRT motoru GPU'na göre bir kez hazırlanır (birkaç dakika).
3. Uygulama açılır; girdi klasörünü seç → **Analiz Et** → incele → **OCR Yap**.

## Lisans (deneme / trial)

LexAI **lisanslı** bir üründür ve **geçici deneme** olarak dağıtılır:
- İlk açılışta uygulama lisansını **çevrimiçi** doğrular (internet gerekir).
- Lisansınız yoksa / deneme süreniz dolmuşsa uygulama **çalışmaz** ve size bir **lisans kodu**
  (`LEXAI-XXXX-XXXX`) gösterir. Bu kodu yetkilinize iletin.
- Lisans makinenize bağlıdır (kopyalanamaz). Lisans iptal edilirse uygulama durur.

## Otomatik güncelleme

Uygulama açılışta yeni sürümü denetler; varsa **bildirim** gösterir. "Şimdi güncelle" ile imzalı kurulum
indirilir, doğrulanır ve kurulur.

## Destek

**GilTec** — Lisans / hata / talep için: **<gilikmehmet@gmail.com>** · **<https://giltec.com.tr>** (lisans kodunuzu ekleyin).

---

<div align="center"><sub>© LexAI · <b>GilTec</b> · giltec.com.tr · Native C++ TensorRT + Python servis + Tauri</sub></div>
