# KOSMO2-2-MODEL
The KOSMOS-2 model was proposed in Kosmos-2: Grounding Multimodal Large Language Models to the World by Zhiliang Peng, Wenhui Wang, Li Dong, Yaru Hao, Shaohan Huang, Shuming Ma, Furu Wei.

KOSMOS-2 is a Transformer-based causal language model and is trained using the next-word prediction task on a web-scale dataset of grounded image-text pairs GRIT. The spatial coordinates of the bounding boxes in the dataset are converted to a sequence of location tokens, which are appended to their respective entity text spans (for example, a snowman followed by <patch_index_0044><patch_index_0863>). The data format is similar to “hyperlinks” that connect the object regions in an image to their text span in the corresponding caption.
