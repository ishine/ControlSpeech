# promptts baseline

CUDA_VISIBLE_DEVICES=0 python infer/promptTTS_infer.py  --exp_name promptts1_style_baseline  --hparams='seed=1200'
CUDA_VISIBLE_DEVICES=0 python infer/promptTTS_infer_one.py  --exp_name promptts1_style_baseline  --hparams='seed=1200'