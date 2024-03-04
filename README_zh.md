# MoGUI😈 and MoCon🛡️

<div align="center">

📃 [论文](./MoGUI_Paper_v0.1.pdf) | 😈 [MoGUI数据](https://huggingface.co/datasets/OpenDFM/MoGUI) | 🛡️ [MoCon数据](https://huggingface.co/datasets/OpenDFM/MoCon) 

简体中文 | [English](./README.md) 

</div>

## 🔥 News

- **[即将上线]** 我们即将发布完整技术报告。
- **[2024.3.1]** 我们发布了[MoCon🛡️数据](https://huggingface.co/datasets/OpenDFM/MoCon)。
- **[2024.2.29]** 我们发布了[MoGUI😈数据](https://huggingface.co/datasets/OpenDFM/MoGUI)和[论文预告](./MoGUI_Paper_v0.1.pdf)。

## 什么是MoGUI😈？

MoGUI😈，中文读音为“魔鬼”，是一个手机界面（Mobile GUI）数据集。包含来自25万个应用程序的超过260万个界面数据，每个界面数据包含界面截图和`.xml`结构元数据，每个应用程序还包括一个导航图（navigation graph），旨在明确爬取过程中不同界面的跳转关系。我们还提供这些应用程序在Google Play商店的元数据。

## 什么是MoCon🛡️？

MoCon🛡️，中文读音为“魔抗”，是一个对手机界面元素（Mobile Contents）进行标注的数据集。我们从Rico数据集中抽取了超过1万个手机界面，并对界面中的所有元素进行标注，将文本按照字体分为7类，将图标按照形状和意图分为154类。

## 📑 引用

如果您觉得我们的工作有用，请引用我们！

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

## 📧 联系我们

如果你有任何问题，请随时通过电子邮件联系我们 `JamesZhutheThird@sjtu.edu.cn` 和 `slt19990817@sjtu.edu.cn`