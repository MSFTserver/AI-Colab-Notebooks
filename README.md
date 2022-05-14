# AI-Colab-Notebooks
AI colab Notebooks Made or edited by HostsServer aka MSFTserver

### NoteBooks

- #### [ESRGAN-4-VID.ipynb](ESRGAN-4-VID.ipynb)
  - Exports Frames from Video using [ffmpeg](https://www.ffmpeg.org/)
  - Runs them Through [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
  - Recompiles the video with ffmpeg.
 
- #### [Super_SloMo.ipynb](Super_SloMo.ipynb)
  - Makes a video slow motion
  - Given two consecutive frames, video interpolation aims at generating intermediate frame(s) to form both spatially and temporally coherent video sequences.
  - end-to-end convolutional neural network for variable-length multi-frame video interpolation
  - PyTorch implementation of "Super SloMo: High Quality Estimation of Multiple Intermediate Frames for Video Interpolation" by Jiang H., Sun D., Jampani V., Yang M., Learned-Miller E. and Kautz J. [Project](https://people.cs.umass.edu/~hzjiang/projects/superslomo/) [Paper](https://arxiv.org/abs/1712.00080)

- #### [VQGAN_Prompts_Generator.ipynb](VQGAN_Prompts_Generator.ipynb)
  - Generates a random prompt for a VQGAN+CLIP
  - based on a random selection of "things", "places", "colors", "styles", and "artists.
  - Credit to [dughogan](https://github.com/dughogan) orignal project on [Github](https://github.com/dughogan/VQGAN_Prompts)
 
- #### [NNST.ipynb](NNST.ipynb) / [NNST-Batch.ipynb](NNST-Batch.ipynb)
  - colab implementation of Neural Neighbor Style Transfer
  - based on nearest-neighbors that achieves higher quality stylization than prior work, without sacrificing content preservation
  - Credit to [nkolkin13](https://github.com/nkolkin13) orignal project on [Github](https://github.com/nkolkin13/NeuralNeighborStyleTransfer)
  - [Paper](https://ttic.uchicago.edu/~nickkolkin/Paper/NNST_Preprint.pdf)
