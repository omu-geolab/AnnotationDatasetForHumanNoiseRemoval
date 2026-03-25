Annotation Dataset For Human Noise Removal
--
### 概要 / Overview
異なる2つの現場で3次元計測した点群データに人間点群のみをアノテーションしたデータです。  
This is 3D measurement point cloud data from two different sites, annotated only with human point clouds.
<br>  
<img width="30%" height="30%" alt="Fig7R" src="https://github.com/user-attachments/assets/acad630f-41dd-4c61-92e2-efca132d5955" /> <img width="41%" height="41%" alt="スクリーンショット 2025-11-23 11 46 42" src="https://github.com/user-attachments/assets/649accc9-49a6-40b5-9a13-3874484beb46" />
<br> 

本データセットは、取得したカメラ画像に映る人物を対象としていますが、アノテーションの付与には以下の基準を設けております。  
While this dataset targets individuals appearing in the captured camera images, the following criteria have been established for applying annotations:  
- アノテーション対象： 視野角内で静止している人物 Annotation Target: Individuals who are stationary within the field of view.  
- アノテーション対象外： 視野角内で移動している人物（移動体）Annotation Exclusion: Individuals who are moving within the field of view (treated as moving objects).  

### ライセンス / License
CC BY-SA 4.0

### チーム / Team
大阪公立大学大学院 情報学研究科 学際情報学専攻 [吉田大介研究室](https://www.omu.ac.jp/i/geo/)（小村風我）  
Daisuke Yoshida Laboratory, Department of Interdisciplinary Informatics, Graduate School of Informatics, Osaka Metropolitan University

### 📝 Citation / 引用
If you find this code or dataset useful for your research, please cite our paper:

> Komura, F.; Yoshida, D.; Ueda, R. Geometry-Aware Human Noise Removal from TLS Point Clouds via 2D Segmentation Projection. *Sensors* **2026**, *26*, 1237. https://doi.org/10.3390/s26041237

```bibtex
@article{komura2026geometry,
  title={Geometry-Aware Human Noise Removal from TLS Point Clouds via 2D Segmentation Projection},
  author={Komura, Fuga and Yoshida, Daisuke and Ueda, Ryosei},
  journal={Sensors},
  volume={26},
  number={4},
  pages={1237},
  year={2026},
  publisher={MDPI},
  doi={10.3390/s26041237},
  url={[https://www.mdpi.com/1424-8220/26/4/1237](https://www.mdpi.com/1424-8220/26/4/1237)}
}
