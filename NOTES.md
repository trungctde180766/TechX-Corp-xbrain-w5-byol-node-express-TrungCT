# NOTES

Strategy: serverless-http

Lý do chọn:
- Chỉ cần thêm 1 file mới (lambda.js), 3 dòng code
- Không chạm vào app.js
- Adapter tự xử lý việc chuyển đổi event API Gateway sang request/response của Express

Cold start đo được: 256.54 ms (Init Duration từ CloudWatch log)
![AWS Lambda Function Overview — byol-node-express with API Gateway trigger](image_2026-05-16_001558263.png)
