
## Session: 2026-06-08 19:55
Day 1 COMPLETE: Fenz et al. DQN baseline working

Training results:
- 120,000 steps, 24,000 episodes, 6.6 minutes
- Peak reward: 7072 EUR/ha (Fenz et al. best: 7006 EUR/ha)
- Clean sequences: 85/100
- Final 500-ep mean: 1555 EUR/ha

Top sequence:
FIELD_BEANS -> POTATOES -> MILLET -> LENTILS -> CLOVER_GRASS -> HEMP
4752 EUR/ha, Final N: 390 kg/ha

Framework: PyTorch direct DQN
keras-rl2 incompatible with TF 2.16+ - rebuilt from scratch
Next: Week 1 Day 2 annotations, then Week 3 Canadian adaptation
