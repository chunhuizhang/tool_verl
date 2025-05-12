
```bash
python ./examples/data_preprocess/gsm8k_multiturn_w_tool.py --local_dir ./data/gsm8k
ln -s /mnt/buffer/zhangchunhui/checkpoints/ ./
sbatch ./examples/sglang_multiturn/run_qwen2.5-3b_gsm8k_multiturn_4xgpu.slurm
```
