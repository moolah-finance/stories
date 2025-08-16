# 2. AI‑Driven Trend Identification

## 2.1 Pipeline  
1. **Data Ingestion**: News, research, social media  
2. **Preprocessing**: Tokenization, TF–IDF weighting  
3. **Pattern & Topic Detection**  
   - LDA for topic clusters  
   - Embedding drift for semantic shifts  
4. **Validation**  
   - Co-occurrence graphs  
   - Cross‑source confirmation (SDI, geographic spread)  

## 2.2 Scoring Metrics  
- **Trend Momentum**  
  \[ \text{Momentum}_t = \sum_{i=1}^t e^{-\lambda(t-i)} \times \text{Freq(theme, }i) \]  
- **Media Velocity**  
  \[ \frac{|\text{Articles}_t|}{|\text{Articles}_{t-\Delta t}|} \]  
- **Source Diversity**  
  \[ -\sum_i p_i \log p_i \]  

## 2.3 Mapping to Investments  
- **Direct beneficiaries**: >50% revenue exposure  
- **Indirect**: 20–50% exposure  
- **Enablers**: Infrastructure & tools  
