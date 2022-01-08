# BCN 20000 tools for assembling and training

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" /></a>

This repository gives access to the tools created and used
for assembling the BCN 20000 dataset as well as the training code for the baseline ensamble model. The dataset itself is available for download at the [Wherever the data is](https://google.com).

<hr>


# BCN-20k
Data pre-processing and training used for the BCN 20k scientific paper



<hr>

## Cropping

Following technique was used crop the dermatoscopies which with dark background:
- [`preprocessing/image_cropper.py`](preprocessing/image_cropper.py):


![Original (a), (b) and (c) and cropped images (d), (e) and (f)](https://github.com/CarlosHernandezP/BCN-20k/blob/main/Cropped_uncropped_figure.png)

<hr>
