Source: https://pi-cai.grand-challenge.org/

Imaging data has been released via: [**zenodo.org/record/6624726 (DOI: 10.5281/zenodo.6624726)**](https://zenodo.org/record/6624726)  

Annotations have been released and are maintained via: [**github.com/DIAGNijmegen/picai_labels**](https://github.com/DIAGNijmegen/picai_labels)


Download all folds

```sh
curl -C - "https://zenodo.org/record/6624726/files/picai_public_images_fold0.zip?download=1" --output picai_public_images_fold0.zip
curl -C - "https://zenodo.org/record/6624726/files/picai_public_images_fold1.zip?download=1" --output picai_public_images_fold1.zip
curl -C - "https://zenodo.org/record/6624726/files/picai_public_images_fold2.zip?download=1" --output picai_public_images_fold2.zip
curl -C - "https://zenodo.org/record/6624726/files/picai_public_images_fold3.zip?download=1" --output picai_public_images_fold3.zip
curl -C - "https://zenodo.org/record/6624726/files/picai_public_images_fold4.zip?download=1" --output picai_public_images_fold4.zip
```

Unzip all folds

```sh
unzip picai_public_images_fold0.zip -d ./prostate_cancer_segmentation/raw_data
unzip picai_public_images_fold1.zip -d ./prostate_cancer_segmentation/raw_data
unzip picai_public_images_fold2.zip -d ./prostate_cancer_segmentation/raw_data
unzip picai_public_images_fold3.zip -d ./prostate_cancer_segmentation/raw_data
unzip picai_public_images_fold4.zip -d ./prostate_cancer_segmentation/raw_data
```

And download labels

```sh
git clone https://github.com/DIAGNijmegen/picai_labels ./prostate_cancer_segmentation/raw_data
```