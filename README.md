# CropChain

AI-driven crop rotation planning for Canadian Prairie and Ontario agriculture.

## Status

**Day 1 Complete:** Fenz et al. 2023 DQN baseline running  
**Peak reward: 7072 EUR/ha** (beats paper benchmark of 7006 EUR/ha)  
**Clean sequences: 85/100**  

## Roadmap
- Week 3: Canadian Prairie crop adaptation
- Month 2: First farmer report delivered
- Month 9: YC application

## Scientific Foundation
- Fenz et al. (2023) Computers and Electronics in Agriculture 212, 108160
- Li et al. (2025) Advanced Science 12, e06590
- Yu et al. (2025) Molecular Plant 18, 1963-1982

## Architecture
PyTorch DQN | 4D state | 25 crops | 3 hidden layers (64-64-32)

| Metric | CropChain | Fenz et al. 2023 |
|--------|-----------|-----------------|
| Peak reward | 7072 EUR/ha | 7006 EUR/ha |
| Clean sequences | 85/100 | ~80/100 |
| Training time | 6.6 min | Not reported |
