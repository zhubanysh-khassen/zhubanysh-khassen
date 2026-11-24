## Hi, I'm Zhubanysh 👋

Final-year IT Management student in Astana, Kazakhstan (KazUTB, graduating 2027).
I build **computer-vision pipelines** end to end, from training a detector to running it on cheap hardware. I also do **data analysis** in SQL and Python.
Each project below has its numbers and the reasons behind them written up in the README.

### Computer vision

| Project | What it shows | Key result |
|---|---|---|
| [aerial-object-detection](https://github.com/zhubanysh-khassen/aerial-object-detection) | YOLO26 fine-tuned on VisDrone drone imagery + SAHI sliced inference | small-object recall **0.25 → 0.44** |
| [edge-benchmark](https://github.com/zhubanysh-khassen/edge-benchmark) | One detector on GPU, CPU, OpenVINO INT8, RK3588 and Hailo-8L | **9.2 ms/frame** on a laptop CPU with no mAP loss |
| [traffic-counter-astana](https://github.com/zhubanysh-khassen/traffic-counter-astana) | YOLO26 + ByteTrack + OpenCV homography: vehicle counts and speed in km/h | per-vehicle CSV for traffic simulation |
| [pytorch-vehicle-classifier](https://github.com/zhubanysh-khassen/pytorch-vehicle-classifier) | Training loop in plain PyTorch, CNN from scratch vs transfer learning | **96.7%** with ResNet-18 |

### Data analysis

| Project | What it shows | Key result |
|---|---|---|
| [ps5-rental-sql-analysis](https://github.com/zhubanysh-khassen/ps5-rental-sql-analysis) | SQL case study: CTEs, window functions, cohort retention | referral customers: **+41% LTV** |

### Also built
- **[Poliglot](https://poliglot-37p.pages.dev)**: a language-learning web app built with React, TypeScript, Supabase and the Gemini API.
- **Video automation in Python**: an uploader that schedules YouTube videos through the YouTube Data API, plus a tool that uses OCR on frames to cut moments out of long recordings.

### Stack
`Python` `PyTorch` `Ultralytics YOLO` `OpenCV` `ONNX Runtime` `OpenVINO` `SQL` `pandas` `Git` `Linux/WSL2`

📫 Telegram [@zhukhas](https://t.me/zhukhas) · Languages: Kazakh, Russian, English
