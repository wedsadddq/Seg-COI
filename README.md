<div align="center">

# Breaking the Boundaries of OVS: A Training-Free Semantic Query Framework for Segmenting Anything with Hypernym

</div>
## 📄 Overview

<div align="center">
   <img src="images/da(1).pdf" alt="Seg-COI Framework" width="80%"/>
</div>

> *We reinterpret Open-Vocabulary Segmentation (OVS) from the perspective of semantic query segmentation, extending traditional segmentation methods to a more flexible and general paradigm that explicitly focuses on categories of interest. To this end, we propose SegCoI, a novel query-guided and training-free segmentation framework designed to reuse the intrinsic capabilities of pre-trained models for segmenting arbitrary categories of interest beyond the open vocabulary. More specifically, we devise a Hierarchical Global-Local Query (HGQ) mechanism, which leverages the superclasses of query categories to alleviate semantic entanglement among similar categories and enhance the training-free operability of pre-trained models. Furthermore, we introduce Dominant Category Mask Refinement (DCMR) to refine segmentation boundaries through persistent labeling based on the most dominant category within each mask. Additionally, we design a lightweight yet efficient context-aware visual attention computation optimization strategy that directly adjusts the last-layer visual attention of CLIP. This strategy significantly strengthens the perception of local visual regions while avoiding model fine-tuning. Extensive experiments demonstrate that SegCoI achieves 1.5× performance improvement over existing methods on target categories in interactive visual query segmentation, establishing a new state-of-the-art benchmark.*
