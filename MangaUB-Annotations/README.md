# Annotations for MangaUB: A Manga Understanding Benchmark for Large Multimodal Models
This is the official repository for the annotations used in MangaUB. The paper is available here: [https://doi.org/10.1109/MMUL.2025.3550451](https://doi.org/10.1109/MMUL.2025.3550451)


## Contents
The annotations are contained under `./annotations/`. Here are the contents of the directory:

| Filename                         | Source                 | Content                                                        |
|----------------------------------|------------------------|----------------------------------------------------------------|
| character_count.csv              | New                    | Annotations for the Character Count task                       |
| onomatopoeia_descriptions.json   | New                    | Descriptions used for the Onomatopoeia Scene task              |
| recognition_background.csv       | New                    | Annotations for the Single-Panel Recognition tasks             |
| kangaiset_subset_keys.csv        | Selected from [4]      | Selected subset from the KangaiSet dataset [4]                 |
| onomatopoeia_COO_ids.csv         | Selected from [3]      | Selected subset from the COO dataset [3]                       |
| four_panel_comics.csv            | Selected from [1,2]    | Four-panel comics from the Manga109 dataset [1,2]              |
| genre.csv                        | Referenced from [1,2]  | List of genres for the works from the Manga109 dataset [1,2]   |

The `New` source indicates the annotations that were newly created for the MangaUB paper.


## Citation
This dataset is associated with the MangaUB benchmark.
When using MangaUB or if you find our work helpful, please cite our following [paper](https://doi.org/10.1109/MMUL.2025.3550451):

```bibtex
@article{mangaub2025,
  author={Ikuta, Hikaru and Wohler, Leslie and Aizawa, Kiyoharu},
  journal={IEEE MultiMedia},
  title={MangaUB: A Manga Understanding Benchmark for Large Multimodal Models},
  year={2025},
  pages={1-10},
  doi={10.1109/MMUL.2025.3550451}
}
```


## References
- [1] Y. Matsui, K. Ito, Y. Aramaki, A. Fujimoto, T. Ogawa, T. Yamasaki, and K. Aizawa, “Sketch-based manga retrieval using Manga109 dataset,” <i>Multimedia Tools Appl.,</i> vol. 76, no. 20, pp. 21 811–21 838, 2017, doi: 10.1007/s11042-016-4020-z.
- [2] K. Aizawa, A. Fujimoto, A. Otsubo, T. Ogawa, Y. Matsui, K. Tsubota, and H. Ikuta, “Building a manga dataset “Manga109” with annotations for multimedia applications,” <i>IEEE MultiMedia,</i> vol. 27, no. 2, pp. 8–18, 2020, doi: 10.1109/mmul.2020.2987895.
- [3] J. Baek, Y. Matsui, and K. Aizawa, “COO: Comic onomatopoeia dataset for recognizing arbitrary or truncated texts,” in <i>Proc. European Conf. Comput. Vision,</i> 2022, p. 267–283, doi: 10.1007/978-3-031-19815-1 16.
- [4] R. Théodose and J.-C. Burie, “KangaiSet: A dataset for visual emotion recognition on manga,” in <i>Document Analysis and Recognition: Proc. ICDAR 2023 Workshops,</i> 2023, pp. 120–134, doi: 10.1007/978-3-031-41498-5 9.
