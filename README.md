# UFPR-VeSV-Dataset

The UFPR Vehicle Surveillance (UFPR-VeSV) dataset provides a challenging benchmark to advance Fine-Grained Vehicle Classification (FGVC) and integrate it with Automatic License Plate Recognition (ALPR). The dataset's construction and initial results from experiments using deep learning models are detailed in our paper *Toward Unified Fine-Grained Vehicle Classification and Automatic License Plate Recognition*. [[PDF]](https://arxiv.org/pdf/2604.05271).

## About

The UFPR-VeSV dataset consists of 24,945 images of 16,297 unique vehicles, sourced from the Military Police of Paraná (Brazil) surveillance system across highways, urban streets, and rural roads. The dataset reflects diverse real-world conditions, including frontal and rear views, partial occlusions, varying distances, and environmental factors such as weather and motion blur. Examples of vehicle images are shown in Fig. 1.

<figure>
    <figcaption>
        <b>Fig. 1.</b> Examples of images from the UFPR-VeSV dataset.
    </figcaption>
    <img src=./figs/vehicle-samples.png alt="vehicle samples from UFPR-VeSV dataset">
</figure>

The dataset provides rich annotations across 13 color classes, 26 makes, 136 models, and 14 vehicle types, alongside bounding box corner coordinates and characters for license plates. It features license plates spanning standard Brazilian and Mercosur layouts, captured under diverse angles, resolutions, and noise levels (see Fig. 2).

<figure>
    <figcaption>
        <b>Fig. 2.</b> Examples of license plate images from the UFPR-VeSV. The corresponding license plate characters are displayed bellow each image.
    </figcaption>
    <img src=./figs/lp-samples.png alt="License plate samples from UFPR-VeSv dataset">
</figure>

The dataset encompasses a broad temporal range and is categorized according to camera capture mode. Notably, nighttime images — captured predominantly in infrared — account for 21.5% of the data. The dataset also features diverse vehicle viewpoints. Based on license plate visibility, these perspectives are standardized into 13,842 rear-view and 11,103 frontal-view images.

Regarding privacy concerns, the license plates are associated with the vehicles only; no public information about vehicle drivers or owners is available. Faces that may appear were blurred to preserve identity. 

## How to obtain

Access to the dataset is provided upon request and requires the completion of a licensing agreement. The UFPR-VeSV dataset is intended solely for academic research and is freely available to researchers affiliated with educational or research institutes for **non-commercial purposes**.

To access the dataset, please review the  [**license agreement**](./pdfs/license-agreement.pdf), sign it, and return it to the first author at ([gelima@inf.ufpr.br](mailto:gelima@inf.ufpr.br)). Make sure to send your request from a valid university email account (e.g., .edu, .ac, or similar). You can expect to receive a download link within 1-5 business days.

Please note that failure to follow these instructions may result in no response.

## Citation

This paper is currently in press. The BibTeX citation below is temporary and will be updated with final publication details once it is officially released.

If you use the UFPR-VeSV dataset in your research, please cite the paper:

* G. E. Lima, V. Nascimento, E. Santos, E. Nascimento Jr., R. Laroca, D. Menotti, "Toward Unified Fine-Grained Vehicle Classification and Automatic License Plate Recognition," *Journal of the Brazilian Computer Society*, vol. 32, no. 1, pp. 1-16, 2026. In Press. [[SBC-OpenLib]](https://journals-sol.sbc.org.br/index.php/jbcs/article/view/5899) [[arXiv]](https://arxiv.org/abs/2604.05271).

```
@article{lima2026toward,
  title = {Toward Unified Fine-Grained Vehicle Classification and Automatic License Plate Recognition},
  author = {G. E. {Lima} and V. {Nascimento} and E. {Santos} and E. {Nascimento Jr.} and R. {Laroca} and D. {Menotti}},
  year = {2026},
  journal = {Journal of the Brazilian Computer Society},
  issn = {1678-4804},
  volume = {32},
  number = {1},
  pages = {783-799},
  doi = {10.5753/jbcs.2026.5899}
}
```

## Related publications

A list of all our papers on vehicle identification can be seen [here](https://scholar.google.com/scholar?hl=pt-BR&as_sdt=0%2C5&as_ylo=2018&q=allintitle%3A+plate+OR+license+OR+vehicle+author%3A%22David+Menotti%22&btnG=).

## Contact

For any questions or comments, please contact Gabriel E. Lima ([gelima@inf.ufpr.br](mailto:gelima@inf.ufpr.br)).
