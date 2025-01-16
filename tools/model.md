# GenAI語言模型工具清單

## 目錄
- [快速索引](#快速索引)
- [模型列表](#模型列表)
- [更新紀錄](#更新紀錄)

## 快速索引(待調整)

### 依開發地區
- [台灣模型](#tag-taiwan)
- [國際模型](#tag-international)

### 依開源狀態
- [開源模型](#tag-opensource)
- [閉源模型](#tag-closedsource)

### 依計費方式
- [Token計費](#tag-token-based)
- [訂閱制](#tag-subscription)
- [免費使用](#tag-free)

## 模型列表

### Commend-R

![國際](https://img.shields.io/badge/-國際-blue) ![開源](https://img.shields.io/badge/-開源-green) ![Token計費](https://img.shields.io/badge/-Token計費-orange)

**簡介**  
由 Cohere 公司研發的高度可擴展的語言模型家族，具有高性能和強大的準確性。

**基本資訊**
- 🔗 官網：https://cohere.com/command
- 🤖 開源連結：https://huggingface.co/collections/CohereForAI/c4ai-command-r-6604150f4c8ac7bea92963ed
- 💻 API支援：✅ 提供
- 🌐 研發據點：加拿大、美國

**計費方式**
- 依token計費
- 詳細價格：https://cohere.com/pricing

---

### Embed

![國際](https://img.shields.io/badge/-國際-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![Token計費](https://img.shields.io/badge/-Token計費-orange)

**簡介**  
Embed是領先的多模態嵌入模型，作為語義搜索和檢索增強生成(RAG)系統的智能檢索引擎。

**基本資訊**
- 🔗 官網：https://cohere.com/embed
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：加拿大、美國

**計費方式**
- 依token計費
- 詳細價格：https://cohere.com/pricing

---

### Rerank

![國際](https://img.shields.io/badge/-國際-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![搜尋計費](https://img.shields.io/badge/-搜尋計費-orange)

**簡介**  
Rerank為任何關鍵字或向量搜索系統提供強大的語義提升，無需進行任何系統重建或替換。

**基本資訊**
- 🔗 官網：https://cohere.com/rerank
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：加拿大、美國

**計費方式**
- 依搜尋次數計費
- 詳細價格：https://cohere.com/pricing

---

### TAIDE-LX-7B

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green) ![免費](https://img.shields.io/badge/-免費-yellow)

**簡介**  
由國科會支持的「可信任生成式AI發展先期計畫」(TAIDE)研發成果，以LLaMA2-7B為基礎，僅使用繁體中文資料預訓練的模型，適合進一步微調的使用情境。

**基本資訊**
- 🔗 官網：https://huggingface.co/taide/TAIDE-LX-7B
- 🤖 開源狀態：開源
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

**注意事項**
預訓練模型未經微調和偏好對齊，使用時請注意輸出安全性。

---

### Llama 3-TAIDE-LX-8B-Chat-Alpha1 

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green)

**簡介**  
由我國國科會支持的「可信任生成式AI發展先期計畫」(TAIDE)研發成果，以 LLaMA3-8B 為基礎，使用繁體中文資料預訓練 (continuous pretraining)，並透過指令微調(instruction tuning)強化辦公室常用任務和多輪問答對話能力，適合聊天對話或任務協助的使用情境。

**基本資訊**
- 🔗 官網：https://huggingface.co/taide/Llama3-TAIDE-LX-8B-Chat-Alpha1
- 🤖 開源連結：https://huggingface.co/taide/Llama3-TAIDE-LX-8B-Chat-Alpha1
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

### Llama-3-Taiwan-8B-Instruct

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green)

**簡介**  
Llama-3-Taiwan-8B 是一個由 MiuLab 基於 LLaMa 3 架構研發的專為台灣文化和繁體中文的語言模型系列 Project TAME (TAiwan Mixture of Experts) 之一，適用於多種 NLP任務，包括多輪對話、RAG、台灣在地化語言任務和其他與繁體中文密切相關的應用。

**基本資訊**
- 🔗 官網：https://github.com/MiuLab/Taiwan-LLM
- 🤖 開源連結：https://huggingface.co/yentinglin/Llama-3-Taiwan-8B-Instruct
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

### Llama-3-Taiwan-70B

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green)

**簡介**  
Llama-3-Taiwan-70B 是一個由 MiuLab 基於 LLaMa 3 架構研發的專為台灣文化和繁體中文的語言模型系列 Project TAME (TAiwan Mixture of Experts) 之一，適用於多種 NLP任務，包括多輪對話、RAG、台灣在地化語言任務和其他與繁體中文密切相關的應用。

**基本資訊**
- 🔗 官網：https://github.com/MiuLab/Taiwan-LLM
- 🤖 開源連結：https://huggingface.co/yentinglin/Llama-3-Taiwan-70B-Instruct
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

### Breeze-7B

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green) ![免費](https://img.shields.io/badge/-免費-yellow)

**簡介**  
由聯發科技聯發創新基地基於Mixtral-7B針對中文特殊情境優化所訓練的繁體中文大型語言模型。

**基本資訊**
- 🔗 官網：https://huggingface.co/collections/MediaTek-Research/breeze-7b-65a67144880ad716173d7d87
- 🤖 開源連結：https://huggingface.co/MediaTek-Research/Breeze-7B-Instruct-v1_0
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

### Breexe-8x7B

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green) ![免費](https://img.shields.io/badge/-免費-yellow)

**簡介**  
由聯發科技聯發創新基地基於Mixtral-8x7B針對中文特殊情境優化所訓練的繁體中文大型語言模型。

**基本資訊**
- 🔗 官網：https://huggingface.co/collections/MediaTek-Research/breexe-8x7b-65cd841ce7ef6d9c02fc56d9
- 🤖 開源連結：https://huggingface.co/MediaTek-Research/Breexe-8x7B-Instruct-v0_1
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

### Llama3.1-FFM

![台灣](https://img.shields.io/badge/-台灣-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![訂閱制](https://img.shields.io/badge/-訂閱制-purple)

**簡介**  
由台智雲推出的企業級大語言模型，專為繁體中文和多語言處理而設計，強化模型Function Calling能力與多語言擴充詞表，提升推論效率和準確性。

**基本資訊**
- 🔗 官網：https://tws.twcc.ai/service/llama3-1-ffm/
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

**計費方式**
- 採用訂閱制
- 詳細價格：https://docs.twcc.ai/docs/pricing

---

### FFM-Mistral

![台灣](https://img.shields.io/badge/-台灣-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![訂閱制](https://img.shields.io/badge/-訂閱制-purple)

**簡介**  
由台智雲推出的企業級大語言模型，基於Mistral AI開源模型以繁中語料優化而成，採用混合專家模型架構（MoE），能以低成本運算大量參數及資料，得到更精確的回答。

**基本資訊**
- 🔗 官網：https://tws.twcc.ai/service/ffm-mistral/
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

**計費方式**
- 採用訂閱制
- 詳細價格：https://docs.twcc.ai/docs/pricing

---

### FFM-Embedding

![台灣](https://img.shields.io/badge/-台灣-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![訂閱制](https://img.shields.io/badge/-訂閱制-purple)

**簡介**  
由台智雲推出的向量嵌入模型，提供增強語意搜尋的向量嵌入模型解決方案，可以將文本轉換為一組向量，進行文本解析、關鍵字分析、文本分類等任務。

**基本資訊**
- 🔗 官網：https://tws.twcc.ai/service/embedding/
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

**計費方式**
- 採用訂閱制
- 詳細價格：https://docs.twcc.ai/docs/pricing

---

### CaiGunn 34B

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green) ![免費](https://img.shields.io/badge/-免費-yellow)

**簡介**  
由亞太智能機器(APMIC)自行研發的開源模型，支援英文與中文，具備 4K Context window，可搭配 CaiGunn 平台進行微調。

**基本資訊**
- 🔗 官網：https://www.ap-mic.com/gpt
- 🤖 開源連結：https://huggingface.co/APMIC/caigun-lora-model-34B-v2
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

### Breeze-7B

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green) ![免費](https://img.shields.io/badge/-免費-yellow)

**簡介**  
由聯發科技聯發創新基地基於Mixtral-7B針對中文特殊情境優化所訓練的繁體中文大型語言模型。

**基本資訊**
- 🔗 官網：https://huggingface.co/collections/MediaTek-Research/breeze-7b-65a67144880ad716173d7d87
- 🤖 開源連結：https://huggingface.co/MediaTek-Research/Breeze-7B-Instruct-v1_0
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

### Breexe-8x7B

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green) ![免費](https://img.shields.io/badge/-免費-yellow)

**簡介**  
由聯發科技聯發創新基地基於Mixtral-8x7B針對中文特殊情境優化所訓練的繁體中文大型語言模型。

**基本資訊**
- 🔗 官網：https://huggingface.co/collections/MediaTek-Research/breexe-8x7b-65cd841ce7ef6d9c02fc56d9
- 🤖 開源連結：https://huggingface.co/MediaTek-Research/Breexe-8x7B-Instruct-v0_1
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

### Embed

![國際](https://img.shields.io/badge/-國際-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![Token計費](https://img.shields.io/badge/-Token計費-orange)

**簡介**  
由 Cohere 公司所研發多模態嵌入模型，作為語義搜尋和增強檢索生成（RAG）系統的智能檢索引擎。

**基本資訊**
- 🔗 官網：https://cohere.com/embed
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：加拿大、美國

**計費方式**
- 依token計費
- 詳細價格：https://cohere.com/pricing

---

### Rerank

![國際](https://img.shields.io/badge/-國際-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![搜尋計費](https://img.shields.io/badge/-搜尋計費-orange)

**簡介**  
由 Cohere 公司所研發，提供了強大的語義提升，無需大規模更換或替換即可提升關鍵詞或向量搜尋系統的搜尋質量。

**基本資訊**
- 🔗 官網：https://cohere.com/rerank
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：加拿大、美國

**計費方式**
- 依搜尋次數計費
- 詳細價格：https://cohere.com/pricing

---

### FFM-Mistral

![台灣](https://img.shields.io/badge/-台灣-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![訂閱制](https://img.shields.io/badge/-訂閱制-purple)

**簡介**  
由台智雲推出的企業級大語言模型，基於Mistral AI開源模型以繁中語料優化而成，採用混合專家模型架構（MoE），
能以低成本運算大量參數及資料，得到更精確的回答。

**基本資訊**
- 🔗 官網：https://tws.twcc.ai/service/ffm-mistral/
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

**計費方式**
- 採用訂閱制
- 詳細價格：https://docs.twcc.ai/docs/pricing

---

### FFM-Embedding

![台灣](https://img.shields.io/badge/-台灣-blue) ![閉源](https://img.shields.io/badge/-閉源-red) ![訂閱制](https://img.shields.io/badge/-訂閱制-purple)

**簡介**  
由台智雲推出的向量嵌入模型，提供增強語意搜尋的向量嵌入模型解決方案，可以將文本轉換為一組向量，
進行文本解析、關鍵字分析、文本分類等任務。

**基本資訊**
- 🔗 官網：https://tws.twcc.ai/service/embedding/
- 🤖 開源狀態：閉源
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

**計費方式**
- 採用訂閱制
- 詳細價格：https://docs.twcc.ai/docs/pricing

---

### CaiGunn 34B

![台灣](https://img.shields.io/badge/-台灣-blue) ![開源](https://img.shields.io/badge/-開源-green) ![免費](https://img.shields.io/badge/-免費-yellow)

**簡介**  
由亞太智能機器(APMIC)自行研發的開源模型，支援英文與中文，具備 4K Context window，
可搭配 CaiGunn 平台進行微調。

**基本資訊**
- 🔗 官網：https://www.ap-mic.com/gpt
- 🤖 開源連結：https://huggingface.co/APMIC/caigun-lora-model-34B-v2
- 💻 API支援：✅ 提供
- 🌐 研發據點：台灣

---

## 更新紀錄
- 2024/01/20: 補充所有模型資訊
- 2024/01/19: 初始化文件