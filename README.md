# simbert-roformer_sim-pytorch
1. 本脚本全部基于[bert4torch](https://github.com/Tongjilibo/bert4torch)框架，主要是用pytorch复现[bert4keras](https://github.com/bojone/bert4keras)以及各种实例
2. 如果链接打不开，可能是因为源文件更新，可直接访问[bert4torch_example](https://github.com/Tongjilibo/bert4torch/tree/master/examples)

---
- [basic_language_model_simbert.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/basic/basic_language_model_simbert.py)：基础测试，测试[simbert](https://github.com/ZhuiyiTechnology/simbert)和[roformer-sim](https://github.com/ZhuiyiTechnology/roformer-sim)的生成效果和句子相似度效果。
- [task_seq2seq_simbert.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/seq2seq/task_seq2seq_simbert.py)：相似问生成，数据增广，参考[SimBERT](https://kexue.fm/archives/7427)
- [task_seq2seq_simbert_v2_***.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/seq2seq/task_seq2seq_simbert_v2_stage1.py)：相似问生成，数据增广，三个步骤：1-[弱监督](https://github.com/Tongjilibo/bert4torch/blob/master/examples/seq2seq/task_seq2seq_simbert_v2_stage1.py)，2-[蒸馏](https://github.com/Tongjilibo/bert4torch/blob/master/examples/seq2seq/task_seq2seq_simbert_v2_stage2.py)，3-[有监督](https://github.com/Tongjilibo/bert4torch/blob/master/examples/seq2seq/task_seq2seq_simbert_v2_supervised.py)，参考[SimBERT-V2](https://kexue.fm/archives/8454)
