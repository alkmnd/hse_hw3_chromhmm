# hse_hw3_chromhmm
 [Ссылка на Colab](https://colab.research.google.com/drive/13ykNGSVjeX2dN_2xc_9P-kEOhM4_X_WT?usp=sharing)
 
Клеточная линия: HSMMtube

## Гистоновые метки

|Гистоновая метка|Имя файла|
|:--|--:|
|H2AFZ|H2AFZ.bam|
|H3K27ac|H3K27ac.bam|
|H3K27me3|H3K27me3.bam|
|H3K36me3|H3K36me3.bam|
|H3K4me1|H3K4me1.bam|
|H3K4me2|H3K4me2.bam|
|H3K4me3|H3K4me3.bam|
|H3K79me2|H3K79me2.bam|
|H3K9ac|H3K9ac.bam|
|H3K9me3|H3K9me3.bam|
|H4K20me1|H4K20me1.bam|

## файл cellmarkfiletable.txt
|Клеточная линия |	Гистоновая метка	| Файл с гистоновой меткой |	Файл с контролем |
|:--|--|--|--:|
|HSMMtube	|H2AFZ	|H2AFZ.bam|	Control.bam|
|HSMMtube |	H3K27ac	|	H3K27ac.bam |	Control.bam|
|HSMMtube |	H3K27me3 |	H3K27me3.bam |	Control.bam|
|HSMMtube |	H3K36me3	|	H3K36me3.bam |	Control.bam|
|HSMMtube |	H3K4me1 |	H3K4me1.bam |	Control.bam|
|HSMMtube |	H3K4me2	|	H3K4me2.bam |	Control.bam|
|HSMMtube |	H3K4me3 |	H3K4me3.bam |	Control.bam|
|HSMMtube	| H3K79me2 |	H3K79me2.bam |	Control.bam|
|HSMMtube |	H3K9ac |	H3K9ac.bam |	Control.bam|
|HSMMtube	| H3K9me3 |	H3K9me3.bam |	Control.bam|
|HSMMtube	| H4K20me1 |	H4K20me1.bam |	Control.bam|

## ChromHMM
| emission | transition | overlap |
|:--|--|--:|
|![](https://github.com/alkmnd/hse_hw3_chromhmm/blob/main/data/emissions_11.png)|![](https://github.com/alkmnd/hse_hw3_chromhmm/blob/main/data/transitions_11.png)|![](https://github.com/alkmnd/hse_hw3_chromhmm/blob/main/data/HSMMtube_11_overlap.png)|

|RefSeqTSS|RefSeqTES|
|:--|--:|
|![](https://github.com/alkmnd/hse_hw3_chromhmm/blob/main/data/HSMMtube_11_RefSeqTSS_neighborhood.png)|![](https://github.com/alkmnd/hse_hw3_chromhmm/blob/main/data/HSMMtube_11_RefSeqTES_neighborhood.png)|
