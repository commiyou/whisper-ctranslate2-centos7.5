# build on centos 7.5

```bash
conda create --name whisper-ctranslate2 python=3.8
conda install av==10.0.0 -c conda-forge

conda install -c conda-forge rust
conda install cudnn  # 9.x is fine
pip install whisper-ctranslate2 
```
