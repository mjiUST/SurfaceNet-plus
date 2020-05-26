# SurfaceNet+
- An End-to-end 3D Neural Network for Very Sparse MVS
- **Key contributions**
    1. Proposed a Sparse-MVS benchmark 
        * (under construction)
        * Comprehensive evaluation of the 
        * Based on the datasets: DTU and T&T 
    2. Proposed a **trainable occlusion-aware** view selection scheme for the volumetric MVS method, e.g., [SurfaceNet](https://github.com/mjiUST/SurfaceNet)[5]. 
    3. Analysed the advantages of the volumetric method, e.g., [SurfaceNet](https://github.com/mjiUST/SurfaceNet)[5], on the **Sparse-MVS problem** over the depth-fusion methods, e.g., [Gipuma](https://github.com/kysucix/gipuma) [6], [R-MVSNet](https://github.com/YoYo000/MVSNet)[7], [Point-MVSNet](https://github.com/callmeray/PointMVSNet)[8], and [COLMAP](https://github.com/colmap/colmap)[9].

# Sparse-MVS Benchmark 

## Sparse-MVS of DTU dataset

<p align="center">
  <img width="460" src="figures/teaser.jpg">
  
  Fig.1: Illustration of a very sparse MVS setting using only $1/7$ of the camera views, i.e., $\{v_i\}_{i=1,8,15,22,...}$, to recover the model 23 in the DTU dataset [10]. Compared with the state-of-the-art methods, the proposed SurfaceNet+ provides much complete reconstruction, especially around the boarder region captured by very sparse views.
</p>

<p align="center">
  <img width="460" src="figures/DTU.jpg">
  
  Fig.2: Illustration of a very sparse MVS setting using only $1/7$ of the camera views, i.e., $\{v_i\}_{i=1,8,15,22,...}$, to recover the model 23 in the DTU dataset [10]. Compared with the state-of-the-art methods, the proposed SurfaceNet+ provides much complete reconstruction, especially around the boarder region captured by very sparse views.
</p>

## Sparse-MVS of T&T dataset

<p align="center">
  <img width="460" src="figures/T&T.jpg">
  
  Fig.3: Illustration of a very sparse MVS setting using only $1/7$ of the camera views, i.e., $\{v_i\}_{i=1,8,15,22,...}$, to recover the model 23 in the DTU dataset [10]. Compared with the state-of-the-art methods, the proposed SurfaceNet+ provides much complete reconstruction, especially around the boarder region captured by very sparse views.
</p>


## Citing SurfaceNet+

If you find SurfaceNet+, the Sparse-MVS benchmark, or [SurfaceNet](https://github.com/mjiUST/SurfaceNet) useful in your research, please consider citing:

    @ARTICLE{ji2020surfacenet_plus,
        title={SurfaceNet+: An End-to-end 3D Neural Network for Very Sparse Multi-view Stereopsis}, 
        author={M. {Ji} and J. {Zhang} and Q. {Dai} and L. {Fang}},
        journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
        year={2020},
        volume={},
        number={},
        pages={1-1},
    }

    @inproceedings{ji2017surfacenet,
        title={SurfaceNet: An End-To-End 3D Neural Network for Multiview Stereopsis},
        author={Ji, Mengqi and Gall, Juergen and Zheng, Haitian and Liu, Yebin and Fang, Lu},
        booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
        pages={2307--2315},
        year={2017}
    }


