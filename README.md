# Vũ Quốc Đạt

**NLP · Image–Text Retrieval · Computer Vision**

Các dự án mình tham gia cùng nhóm tại Đại học FPT, Đà Nẵng. Mỗi mục bên dưới có liên kết đến repo gốc và phần đóng góp cá nhân.

## Dự án đã tham gia

### [IMDb Sentiment Analysis](https://github.com/sotbatchien123/imdb-sentiment-revisited)

Phân loại cảm xúc review phim và phân tích cảm xúc theo 6 khía cạnh trên IMDb.

- **Phương pháp:** BERT + BiLSTM, fine-tune RoBERTa-large và nhãn silver từ Qwen3-8B.
- **Kết quả của nhóm:** Macro-F1 **96,74%** cho phân loại hai lớp; **74,19%** cho ABSA, đánh giá so với nhãn silver.
- **Đóng góp cá nhân:** thảo luận thiết kế nghiên cứu, rà soát bản thảo và đề xuất bổ sung `CITATION.cff` để hỗ trợ trích dẫn dự án — [PR #2](https://github.com/sotbatchien123/imdb-sentiment-revisited/pull/2).

[Repo gốc](https://github.com/sotbatchien123/imdb-sentiment-revisited) · [Bản fork của mình](https://github.com/DatVu6868/imdb-sentiment-revisited)

### [Image–Text Retrieval — DSCMR & CLIP4CMR](https://github.com/sotbatchien123/dscmr-clip4cmr-pascal)

Truy hồi ảnh từ văn bản và văn bản từ ảnh trên bộ dữ liệu Pascal Sentence.

- **Phương pháp:** tái lập DSCMR và CLIP4CMR; cải tiến đặc trưng, adapter và fine-tune nhánh ảnh.
- **Kết quả của nhóm:** CLIP4CMR đạt mAP@ALL **76,63%** (ảnh → văn bản) và **75,68%** (văn bản → ảnh), trung bình 5 seed trên tập test.
- **Đóng góp cá nhân:** rà soát và hoàn thiện thông tin các tài liệu tham khảo trong bài báo, gồm DOI và thông tin xuất bản — [PR #2 đã được merge](https://github.com/sotbatchien123/dscmr-clip4cmr-pascal/pull/2).

[Repo gốc](https://github.com/sotbatchien123/dscmr-clip4cmr-pascal) · [Bản fork của mình](https://github.com/DatVu6868/dscmr-clip4cmr-pascal)

### [Small Bird Detection — MVA 2023 SOD4SB](https://github.com/sotbatchien123/sod4sb-small-bird-detection)

Phát hiện chim nhỏ trong ảnh 4K, tập trung vào cách giữ độ phân giải và kết hợp các mô hình phát hiện.

- **Phương pháp:** YOLOv8-M với slicing và flip TTA; kết hợp GFL R50-FPN bằng Weighted Boxes Fusion.
- **Kết quả của nhóm:** **84,5% AP50** trên tập validation MVA 2023 SOD4SB đã rà soát.
- **Đóng góp cá nhân:** bổ sung phần kiểm tra trên split A/B và phần tập test công khai trong demo — [commit đóng góp](https://github.com/sotbatchien123/sod4sb-small-bird-detection/commit/5364b729a59f5ed6f2e23a8c161c117b9d96181e).

[Repo gốc](https://github.com/sotbatchien123/sod4sb-small-bird-detection) · [Bản fork của mình](https://github.com/DatVu6868/sod4sb-small-bird-detection)
