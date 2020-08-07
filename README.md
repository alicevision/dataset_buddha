# Buddha dataset

![](capdigitalCourtyard.png)


## The dataset
This dataset collects 67 images of a Buddha head placed on a table.
The images cover the whole object.

## Dataset Structure
The dataset is composed of the following directories:

 - `buddha` contains the full dataset of 67 images;
 - `buddha_mini6` is a short version with only 6 selected images, usually used for quick testing.

For both dataset, and for each camera a file containing the estimated projection matrix is given, so that the MVS algorithm can be tested from this geometry.

## License

This dataset is released under the Creative Commons Attribution 4.0 license (see [LICENSE.md](LICENSE.md))

## References

- AliceVision Photogrammetric Computer Vision Framework: http://alicevision.github.io
- The LADIO project: http://www.ladioproject.eu/

## Citation

If you are referring to or using this dataset please cite it as

```
Simone Gasparini, Fabien Castan, & Yann Lanthony. (2017). Buddha Dataset (Version 1.0) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.1203283
```

BibTex
```
@misc{buddhaDataset_2017_1203283,
  author       = {Simone Gasparini and
                  Fabien Castan and
                  Yann Lanthony},
  title        = {Buddha Dataset},
  month        = jan,
  year         = 2017,
  note         = {https://github.com/alicevision/dataset_buddha},
  doi          = {10.5281/zenodo.1203283},
  url          = {https://doi.org/10.5281/zenodo.1203283}
}
```

## Acknowledgements
This dataset has been developed during the [LADIO](http://www.ladioproject.eu/) project funded by the European Union’s Horizon 2020 research and innovation programme under grant agreement No 731970.

## Authors

Simone Gasparini
Fabien Castan
Yann Lanthony
