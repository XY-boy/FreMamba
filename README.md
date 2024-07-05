# FreMamba
### 📖[**Paper**](https://ieeexplore.ieee.org/document/10387229) | 🖼️[**PDF**](/fig/TTST.pdf)

PyTorch codes for "[Frequency-Assisted Mamba for Remote Sensing Image Super-Resolution](https://ieeexplore.ieee.org/document/10387229)", **IEEE Transactions on Multimedia (TMM)**, under review.

- Authors: [Yi Xiao](https://xy-boy.github.io/), [Qiangqiang Yuan*](http://qqyuan.users.sgg.whu.edu.cn/), [Kui Jiang](https://homepage.hit.edu.cn/jiangkui?lang=zh), [Yuzeng Chen](https://jianghe96.github.io/), [Qiang Zhang](https://qzhang95.github.io/), and [Chia-Wen Lin](https://www.ee.nthu.edu.tw/cwlin/)<br>

&nbsp;&nbsp;&nbsp; <img src="fig/whu.png" width="110px"> &nbsp;&nbsp;<img src="fig/hit.png" width="150px"> &nbsp;&nbsp;<img src="fig/dmu.jpg" width="130px"> &nbsp;&nbsp;<img src="fig/nthu.png" width="150px">

### Abstract
>Recent progress in remote sensing image (RSI) super-resolution (SR) has exhibited remarkable performance using deep neural networks, e.g., Convolutional Neural Networks and Transformers. However, existing SR methods often suffer
from either a limited receptive field or quadratic computational overhead, resulting in sub-optimal global representation and unacceptable computational costs in large-scale RSI. To alleviate these issues, we develop the first attempt
to integrate the Vision State Space Model (Mamba) for RSI-SR, which specializes in processing large-scale RSI by capturing long-range dependency with linear complexity. To achieve better SR reconstruction, building upon Mamba, we devise a Frequency-assisted Mamba framework, dubbed FMSR, to explore the spatial and frequent correlations. In particular, our FMSR features a multi-level fusion architecture equipped with the Frequency Selection Module (FSM), Vision State Space Module (VSSM), and Hybrid Gate Module (HGM) to grasp their merits for effective spatial-frequency fusion. Recognizing that global and local dependencies are complementary and both beneficial for SR, we further recalibrate these multi-level features for accurate feature fusion via learnable scaling adaptors. Extensive experiments on AID, DOTA, and DIOR benchmarks demonstrate that our FMSR outperforms state-of-the-art Transformer-based methods HAT-L in terms of PSNR by 0.11 dB on average, while consuming only 28.05% and 19.08% of its memory consumption and complexity, respectively.
>

### 🌱 Overall
<img src="fig/network.png" width="500px">
