# Dynamic Multimodal Inference [CMU Spring 2024 Course Project : 11-785 Introduction to Deep Learning]

## Overview

This repository contains code used for a group project, as part of coursework at Carnegie Mellon University. 
The project deals with dynamically selecting an inference path for multimodal inputs. The selected path can use any subset of the input's set of modalities, resulting in computational savings when performing inference across data instances.

Our work is derivative of techniques proposed in the paper [Dynamic Multimodal Fusion](https://arxiv.org/abs/2204.00102), whose source code can be found at [https://github.com/zihuixue/DynMM](https://github.com/zihuixue/DynMM)

We run ablations of our own to verify the papers results on the task of 23-multilabel genre classification on the MM-IMDB dataset, released in the paper [Gated Multimodal Units for Information Fusion](https://arxiv.org/abs/1702.01992). The dataset is downloadable at [https://archive.org/download/mmimdb/multimodal_imdb.hdf5](https://archive.org/download/mmimdb/multimodal_imdb.hdf5).

Our code is largely built on top of the [MultiBench](https://github.com/pliang279/MultiBench) repository (see [MultiBench: Multiscale Benchmarks for Multimodal Representation Learning](https://arxiv.org/abs/2107.07502)).

## Code structure

This repository consits of two git modules - [https://github.com/Rajeevveera24/DynMM/tree/main](https://github.com/Rajeevveera24/DynMM/tree/main) and [https://github.com/Rajeevveera24/MultiBench/tree/main](https://github.com/Rajeevveera24/MultiBench/tree/main), which are forks of the DynMM and MultiBench repositories respectively.

### Our code set up

Following the set up instructions in [https://github.com/Rajeevveera24/MultiBench/tree/main](https://github.com/Rajeevveera24/MultiBench/tree/main), we use code from  [https://github.com/Rajeevveera24/DynMM/tree/main](https://github.com/Rajeevveera24/DynMM/tree/main) in the  [https://github.com/Rajeevveera24/MultiBench/tree/main](https://github.com/Rajeevveera24/MultiBench/tree/main) repository. As per the instructions, we perform the same set up steps (Steps arecopied from the original repo)



1. Download MM-IMDB and CMU-MOSEI data from [MultiBench](https://github.com/pliang279/MultiBench)
2. Clone the Multibench repository.
3. Copy folders from `DynMM/ModalityDynMM` to `MultiBench`
4. We run the scripts mentioned in [https://github.com/Rajeevveera24/DynMM/tree/main?tab=readme-ov-file#overview](https://github.com/Rajeevveera24/DynMM/tree/main?tab=readme-ov-file#overview) to verify the paper's results.
5. The extensions, modifications and ablations we experimented with can be found in the latest commits of [https://github.com/Rajeevveera24/MultiBench/commits/main/](https://github.com/Rajeevveera24/MultiBench/commits/main/)

### If you wish to run our code, here is how you can set it up
1. 
