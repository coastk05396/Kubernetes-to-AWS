# Kubernetes Deploy to AWS

### 使用技術
- JavaScript
- Node.JS
- MongoDB

### DevOps工具
- Kubernetes
- Docker
- Docker-Compose
- PostMan

### AWS 服務
- EKS
- EFS
- EC2
- Cloudformation
- VPS
---
1. EKS開機
2. 創建VPC 以利於EKS 內部Pod 連線
3. 利用 EFS CSI driver 與EKS連線 讓 Persistent Volume 映射進去

![](https://i.imgur.com/XesHj3h.png)


- 建立兩個 worker Node (EC2)

![](https://i.imgur.com/99M1OXL.png)


- 執行 kubectl get pods | 確認全部上線

![](https://i.imgur.com/XcPNgZZ.png)

- POSTMAN 測試 (200成功)

![](https://i.imgur.com/SEyh6e9.png)
