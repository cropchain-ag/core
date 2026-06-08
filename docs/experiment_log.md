# CropChain Experiment Log

## Day 1 - Fenz et al. Baseline - COMPLETE

### Training Results
- Steps: 120,000 | Episodes: 24,000 | Time: 6.6 min
- Peak reward: 7072 EUR/ha (Fenz et al. best: 7006 EUR/ha) BEATEN
- Clean sequences: 85/100
- Final 500-ep mean: 1555 EUR/ha
- Final violations/episode: 0.478

### Top Sequence
FIELD_BEANS -> POTATOES -> MILLET -> LENTILS -> CLOVER_GRASS -> HEMP
Total: 4752 EUR/ha | Final N: 390 kg/ha

### Errors Fixed
1. keras-rl2 incompatible with TF 2.16+: rebuilt in PyTorch
2. SB3 DummyVecEnv broke reward signal: direct training loop  
3. generate_sequences called wrong variable: model -> agent

### Next Session
Day 2: annotate every line of code
Week 3: Canadian Prairie adaptation
