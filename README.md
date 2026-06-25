# RL_MM

Reinforcement Learning project.

## Files

- `PPO_MM_001.ipynb` — notebook with PPO training.
- `ppo_mmcore_sanity_cnn_v1_final.pt` — trained model weights.
- `btcusdt_depth5_1days.parquet` — dataset.

## Requirements

```bash
pip install torch pandas numpy gymnasium stable-baselines3
```

## Run

Open the notebook:

```bash
jupyter notebook PPO_MM_001.ipynb
```

## Results

The repository contains a PPO model trained on market depth data.
