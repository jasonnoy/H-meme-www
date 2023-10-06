Identifying Creative Harmful Memes via Prompt based Approach

Prerequisites: Google drive account access is necessary for downloading the harm dataset.

It is very simple to use our approach to train & apply a harmful meme detection model:
First, use vision-in-text module to generate a caption and a bunch of keywords as mentioned in our paper.
Second, use the h-meme model to train a harmful meme detection model, we used harmful-politics dataset as example, which contains the example we used in the following picture.

![image](https://github.com/jasonnoy/H-meme-www/assets/71385903/cecd8ca9-314e-496e-8d14-e4ccd6adaab4)

You can apply to any image-text dataset, thanks to the applicability of this approach.
Feel free to check out our original paper: https://dl.acm.org/doi/10.1145/3543507.3587427.

Use citation
@inproceedings{10.1145/3543507.3587427,
author = {Ji, Junhui and Ren, Wei and Naseem, Usman},
title = {Identifying Creative Harmful Memes via Prompt Based Approach},
year = {2023},
isbn = {9781450394161},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3543507.3587427},
doi = {10.1145/3543507.3587427},
booktitle = {Proceedings of the ACM Web Conference 2023},
pages = {3868–3872},
numpages = {5},
location = {Austin, TX, USA},
series = {WWW '23}
}
