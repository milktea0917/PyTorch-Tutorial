# PyTorch-Tutorial

This is a sample tutorial based on GPT’s learning schedule.

I’m using it to review what I’ve learned in the past, and I hope it can also be helpful for anyone currently studying PyTorch.

## 🎯 課程目標
熟悉 PyTorch 語法與架構

強化模型訓練流程（資料處理、模型建構、訓練、驗證）

練習實作常見模型（CNN、RNN、Transformer）

簡單介紹 PyTorch Lightning 與部署方法

## 🗓️ 25 天學習計畫（每日約 2 小時）
### 🧱 Week 1：PyTorch 基礎與張量操作
| Day |	主題 | 重點內容 |
| --- | --- | --- |
| 1 |	PyTorch 安裝與簡介 |	安裝、IDE設定、基本概念 |
| 2 |	Tensor 基礎 |	建立、形狀轉換、運算 |
| 3 |	Autograd 自動微分 |	requires_grad, backward() |
| 4 |	CUDA/GPU 操作 |	.to(device), GPU 加速 |
| 5 |	Dataset & DataLoader |	自定義資料集、batch 載入 |
| 6 |	模型定義方式 |	nn.Module、forward() |
| 7 |	優化器與損失函數 |	optimizer.step(), 常用 loss |

### 🧠 Week 2：實戰訓練流程 & CNN 模型
| Day |	主題 | 重點內容 |
| --- | --- | --- |
| 8 | 訓練與驗證流程整合 | loop 撰寫技巧、準確率統計 |
| 9 |	模型儲存與載入 |	torch.save(), load_state_dict() |
| 10 |	練習：MNIST | 手寫辨識	全流程實作 |
| 11 |	卷積層與池化層 |	nn.Conv2d, nn.MaxPool2d |
| 12 |	CNN 架構練習 |	自建 CNN 模型 |
| 13 |	CIFAR-10 資料集實作 |	image transforms, augmentation |
| 14 |	視覺化：tensorboard or matplotlib |	Loss 曲線、confusion matrix |

### 🔁 Week 3：進階模型與技巧
| Day |	主題 | 重點內容 |
| --- | --- | --- |
| 15 |	RNN/LSTM 簡介與實作 |	文字分類 or 時序預測 |
| 16 |	Transformer 基礎結構 |	nn.Transformer, attention |
| 17 |	預訓練模型使用 |	torchvision.models、Huggingface |
| 18 |	過擬合與正規化技巧 |	dropout, weight decay, early stopping |
| 19 |	學習率調整策略 |	scheduler 使用方法 |
| 20 |	多 GPU 訓練簡介 |	DataParallel, DistributedDataParallel |
| 21 |	測試集推論與部署 |	model.eval(), 推論效能優化 |

### ⚙️ Week 4：工具整合與小專題
| Day |	主題 | 重點內容 |
| --- | --- | --- |
| 22 |	PyTorch Lightning 簡介 |	結構化訓練流程 |
| 23 |	小專題構想與資料集準備 |	例如：貓狗分類、情緒分析等 |
| 24 |	小專題實作 |	模型訓練與結果呈現 |
| 25 |	專題總結與下一步 |	優化技巧、可再延伸主題推薦 |
