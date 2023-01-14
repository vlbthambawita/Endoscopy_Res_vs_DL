# Impact of Image Resolution on Deep Learning Performance in Endoscopy Image Classification: An experimental study using a large dataset of endoscopic images

This is the official repository for the paper: https://www.mdpi.com/2075-4418/11/12/2183


## How to train a model for specific input size?
> python train_and_test.py train --model resnet152 --input_img_size 32 --rescaled_to 32 \
> --data_root <<"data directory path which has two splits: split_0 and split_1">> \
> --out_dir <<"Directory to output checkpoints">> \
> --tensorboard_dir <<"Tensorboard directory">> \
> --bs <<"default=8>> 

* For more parameter options, please check the train_and_test.py file.


## How to test a pretained model for different input sizes?
python train_and_test.py test --input_img_size 32 --rescaled_to 32 --test_checkpoint <<best_checkpoint_path>> 

## Citation: 

>@Article{diagnostics11122183,
>AUTHOR = {Thambawita, Vajira and Strümke, Inga and Hicks, Steven A. and Halvorsen, Pål and Parasa, Sravanthi and Riegler, Michael A.},
>TITLE = {Impact of Image Resolution on Deep Learning Performance in Endoscopy Image Classification: An Experimental Study Using a Large Dataset of >Endoscopic Images},
>JOURNAL = {Diagnostics},
>VOLUME = {11},
>YEAR = {2021},
>NUMBER = {12},
>ARTICLE-NUMBER = {2183},
>URL = {https://www.mdpi.com/2075-4418/11/12/2183},
>ISSN = {2075-4418}}




