# Awesome-Region-Encoders

This repository provides the latest and most comprehensive information on **Region Encoders**.

Region encoders are machine learning frameworks designed to represent geographic regions by integrating multimodal data, such as satellite imagery, demographic statistics, and environmental factors. This representation is crucial for addressing challenges like sparse and unevenly distributed data, which often limit the effectiveness of traditional models. By creating unified regional representations, region encoders enable advanced spatial analysis and support downstream tasks such as spatiotemporal prediction, forecasting, and decision-making in domains like urban planning, climate science, and public health.

**This project is curated and maintained by [JangHyeon Lee](https://janghyeon-lee.github.io/) and [Min Namgung](https://minnamgung.github.io/), members of the [Knowledge Computing Lab](https://knowledge-computing.github.io/).**

## Geo-Foundation Models
- (*KDD 24*) Urban Foundation Models: A Survey ([paper](https://dl.acm.org/doi/pdf/10.1145/3637528.3671453), [code](https://github.com/usail-hkust/Awesome-Urban-Foundation-Models))
- (*KDD 24*) ReFound: Crafting a Foundation Model for Urban Region Understanding upon Language and Visual Foundations ([paper](https://dl.acm.org/doi/10.1145/3637528.3671992))
- (*arXiv 25*) General Geospatial Inference with a Population Dynamics Foundation Model ([paper](https://arxiv.org/pdf/2411.07207), [code](https://github.com/google-research/population-dynamics))
  
## Graph-based
- (*CIKM 19*) Unsupervised Representation Learning of Spatial Data via Multimodal Embedding ([paper](https://dl.acm.org/doi/10.1145/3357384.3358001), [code](https://github.com/porterjenkins/region-encoder))
- (*IJCAI 21*) Multi-view joint graph representation learning for urban region embedding ([paper](https://www.ijcai.org/proceedings/2020/0611.pdf), [code](https://github.com/mingyangzhang/mv-region-embedding/tree/master))
- (*KDD 23*) Spatial Heterophily Aware Graph Neural Networks ([paper](https://dl.acm.org/doi/abs/10.1145/3580305.3599510), [code](https://github.com/PaddlePaddle/PaddleSpatial/tree/main/research/SHGNN))
- (*ICDE 24*) HAFusion: Urban Region Representation Learning with Attentive Fusion ([paper](https://arxiv.org/abs/2312.04606), [code](https://github.com/MiRuacle24/HAFusion))

## Contrastive Learning-based
- (*TKDE 22*) Region Embedding With Intra and Inter-View Contrastive Learning ([paper](https://arxiv.org/pdf/2211.08975), [code](https://github.com/Liang-NTU/ReMVC))
- (*WWW 22*) Beyond the First Law of Geography: Learning Representations of Satellite Imagery by Leveraging Point-of-Interests ([paper](https://dl.acm.org/doi/10.1145/3485447.3512149), [code](https://github.com/axin1301/satellite-imagery-POI))
- (*WWW 23*) Knowledge-infused Contrastive Learning for Urban Imagery-based Socioeconomic Prediction ([paper](https://dl.acm.org/doi/10.1145/3543507.3583876), [code](https://github.com/tsinghua-fib-lab/UrbanKG-KnowCL))
- (*WWW 24 Oral*) UrbanCLIP: Learning Text-enhanced Urban Region Profiling with Contrastive Language-Image Pretraining from the Web ([paper](https://arxiv.org/pdf/2310.18340), [code](https://github.com/stupidbuluchacha/urbanclip), [review](https://openreview.net/forum?id=KCZU12jzfC&referrer=%5Bthe%20profile%20of%20Yuxuan%20Liang%5D(%2Fprofile%3Fid%3D~Yuxuan_Liang1)))
- (*AAAI 24*) Urban Region Embedding via Multi-View Contrastive Prediction ([paper](https://arxiv.org/pdf/2312.09681), [code](https://github.com/lizc-sdu/ReCP))

## Downstream Tasks
### Spatial Interpolation 
- (*Remote Sensing 20*) Random Forest Spatial Interpolation ([paper](https://www.mdpi.com/2072-4292/12/10/1687), [code](https://github.com/AleksandarSekulic/RFSI))
- (*IJGIS 20*) Geographically neural network weighted regression for the accurate estimation of spatial non-stationarity ([paper](https://www.tandfonline.com/doi/full/10.1080/13658816.2019.1707834), [code](https://github.com/zjuwss/gnnwr))
- (*AAAI 20*) Kriging Convolutional Networks ([paper](https://arxiv.org/pdf/2306.09463), [code](https://github.com/tufts-ml/kcn-torch))
- (*IJGIS 21*) Geographically and temporally neural network weighted regression for modeling spatiotemporal non-stationary relationships ([paper](https://www.tandfonline.com/doi/full/10.1080/13658816.2020.1775836), [code](https://github.com/zjuwss/gnnwr))
- (*NIPS 22*) Learning to Reconstruct Missing Data from Spatiotemporal Graphs with Sparse Observations ([paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/cf70320e93c08b39b1b29a348097a376-Paper-Conference.pdf), [code](https://github.com/Graph-Machine-Learning-Group/spin))
- (*SIGMOD 23*) SSIN: Self-Supervised Learning for Rainfall Spatial Interpolation ([paper](https://arxiv.org/abs/2311.15530), [code](https://github.com/jlidw/SSIN))
- (*Nature Communications 24*) Scalable spatiotemporal prediction with Bayesian neural fields ([paper](https://www.nature.com/articles/s41467-024-51477-5), [code](https://github.com/google/bayesnf))
- (*IJGIS 24*) DKNN: deep kriging neural network for interpretable geospatial interpolation ([paper](https://www.tandfonline.com/doi/full/10.1080/13658816.2024.2347316), [code](https://github.com/in1311/DKNN))
- (*SIGSPATIAL 24*) SAUC: Sparsity-Aware Uncertainty Calibration for Spatiotemporal Prediction with Graph Neural Networks ([paper](https://dl.acm.org/doi/10.1145/3678717.3691241), [code](https://github.com/AnonymousSAUC/SAUC))

## Datasets & Benchmarks
- OpenStreetMap ([link](https://www.openstreetmap.org/))
- NYC Open Data ([link](https://opendata.cityofnewyork.us/))
- USDA National Agriculture Imagery Program (NAIP) ([link](https://coast.noaa.gov/htdata/raster3/imagery/NY_NAIP_2015_8402/))
- Global Streetscapes ([link](https://huggingface.co/datasets/NUS-UAL/global-streetscapes))
- Treepedia ([link](https://senseable.mit.edu/treepedia))

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=janghyeon-lee/Awesome-Region-Encoders&type=Date)](https://star-history.com/#janghyeon-lee/Awesome-Region-Encoders&Date)
