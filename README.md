# (Refactor In Progress) Forecasting from LiDAR via Future Object Detection [[PDF](https://arxiv.org/pdf/2203.16297.pdf)]

Neehar Peri, Jonathon Luiten, Mengtian Li, Aljosa Osep, Laura Leal-Taixe, Deva Ramanan

<p align="center"> <img src='docs/pipeline.png' align="center" height="230px"> </p>

## Abstract 
Object detection and forecasting are fundamental components of embodied perception. These two problems, however, are largely studied in isolation by the community. In this paper, we propose an end-to-end approach for detection and motion forecasting based on raw sensor measurement as opposed to ground truth tracks. Instead of predicting the current frame locations and forecasting forward in time, we directly predict future object locations and backcast to determine where each trajectory began. Our approach not only improves overall accuracy compared to other modular or end-to-end baselines, it also prompts us to rethink the role of explicit tracking for embodied perception. Additionally, by linking future and current locations in a many-toone manner, our approach is able to reason about multiple futures, a capability that was previously considered difficult for end-to-end approaches. We conduct extensive experiments on the popular nuScenes dataset and demonstrate the empirical effectiveness of our approach. In addition, we investigate the appropriateness of reusing standard forecasting metrics for an end-to-end setup, and find a number of limitations which allow us to build simple baselines to game these metrics. We address this issue with a novel set of joint forecasting and detection metrics that extend the commonly used AP metrics from the detection community to measuring forecasting accuracy.

If you find this codebase helpful, please consider citing:

    @article{peri2022futuredet,
      title={Forecasting from LiDAR via Future Object Detection},
      author={Peri, Neehar and Luiten, Jonathon and Li, Mengtian and Osep, Aljosa and Leal-Taixe, Laura and Ramanan, Deva},
      journal={arXiv:2203.16297},
      year={2022},
    }

<p align="center"> <img src='docs/demo.gif' align="center" height="530px"> </p>

## Contact
Any questions or discussion are welcome! Please raise an issue, or send me an email.

Neehar Peri [[nperi@cs.cmu.edu](mailto:nperi@cs.cmu.edu)]

## Installation 

[Forecasting Evaluation Toolkit](https://github.com/neeharperi/nuScenes-Forecast)

[Sparse Convolutions (spconv)](https://github.com/neeharperi/spconv)

[Apex](https://github.com/neeharperi/apex)

## Usage

## Pre-trained Models
[Model Zoo](https://github.com/neeharperi/FutureDet/MODELZOO.md)