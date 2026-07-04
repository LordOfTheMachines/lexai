# Üçüncü Taraf Bileşenler ve Açık Kaynak Atıfları — LexAI

LexAI, aşağıdaki üçüncü taraf açık kaynak ve yeniden dağıtılabilir bileşenleri içerir. Her bileşen kendi
lisansına tabidir; ilgili lisans şartları o bileşen bakımından LexAI Son Kullanıcı Lisans Sözleşmesi'ne (EULA)
göre önceliklidir. İlgili lisansların tam metinleri, projelerin resmî kaynaklarında ve uygulama kurulum
dizinindeki `licenses/` klasöründe yer alır.

> **Bağımsızlık / marka:** LexAI; PaddlePaddle, Baidu, NVIDIA, Microsoft, Artifex veya aşağıda anılan diğer
> projelerle **bağlantılı ya da onlar tarafından onaylanmış değildir**. Anılan ürün ve marka adları ilgili
> sahiplerine aittir; yalnızca uyumluluk/atıf amacıyla kullanılmıştır.

---

## Apache License 2.0
Aşağıdaki bileşenler **Apache License, Version 2.0** altında lisanslıdır (tam metin:
<https://www.apache.org/licenses/LICENSE-2.0>). Telif, patent, marka ve atıf bildirimleri korunmuştur.

| Bileşen | Telif / Sağlayıcı | Kaynak |
|---|---|---|
| **PaddleOCR** — PP-OCRv5 (algılama/tanıma) ve **PP-DocLayout-L** modelleri, `latin_dict` sözlüğü | © PaddlePaddle Authors | https://github.com/PaddlePaddle/PaddleOCR |
| **PaddlePaddle** (paddlepaddle 3.1.0) | © PaddlePaddle Authors | https://github.com/PaddlePaddle/Paddle |
| **PaddleX** (paddlex 3.4.3) | © PaddlePaddle Authors | https://github.com/PaddlePaddle/PaddleX |
| **Paddle2ONNX** (paddle2onnx) | © PaddlePaddle Authors | https://github.com/PaddlePaddle/Paddle2ONNX |
| **OpenCV** (opencv-python / -contrib 4.13) | © OpenCV team | https://github.com/opencv/opencv |
| **ONNX** (onnx 1.17) | © ONNX Contributors (LF AI & Data) | https://github.com/onnx/onnx |
| **RapidOCR** (rapidocr-onnxruntime) | © RapidAI | https://github.com/RapidAI/RapidOCR |
| **ONNX GraphSurgeon** (onnx_graphsurgeon) | © NVIDIA Corporation | https://github.com/NVIDIA/TensorRT |

> **Not (değişiklik bildirimi — Apache 2.0 §4):** LexAI, PaddleOCR modellerini ONNX'e aktarıp NVIDIA TensorRT
> ile hızlandırılmış native bir C++ çalışma zamanında kullanır; modellerin ağırlıkları değiştirilmemiştir.

## MIT / BSD / benzeri izinli lisanslar
| Bileşen | Lisans | Sağlayıcı |
|---|---|---|
| **ONNX Runtime** (onnxruntime, onnxruntime-gpu) | MIT | Microsoft |
| **FastAPI** | MIT | Sebastián Ramírez |
| **Starlette**, **Uvicorn** | BSD-3-Clause | Encode |
| **Pydantic** | MIT | Pydantic Services |
| **NumPy** | BSD-3-Clause | NumPy Developers |
| **Pillow** | MIT-CMU (HPND) | Jeffrey A. Clark ve katkıcılar |
| **openpyxl** | MIT | openpyxl |
| **python-docx** | MIT | Steve Canny |
| **zeyrek** | MIT | (Zemberek tabanlı morfoloji) |

## GNU AGPL-3.0 / ticari (Artifex)
| Bileşen | Lisans | Sağlayıcı |
|---|---|---|
| **PyMuPDF** (pymupdf, pymupdf4llm, pymupdf-layout) | **GNU AGPL-3.0** veya ticari lisans | Artifex Software (MuPDF) — https://mupdf.com |

## NVIDIA yeniden dağıtılabilir bileşenleri
CUDA®, cuDNN ve TensorRT™ çalışma-zamanı kütüphaneleri **NVIDIA yazılım lisansı / yeniden dağıtım şartlarına**
tabidir ve yalnızca LexAI ile birlikte kullanılabilir. © NVIDIA Corporation. https://developer.nvidia.com

## Yazı tipleri
| Yazı tipi | Lisans | Kaynak |
|---|---|---|
| **Oxanium**, **Space Mono** | SIL Open Font License 1.1 | Google Fonts |

---

*Bu belge bilgilendirme amaçlıdır; yasal bir görüş değildir. Tam uyum için lisans metinlerinin dağıtımla
birlikte sunulması ve gerekli hallerde hukuki danışmanlık alınması önerilir.*
