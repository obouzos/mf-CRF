# mf-CRF: Conditional Random Field Model for Robust Multi-Focus Image Fusion
Includes the code and fused results for the method mf-CRF (Multi-Focus - Conditional Random Field) of the paper:

https://ieeexplore.ieee.org/abstract/document/8737867

## Abstract:
In this paper, a novel multi-focus image fusion algorithm based on conditional random field optimization (mf-CRF) is proposed. It is based on an unary term that includes the combined activity estimation of both high and low frequencies of the input images, while a spatially varying smoothness term is introduced, in order to align the graph-cut solution with boundaries of focused and defocused pixels. The proposed model retains the advantages of both spatial-domain methods and multi-spectral methods and by solving an energy minimization problem and finds an optimal solution for the multi-focus image fusion problem. Experimental results demonstrate the effectiveness of the proposed method that outperforms current state-of-the-art multi-focus image fusion algorithms in both qualitative and quantitative comparisons. In this paper, the successful application of the mf-CRF model in multi-modal image fusion (visible-infrared and medical) is also presented.

code will be available soon

## Citation:
If you find this useful in your research, please consider citing with the following Bibtex code:

```text
@article{mfCRF,
  author={Bouzos, Odysseas and Andreadis, Ioannis and Mitianoudis, Nikolaos},
  journal={IEEE Transactions on Image Processing}, 
  title={Conditional Random Field Model for Robust Multi-Focus Image Fusion}, 
  year={2019},
  volume={28},
  number={11},
  pages={5636-5648},
  keywords={Transforms;Image fusion;Estimation;Minimization;High frequency;Frequency estimation;Dictionaries;Conditional random field (CRF);multi-focus image fusion;energy minimization;independent component analysis (ICA)},
  doi={10.1109/TIP.2019.2922097}}
