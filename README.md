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

## Эпигенетические типы 
|#|Название|Описание |
|:--|--|--:|
|1|Weak enhancer|Выражен в H3K4me1, H2AFZ, H3K4me2, H3K27me3, H4K20me1. Относительно TES находится прмиерно на всем промежутке. Попадвет на конец транскрипции, гены и экзоны. |
|2|Enhancer|Выражен в H3K27ac, H3K4me1, H3K4me2, H2AFZ. Относительно TES находится прмиерно на всем промежутке. Попадает в основном на конец транскрипции|
|3|Promoter|Выражен в H2AFZ, H3K4me2, 3K4me3, H3K27ac. отностельно TES находится до. Попадает на CpG островки, экзоны, старт транскрипции. |
|4|Transcribed region|Выражен в H3K79me2, H3K9ac, H3K4me2, H3K4me3, H3K27ac. относительно TSS находится после, относительно TES максимум находиься до. В основном попадает на гены, старт транкрипции|
|5|Transcribed region|Выражен в H3K79me2, H3K9ac, H4K20me1. Попадает на ген.|
|6|Transcribed region|Выражен в H3K79me2 и H3K9ac. Находится на всем промежутке относительно TES. Попадает на ген, экзоны, конец транскрипции.|
|7|Weak transcribed|Выражен в H4K20me1 и H3K36me3. Находится на всем промежутке относительно TES. Попадает на конец транксрипции, гены, иногда экзоны и ядерную ламину|
|8|Weak promoter|Выражен в H4K20me1. Находится на всем промежутке относительно TES. Попадает на гены. |
|9|Weak promoter|Выражен в H4K20me1. Попадает на ядерную ламину. |
|10|Heterochromatin|Выражен в H3K27me3. Находится на всем промежутке относительно TES. Попадает на ядерную ламину и конец транскрипции. |
|11|Heterochromatin|Выражен в H3K9me3.  Находится на всем промежутке относительно TES. Попадает на ядерную дамну и конец транскрипции.|

