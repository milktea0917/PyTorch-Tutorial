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
| 1 |	初學者入門範本 (for Google Colab) |	安裝、IDE設定、基本概念 |
| 2 |	Tensor 基礎與進階操作 |	建立、形狀轉換、運算 |
| 3 |	Autograd 自動微分 |	requires_grad, backward() |
| 4 |	CUDA/GPU 操作 |	.to(device)、確認 GPU 是否可用、掌握 .to()、.cuda()、.cpu() 的使用時機 |
| 5 |	Dataset & DataLoader | 使用 TensorDataset 與 DataLoader、練習用 Batch & Shuffle 輸入資料到模型中 |
| 6 |	完整訓練流程整合 |	了解標準訓練流程的五大步驟、練習建立 Loss & Optimizer、撰寫訓練迴圈並觀察 Loss 收斂情況 |
| 7 |	非線性資料建模與過擬合控制 |	對比不同模型表現（linear vs MLP）、避免過擬合的基本技巧（Dropout / L2 正則） |

### 🧠 Week 2：實戰訓練流程 & CNN 模型
| Day |	主題 | 重點內容 |
| --- | --- | --- |
| 8 | 訓練與驗證流程整合 | loop 撰寫技巧、準確率統計 |
| 9 |	模型儲存與載入 |	torch.save(), load_state_dict() |
| 10 |	練習：MNIST | 手寫辨識	全流程實作 |
| 11 |	卷積層與池化層 |	nn.Conv2d, nn.MaxPool2d |
| 12 |	Dropout 與正規化技巧 |	Dropout、Weight Decay、Data Augmentation 實驗設計與比較 |
| 13 |	CNN 架構進階實作 |	實作三種 CNN 結構，探討層數、kernel 組合、Dropout 效果 |
| 14 |		CIFAR-10 實作 |	CIFAR-10 載入、normalization、augmentation、acc/loss 曲線 |

### 🔁 Week 3：進階模型與技巧
| Day |	主題 | 重點內容 |
| --- | --- | --- |
| 15 |	學習率調整策略 |	使用 StepLR, ReduceLROnPlateau, CosineAnnealingLR 等進行實驗 |
| 16 |	視覺化進階 |	Grad-CAM、Feature Map 視覺化，配合 CNN 模型觀察特徵學習位置 |
| 17 |	Transfer Learning 實作 |	使用 ResNet18 進行遷移學習，freeze 部分層、fine-tune 設計 |
| 18 |	Early Stopping 與模型泛化 |	Validation loss 監控、early stopping、比較 overfit 測試 |
| 19 |	測試集推論與導出模型 |	model.eval(), torch.save, torch.jit.trace, ONNX 導出 |
| 20 |	小型專題規劃與模型調參 |	CIFAR10 / 貓狗分類練習，嘗試實作完整調參流程 |
| 21 |	專題驗證與推論展示 |	評估、推論呈現、TensorBoard/Matplotlib 可視化展示成果 |

### ⚙️ Week 4：工具整合與小專題
| Day |	主題 | 重點內容 |
| --- | --- | --- |
| 22 |	PyTorch Lightning 簡介 |	結構化訓練流程 |
| 23 |	小專題構想與資料集準備 |	例如：貓狗分類、情緒分析等 |
| 24 |	小專題實作 |	模型訓練與結果呈現 |
| 25 |	專題總結與下一步 |	優化技巧、可再延伸主題推薦 |
