# MoGUI😈 and MoCon🛡️

<div align="center">

📃 [Paper](./MoGUI_Paper_v0.1.pdf) | 😈 [MoGUI Data](https://huggingface.co/datasets/OpenDFM/MoGUI) | 🛡️ [MoCon Data](https://huggingface.co/datasets/OpenDFM/MoCon) 

[简体中文](./README_zh.md) | English

</div>

## 🔥 News

- **[Cooming Soon]** We will release the complete technical report soon.
- **[2024.3.1]** We have released [MoCon🛡️ data](https://huggingface.co/datasets/OpenDFM/MoCon).
- **[2024.2.29]** We have released [MoGUI😈 data](https://huggingface.co/datasets/OpenDFM/MoGUI) and [pre-release paper](./MoGUI_Paper_v0.1.pdf).

## What is MoGUI😈?

MoGUI😈, pronounced as "Monster" in mandarin, is a Mobile GUI dataset. It contains over 2.6 million GUI data from over 250,000 applications, each GUI data includes a screenshot and `.xml` metadata, and each application also includes a navigation graph, aiming to explicitly crawl the jump relationship between different GUIs during the crawling process. We also provide metadata of these applications in the Google Play.

## What is MoCon🛡️?

MoCon🛡️, pronounced as "Magic Resistance" in mandarin, is a dataset for annotating Mobile GUI Contents. We extracted over 10,000 mobile GUIs from the Rico dataset and annotated all elements in the GUI, dividing text into 7 categories according to font and icons into 154 categories according to shape and intent.

## 📑 Citation

If you find our work useful, please cite us!

```
@misc{zhu2024mogui,
  title={Technical Report of MoGUI and MoCon}, 
  author={Zichen Zhu and Liangtai Sun and Danyang Zhang and Ziyuan Li and Guangpeng Li and Lu Chen and Kai Yu},
  year={2024},
  howpublished={\url{https://huggingface.co/datasets/OpenDFM/MoGUI}}
}

@inproceedings{sun2022meta,
  title={META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI},
  author={Sun, Liangtai and Chen, Xingyu and Chen, Lu and Dai, Tianle and Zhu, Zichen and Yu, Kai},
  booktitle={Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing},
  pages={6699--6712},
  year={2022}
}

@inproceedings{zhu2023cam,
  title={CAM-GUI: A Conversational Assistant on Mobile GUI},
  author={Zhu, Zichen and Sun, Liangtai and Yang, Jingkai and Peng, Yifan and Zou, Weilin and Li, Ziyuan and Li, Wutao and Chen, Lu and Ma, Yingzi and Zhang, Danyang and others},
  booktitle={National Conference on Man-Machine Speech Communication},
  pages={302--315},
  year={2023},
  organization={Springer}
}
```

## 📧 Contact Us

If you have any questions, please feel free to contact us via email `JamesZhutheThird@sjtu.edu.cn` and `slt19990817@sjtu.edu.cn`