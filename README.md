# P-Maize: A golden standard of single-cell analysis with Maize
- **Brief:** The Projection of Maize: Building a powerful analysis pipeline and Getting some significant results of maize research
- **Contributors:** chenkun1@genomics.cn; zhangzijian@genomics.cn; huangpeilin@genomics.cn; weichunxu@genomics.cn; yinzhanhao@genomics.cn; yangdong@genomics.cn
- **Log**
  - 250904 初步确定项目方案

---
# Background
- **Species**

Maize [wiki](https://en.wikipedia.org/wiki/Maize)
<img src="PNG/Maize_plant_diagram.png" alt="Maize_plant_diagram" style="height: 500px; width: auto;">

- **Scientific problem**
玉米苞片的发育和玉米叶的发育？


- **Reference & Citation**
  - 玉米苞叶: 2021_agriculture_Tensile Properties and Fracture Mechanisms of Corn Bract for Corn Peeling Device Design [agriculture](https://www.mdpi.com/2077-0472/11/8/796)
  - [玉米物种Wiki百科](https://en.wikipedia.org/wiki/Maize)

---
# Input
- **User:** chenkun1@genomics.cn

参考基因组数据：/Files/Chenkun/Maize_husk/reference/hzau/Zm-B73-REFERENCE-NAM-5.0.fa
基因组注释：/Files/Chenkun/Maize_husk/reference/hzau/Zm-B73-REFERENCE-NAM-5.0_Zm00001eb.1.gtf
叶片每段的下机矩阵数据（里面也有soupx矩阵）：	
/Files/Chenkun/B73_leaf/B73_L/B73_L1	
/Files/Chenkun/B73_leaf/B73_L/B73_L2	
/Files/Chenkun/B73_leaf/B73_L/B73_L3	
/Files/Chenkun/B73_leaf/B73_L/B73_L4
苞叶下机矩阵：
/Files/Chenkun/Maize_husk/maize-husk-1/
/Files/Chenkun/Maize_husk/maize-husk-2/
苞叶dataget结果：
/Files/Chenkun/Maize_husk/maize_husk_dataget/

目前项目的问题：对苞叶进行初步注释，查看光合基因在叶肉细胞和维管束鞘细胞的表达情况是否符合C3叶片
- **P-Maize**
  - Ref
    - Genome(.fa): /Files/Chenkun/Maize_husk/reference/hzau/Zm-B73-REFERENCE-NAM-5.0.fa
    - Annotation(.gtf): /Files/Chenkun/Maize_husk/reference/hzau/Zm-B73-REFERENCE-NAM-5.0_Zm00001eb.1.gtf
    - Protein(.fa): NA
  - Matrix
    - leaf
    - bract
  - Pipeline1-single (huangpeilin@genomics.cn; yangdong@genomics.cn)
  - Pipeline2-pair (yinzhanhao@genomics.cn; weichunxu@genomics.cn; zhangzijian@genomics.cn)

- **Reference & Citation**
  - [Zm-B73-REFERENCE-NAM-5.0 - Genome - Assembly](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_902167145.1/)

---
# Pipeline

## Pipeline1-single
### 1.Dataget



## Pipeline2-pair





---
# Reference & Citation