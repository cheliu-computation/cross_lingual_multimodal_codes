# cross_lingual_multimodal_codes
multi-modal pretraining
## Files:Cancel changes
    .
    ├── Generate_mix_corpus/           # build cross-lingual vocaburay
    ├── multi-lingual_cxrbert/         # store cross-lingual cxr_bert
    ├── transformer/                   # cxrbert modeling codes
    ├── pretraining_CXRBert.py         # pretraining cxrbert codes
    ├── run_pretraining_cxrbert.sh     # pretraining cxrbert codes
    ├── starter_pretrain_cxrbert.py    # pretraining cxrbert codes

| Hyper-params | Loss | 
| ----- | ----- |
| 5 epochs 8 cards 1024 bz    | 0.6938 | 
| 5 epochs 16 cards 2048 bz   | 0.6715 | 
| 10 epochs 8 cards 1024 bz   | 0.5543 |
| 10 epochs 16 cards 2048 bz  | 0.5613 | 
| 15 epochs 8 cards 1024 bz   | 0.5296 | 
| 15 epochs 16 cards 2048 bz  | 0.5459 |
