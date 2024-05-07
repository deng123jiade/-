# -
据集收集了真实的在线医患对话，并进行了多层次（Multi-Level）的人工标注，包含命名实体、对话意图、症状标签、医疗报告等。本次挑战赛选自其中的对话意图识别子任务。

#版本号

torch                        2.2.2+cu121  
tqdm                         4.66.1

模型：
Transformer_encoder


设置参数：

EMB_DIM = 768

HID_DIM = 256

N_LAYERS = 6

N_HEADS = 12

DROPOUT = 0.2

LEARNING_RATE = 0.00001

OUTPUT_DIM = 768

训练次数：599

准确率：：65.03%

