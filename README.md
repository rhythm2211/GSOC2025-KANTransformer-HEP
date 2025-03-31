# GSOC2025-KANTransformer-HEP

## Overview  
This repository contains my work for GSoC 2025 under ML4SCI, focusing on **KAN-augmented Transformers for symbolic squared amplitude calculations in High-Energy Physics (HEP)**.

## Tasks Completed  

### Task 1.2: Dataset Preprocessing & Tokenization  
- Processed and tokenized **15,584** HEP sequences.  
- Normalized indices and structured data for model training.  

### Task 2: Vanilla Transformer Training & Evaluation  
- Trained a baseline Transformer model for next-token prediction.  
- Achieved **test sequence accuracy of 62.53%**.  

### Task 3.1: KANTransformer Implementation & Evaluation  
- Integrated **KAN layers** into the Transformer architecture.  
- Achieved a remarkable **test sequence accuracy of 97.75%** and **token accuracy of 99.98%**, demonstrating near-perfect precision in long-sequence predictions.  

## Next Steps  
- Further optimize **KANTransformer** with advanced attention mechanisms and hyperparameter tuning.  
- Expand dataset to improve generalization and robustness.  
- Integrate **symbolic validation** for physics consistency.  

## Results  
-  Task 1.2: Preprocessed 15,584 sequences  
-  Task 2: Vanilla Transformer → 62.53% seq accuracy  
-  Task 3.1: KANTransformer → **97.75% seq accuracy, 99.98% token accuracy**

