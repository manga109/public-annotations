# Public-annotations
We provide various annotations of Manga109 dataset.
- [Comic Onomatopoeia (COO)](#comic-onomatopoeia-coo)
- [Manga109Dialog](#Manga109dialog)
- [MangaUB Benchmark Annotations](#mangaub-benchmark-annotations)



## Comic Onomatopoeia (COO)

[Comic Onomatopoeia (COO)](https://github.com/manga109/public-annotations/tree/main/COO-Comic-Onomatopoeia), Related project: https://github.com/ku21fan/COO-Comic-Onomatopoeia

### Annotation type list
Example of a xml file is shown below.
  ```xml 
  <?xml version='1.0' encoding='utf-8'?>
  <book title="ARMS">
    <pages>
      <page height="1170" index="0" width="1654" />
      <page height="1170" index="1" width="1654" />
      <page height="1170" index="2" width="1654">
        <onomatopoeia id="10000000" x0="596" y0="313" x1="658" y1="321" x2="660" y2="328" x3="595" y3="326">ズー・・・・ン</onomatopoeia>
        <onomatopoeia id="10000001" x0="417" y0="345" x1="506" y1="353" x2="506" y2="362" x3="410" y3="361">ゴオォ~・・・・ン</onomatopoeia>
        <onomatopoeia id="10000002" x0="438" y0="318" x1="526" y1="332" x2="522" y2="339" x3="437" y3="335">ドド~・~・・ン</onomatopoeia>
      </page>
      <page height="1170" index="3" width="1654">
        <onomatopoeia id="10000003" x0="686" y0="343" x1="763" y1="323" x2="769" y2="409" x3="678" y3="438">ダッ</onomatopoeia>
        <onomatopoeia id="10000004" x0="11" y0="924" x1="188" y1="845" x2="282" y2="1041" x3="238" y3="1146" x4="143" y4="1032" x5="32" y5="990">ザッ</onomatopoeia>
        <onomatopoeia id="10000005" x0="1204" y0="120" x1="1263" y1="120" x2="1317" y2="120" x3="1325" y3="127" x4="1312" y4="137" x5="1250" y5="138" x6="1212" y6="140" x7="1202" y7="141">ドオオォ~・・・・・ン</onomatopoeia>
        <onomatopoeia id="10000006" x0="1396" y0="389" x1="1452" y1="391" x2="1425" y2="437" x3="1370" y3="494" x4="1343" y4="475" x5="1384" y5="415">ザザッ</onomatopoeia>
        <onomatopoeia id="10000007" x0="1297" y0="224" x1="1314" y1="218" x2="1320" y2="225" x3="1339" y3="220" x4="1360" y4="220" x5="1366" y5="227" x6="1388" y6="224" x7="1383" y7="232" x8="1350" y8="238" x9="1341" y9="240" x10="1330" y10="242" x11="1317" y11="240" x12="1309" y12="241" x13="1296" y13="239">ズズズ~・ー・</onomatopoeia>
        <onomatopoeia id="10000008" x0="1071" y0="958" x1="1126" y1="950" x2="1127" y2="980" x3="1078" y3="990">スッ</onomatopoeia>
        <onomatopoeia id="10000009" x0="887" y0="985" x1="987" y1="985" x2="985" y2="1096" x3="876" y3="1097">ダッ</onomatopoeia>
        <onomatopoeia id="1000000a" x0="1185" y0="149" x1="1210" y1="144" x2="1211" y2="152" x3="1258" y3="152" x4="1273" y4="158" x5="1262" y5="170" x6="1205" y6="171" x7="1181" y7="167">ゴォ~・・・ン</onomatopoeia>
        <onomatopoeia id="1000000b" x0="627" y0="302" x1="639" y1="293" x2="664" y2="293" x3="681" y3="306" x4="670" y4="323" x5="677" y5="345" x6="666" y6="357" x7="679" y7="384" x8="659" y8="404" x9="649" y9="395" x10="643" y10="386" x11="629" y11="372" x12="611" y12="354">キャーッ</onomatopoeia>
        <onomatopoeia id="1000000c" x0="1426" y0="710" x1="1469" y1="695" x2="1460" y2="768" x3="1426" y3="776">ザッ</onomatopoeia>
      </page>
      ...
      ...                
      ...
    </pages>
  </book>
  ```

### Citation
When using annotations of comic onomatopoeia dataset (COO), please cite our paper.
```
@inproceedings{baek2022COO,
  title={COO: Comic Onomatopoeia Dataset for Recognizing Arbitrary or Truncated Texts},
  author={Baek, Jeonghun and Matsui, Yusuke and Aizawa, Kiyoharu},
  booktitle={Proceedings of the European Conference on Computer Vision (ECCV)},
  year={2022}
}
```


### License
The annotations of comic onomatopoeia dataset (COO) belong to [Aizawa Yamakata Matsui Lab](http://www.hal.t.u-tokyo.ac.jp/lab/en/index_1.xhtml) and are licensed under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See the [LICENCE_COO](./LICENSE_COO).


## Manga109Dialog
[Manga109Dialog](https://github.com/manga109/public-annotations/tree/main/Manga109Dialog), Related project: https://github.com/liyingxuan1012/Manga109Dialog

### Annotation type list
Example of a xml file is shown below.
  ```xml 
  <?xml version="1.0" ?>
  <book title="ARMS">
    <pages>
      <page index="0" width="1654" height="1170"/>
      <page index="1" width="1654" height="1170"/>
      <page index="2" width="1654" height="1170">
        <speaker_to_text id="20000001" text_id="00000001" speaker_id="00000002"/>
      </page>
      <page index="3" width="1654" height="1170">
        <speaker_to_text id="20000002" text_id="00000018" speaker_id="00000012"/>
        <speaker_to_text id="20000003" text_id="00000016" speaker_id="00000019"/>
        <speaker_to_text id="20000004" text_id="00000007" speaker_id="00000006"/>
        <speaker_to_text id="20000005" text_id="0000001e" speaker_id="00000011"/>
        <speaker_to_text id="20000006" text_id="0000000b" speaker_id="00000008"/>
        <speaker_to_text id="20000007" text_id="0000001b" speaker_id="00000019"/>
        <speaker_to_text id="20000008" text_id="00000013" speaker_id="00000019"/>
        <speaker_to_text id="20000009" text_id="00000017" speaker_id="00000019"/>
        <speaker_to_text id="2000000a" text_id="0000001a" speaker_id="00000012"/>
      </page>
      ...
      ...                
      ...
    </pages>
  </book>
  ```

### Citation
When using annotations of Manga109Dialog, please cite our paper.
```
@inproceedings{li2024manga109dialog,
  title={Manga109Dialog: A Large-scale Dialogue Dataset for Comics Speaker Detection},
  author={Li, Yingxuan and Aizawa, Kiyoharu and Matsui, Yusuke},
  booktitle={2024 IEEE International Conference on Multimedia and Expo (ICME)},
  year={2024},
  organization={IEEE}
}
```

### License
The annotations of Manga109Dialog belong to [Aizawa Yamakata Matsui Lab](http://www.hal.t.u-tokyo.ac.jp/lab/en/index_1.xhtml) and are licensed under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See the [LICENCE_Manga109Dialog](./LICENSE_Manga109Dialog).



## MangaUB Benchmark Annotations

Contains the base data used to create the prompts for the [MangaUB benchmark](https://github.com/woodrush/manga-ub) ([paper](https://doi.org/10.1109/MMUL.2025.3550451)), a benchmark designed to evaluate multimodal large language models on manga understanding tasks.
The benchmark code is available at: https://github.com/woodrush/manga-ub

> ⚠️ Note: The primary purpose of this dataset is to create the prompts used for the MangaUB benchmark.
> Some of the annotations depend on external datasets and are not directly usable without them.

The following files pertain to the Single-Panel Tasks of MangaUB and can be used independently:

- `character_count.csv`: Annotates the number of characters (human or non-human) appearing in each panel.
  - `panel_id`: UUID of the `frame` element in the Manga109 dataset.
  - `n_characters`: Number of characters in the given panel.
- `recognition_background.csv`: Provides scene-level labels for the Location, Time of Day, and Weather tasks.
  - `panel_id`: UUID of the `frame` element in the Manga109 dataset.
  - `category`: Task type - `Location` / `Time_of_Day` / `Weather`.
  - `label`: Corresponding label (e.g., Indoors/Outdoors, Day/Night, Sunny/Rainy/Snowy).

For further details of the data, please see [./MangaUB-Annotations/README.md](./MangaUB-Annotations/README.md).
For details on the benchmark tasks and usage, please visit the main repository: https://github.com/woodrush/manga-ub .

### Citation
When using the MangaUB annotations, please cite our paper:
```
@article{mangaub2025,
  author={Ikuta, Hikaru and Wohler, Leslie and Aizawa, Kiyoharu},
  journal={IEEE MultiMedia},
  title={MangaUB: A Manga Understanding Benchmark for Large Multimodal Models},
  year={2025},
  pages={1-10},
  doi={10.1109/MMUL.2025.3550451}
}
```


### License
The annotations of the MangaUB dataset belong to [Aizawa Yamakata Matsui Lab](http://www.hal.t.u-tokyo.ac.jp/lab/en/index_1.xhtml) and are licensed under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See the [LICENCE_MANGAUB](./LICENSE_MANGAUB).
