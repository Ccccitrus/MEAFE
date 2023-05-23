## Dataset

### Bilingual datasets

The multi-modal version of DBP15K dataset comes from the [EVA](https://github.com/cambridgeltl/eva) repository, and the folder `pkls` of DBP15K image features should be downloaded according to the guidance of EVA repository, and the downloaded folder `pkls` is placed in the `data` directory of this repository.

The word embedding we used is `glove-6B`, you can download it from [glove](https://nlp.stanford.edu/data/glove.6B.zip), and unzip it into the `data/embedding` directory.

### Cross-KG datasets

The original cross-KG datasets (FB15K-DB15K/YAGO15K) comes from [MMKB](https://github.com/mniepert/mmkb), in which the image embeddings are extracted from the pre-trained VGG16. We use the image embeddings provided by [MMKB](https://github.com/mniepert/mmkb#visual-data-for-fb15k-yago15k-and-dbpedia15k) and transform the data into the format consistent with DBP15K. The converted dataset can be downloaded from [BaiduDisk](https://pan.baidu.com/s/1MLGBNyFjb9LLa4urCk4hCA) (the password is `stdt`), and placed them in the `data` directory.
