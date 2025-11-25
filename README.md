# 🌿 Durian Leaf Disease Detection

Hệ thống phát hiện bệnh lá cây sầu riêng sử dụng Deep Learning (ResNet).

## 📋 Mô Tả

Dự án này xây dựng mô hình trí tuệ nhân tạo để phát hiện và phân loại các loại bệnh lá phổ biến trên cây sầu riêng, bao gồm:
- Lá khỏe mạnh (Healthy)
- Bệnh đốm lá (Leaf Spot)
- Bệnh thán thư (Anthracnose)
- Các bệnh khác (Other Diseases)

## 🎯 Mục Tiêu

- ResNet18: Accuracy 82-88%
- ResNet34: Accuracy 88-92%
- ResNet50: Accuracy >92%

## 🚀 Cài Đặt
```bash
# Clone repository
git clone <your-repo-url>
cd durian-disease-detection

# Tạo virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# hoặc
venv\Scripts\activate  # Windows

# Cài đặt dependencies
pip install -r requirements.txt
```

## 📊 Dataset

[Mô tả dataset của bạn ở đây]

## 🏃 Chạy Thử
```bash
# Training
python scripts/train_model.py --config configs/config_resnet18.yaml

# Evaluation
python scripts/evaluate_model.py --model-path models/checkpoints/resnet18/best_model.pth

# Inference
python scripts/inference.py --image path/to/image.jpg
```

## 📁 Cấu Trúc Dự Án

[Đã mô tả ở trên]

## 📈 Kết Quả

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| ResNet18 | TBD | TBD | TBD | TBD |
| ResNet34 | TBD | TBD | TBD | TBD |
| ResNet50 | TBD | TBD | TBD | TBD |

## 🖼️ Demo

[Screenshots hoặc link đến demo]

## 📝 License

[Your License]

## 👥 Contributors

[Your Name]