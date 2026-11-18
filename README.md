# vieneu-portable

Gói VieNeu-TTS portable cho VidTop Studio (Windows x64): CPython embeddable + `vieneu` + model cache, chạy CPU/ONNX, không cài gì vào Windows.
VidTop tải gói này khi bấm **Tải VieNeu** ở bước Âm thanh và kiểm tra sha256 ghim trong app.

Dựng bằng `desktop/scripts/build-vieneu-portable.cjs` của VidTop. Thành phần và giấy phép: `LICENSES.txt` trong gói
(CPython — PSF; vieneu, VieNeu-TTS-v3-Turbo, MOSS-Audio-Tokenizer-Nano-ONNX — Apache-2.0).

Chạy tay: giải nén rồi `run.cmd` (máy chủ chuẩn OpenAI ở http://127.0.0.1:8000).
