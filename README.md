# Giga Gen Repository

This repository contains organized multimedia assets for the GigaGen competition submissions, categorized into distinct directories for **Videos**, **Audio**, **Images**, and **Documents**.

---

## 📁 Repository Structure

```text
Giga Gen repo/
├── audio/                          # Audio assets & music
│   └── Fun In The Jungle _ Upbeat Jungle Music For Media _ Cheerful Tribal Theme - (320 Kbps).mp3
├── documents/                      # PDF submissions & comics
│   ├── Document from Jai Sagulale__).pdf
│   ├── GIGAGEN_4.0_TheForgottenTemple_Comic by Kartik Barnalapdf.pdf
│   ├── kreatorsss.pdf
│   ├── PRAN-YANTRA by Mihir Dhanore(Topic 3).pdf
│   └── Team Codex Problem Statement 3.pdf
├── images/                         # Extracted comic panels and page images
│   ├── Document_Jai_Sagulale/      # 10 pages (JPG)
│   ├── PRAN_YANTRA/               # 10 pages (PNG)
│   └── TheForgottenTemple_Comic/   # 10 pages (JPG)
├── videos/                         # Video presentations & animations (Tracked with Git LFS)
│   ├── GigaGen Comic (Round 2 Aishwarya Lala Final Video).mp4
│   ├── Kartik Barnala (Topic 1) video.mp4 (132.89 MB - Git LFS)
│   ├── Mihir Dhanore (Topic 1) video.mp4 (183.73 MB - Git LFS)
│   └── Round 2 & 3 Submitted by Team Codex.mp4
├── .gitattributes                  # Git LFS tracking configuration
├── .gitignore                      # Git ignore patterns
└── README.md                       # Project documentation
```

---

## 📦 Media Catalog

### 🎬 Videos (`videos/`)
| File Name | Size | Git LFS Tracked |
| :--- | :--- | :---: |
| `GigaGen Comic (Round 2 Aishwarya Lala Final Video).mp4` | 9.90 MB | Yes |
| `Round 2 & 3 Submitted by Team Codex.mp4` | 8.90 MB | Yes |
| `Kartik Barnala (Topic 1) video.mp4` | 132.89 MB | Yes |
| `Mihir Dhanore (Topic 1) video.mp4` | 183.73 MB | Yes |

> **Note**: Files over 100 MB are tracked using [Git Large File Storage (Git LFS)](https://git-lfs.github.com) to comply with GitHub's file size policy.

### 🎵 Audio (`audio/`)
| File Name | Format | Size |
| :--- | :--- | :--- |
| `Fun In The Jungle _ Upbeat Jungle Music For Media _ Cheerful Tribal Theme - (320 Kbps).mp3` | MP3 Audio | 8.53 MB |

### 📄 Documents & Comics (`documents/`)
| File Name | Type | Size |
| :--- | :--- | :--- |
| `Document from Jai Sagulale__).pdf` | PDF Document / Comic | 2.28 MB |
| `GIGAGEN_4.0_TheForgottenTemple_Comic by Kartik Barnalapdf.pdf` | PDF Comic | 5.27 MB |
| `kreatorsss.pdf` | PDF Document | 1.06 MB |
| `PRAN-YANTRA by Mihir Dhanore(Topic 3).pdf` | PDF Presentation / Comic | 14.95 MB |
| `Team Codex Problem Statement 3.pdf` | PDF Problem Statement | 19.00 MB |

### 🖼️ Images (`images/`)
- **`TheForgottenTemple_Comic/`**: 10 high-resolution comic pages extracted from Kartik Barnala's submission (`kartik_comic_page_01.jpg` to `kartik_comic_page_10.jpg`).
- **`Document_Jai_Sagulale/`**: 10 high-resolution pages extracted from Jai Sagulale's submission (`jai_doc_page_01.jpg` to `jai_doc_page_10.jpg`).
- **`PRAN_YANTRA/`**: 10 high-resolution pages extracted from Mihir Dhanore's submission (`pran_yantra_page_01.png` to `pran_yantra_page_10.png`).

---

## 🚀 Cloning & Working with this Repository

To clone this repository and download all large media files:

```bash
# Clone the repository
git clone <YOUR-REPO-URL>

# Ensure Git LFS pulls the large video files
git lfs pull
```
