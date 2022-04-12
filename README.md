# NLP - Character Level name Classification <br>
Author: Doğu Can ELÇİ, MS Student at Istanbul Technical University
<br>
# NLP FROM SCRATCH: CLASSIFYING NAMES WITH A CHARACTER-LEVEL RNN,Custom-RNN,CNN and Bi-LSTM <br>
In this project, approximately 20.000 tagged names from 18 languages were trained on a character basis using 8 different models, different batch-sizes and embedding-layers, and the results were shown.

Used models:<br>

1- Include Embedding Layer:

• CNN | batch-sizes: [128,64,32,16,8] <br>
• bi-LSTM | batch-sizes: [128,64,32,16,8] <br>
• nn.RNN | batch-sizes: [128,64,32,16,8] <br>
• Customized-RNN | batch-sizes: [128] <br>

2- Without Embedding Layer:

•  CNN | batch-sizes: [128,64,32,16,8] <br>
• bi-LSTM | batch-sizes: [128,64,32,16,8] <br>
• nn.RNN | batch-sizes: [128,64,32,16,8] <br>
• Customized-RNN | batch-sizes: [128] <br>
