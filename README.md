# Anatomical Idiosyncrasies

Every brain is quite anatomically unique, even at the MR imaging resolution. We use quite a few linear and non-linear transformations to combat this when we want to get in a common template. This is very much a work in progress, it's a collection of **common** anatomical idiosyncrasies that can put a spanner in our imaging processing tools.

## Incomplete Hippocampal Inversion
Fairly prevalent in around ~30% of subjects. [(Cury et al., 2015)](https://www.frontiersin.org/articles/10.3389/fnana.2015.00160/full). It is known under other names, such as hippocampal malrotation. Seems to be the easiest to spot in a coronal view [Bernasconi et al., 2005](https://academic.oup.com/brain/article/128/10/2442/274677).

| Diagram | MR |
| --- | --- |
| ![](https://www.frontiersin.org/files/Articles/162834/fnana-09-00160-HTML/image_m/fnana-09-00160-g001.jpg) | ![](https://prod-images.static.radiopaedia.org/images/22985204/9d05935af54dc549d54dd97850eb45_big_gallery.jpeg) |

## Paracingulate Sulcus
Another quite prevalent one in 30-60% of subjects. Can quite easily mess up freesurfers atlas parcellation [Enigma QC](https://drive.google.com/file/d/0Bw8Acd03pdRSU1pNR05kdEVWeXM/view). 

![](https://media.nature.com/lw926/nature-assets/srep/2017/170214/srep42033/images/srep42033-f1.jpg)
