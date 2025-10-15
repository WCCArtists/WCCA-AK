# WCCA-AK: A Multimodal Dataset of André Kim's Fashion Legacy

Official repository for the WCCA-AK dataset, a comprehensive multimodal collection documenting the fashion legacy of André Kim for AI-driven cultural heritage research.

## Overview

WCCA-AK provides researchers with unprecedented access to André Kim's fashion legacy through high-quality multimodal data spanning five decades (1962-2010). Each garment in the dataset includes:

- High-resolution 3D models (OBJ/FBX formats)
- 88 synchronized multi-view images 
- Original design sketches and pattern drawings
- Fashion show footage
- Comprehensive metadata and annotations

## Dataset Access

The dataset is available for academic research purposes. Please visit our project page for download instructions and access requirements:

**[Dataset Download Portal](https://huggingface.co/datasets/SY95/WCCA-AK-images)**

### Requirements
- Registration required for dataset access
- Academic or research affiliation
- Acceptance of CC BY 4.0 license terms

## Dataset Statistics

| Metric | Value |
|--------|-------|
| Total garments | 100 (initial release) |
| Time span | 1962-2010 |
| Total 3D vertices | 125M |
| Total images | 8,800 |
| Total video hours | 24 |
| Design sketches | 312 |
| Storage size | 450 GB (uncompressed) |

## Dataset Structure

```
WCCA-AK/
├── WCCA-AK-001/
│   ├── 3d_models/
│   │   ├── mesh.obj
│   │   ├── mesh.fbx
│   │   └── textures/
│   ├── images/
│   │   ├── multiview/  # 88 synchronized views
│   │   └── details/    # Close-up captures
│   ├── sketches/
│   │   └── original_designs.jpg
│   ├── videos/
│   │   └── fashion_show.mp4
│   └── metadata.json
└── ...
```

## Applications

The dataset supports various research applications including:

- 3D reconstruction from sketches
- Style evolution analysis across decades
- Multimodal fashion generation
- Material and technique recognition
- Cross-cultural style transfer
- Virtual fashion show reconstruction

## Citation

If you use WCCA-AK in your research, please cite our paper:

```bibtex
@inproceedings{oh2025wcca,
  title={WCCA-AK: A Multimodal Dataset of André Kim's Fashion Legacy for AI-Driven Cultural Heritage Research},
  author={Oh, SeongYeon and Lee, Soyoung and Jeong, Hyeon Seong and Jo, Sangwoo and Kim, JinYoung and Choi, Yeonseo and Yoo, YoungJoon and Kim, Taehoon},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision Workshops},
  year={2025}
}
```

## License

The WCCA-AK dataset is released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

Users must:
- Give appropriate credit to the dataset creators and the André Kim Design Atelier
- Provide a link to the license
- Indicate if changes were made

## Acknowledgments

This dataset was created through collaboration between:
- Sogang University
- Chung-Ang University  
- André Kim Design Atelier

We thank the André Kim Design Atelier for providing access to the archive and their invaluable guidance throughout this project. Special thanks to Tridot and Korea Creative Content Agency (KOCCA) for their essential support with 3D scanning facilities.

## Contact

For questions about the dataset, please contact:
- Taehoon Kim (taehoonkim@sogang.ac.kr)
- YoungJoon Yoo (yjyoo3312@cau.ac.kr)

## Future Updates

We plan to expand the dataset to include:
- Additional 900 garments (total 1,000)
- Enhanced material property annotations
- Physics simulation parameters
- Interactive visualization tools

Stay updated by watching this repository.
