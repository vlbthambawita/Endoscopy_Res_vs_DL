# Impact of Image Resolution on Deep LearningPerformance in Endoscopy

## How to train a model for specific input size?
> python train_and_test.py train --model resnet152 --input_img_size 32 --rescaled_to 32 \
> --data_root <<"data directory path which has two splits: split_0 and split_1">> \
> --out_dir <<"Directory to output checkpoints">> \
> --tensorboard_dir <<"Tensorboard directory">> \
> --bs <<"default=8>> 

* For more parameter options, please check the train_and_test.py file.


## How to test a pretained model for different input sizes?
python train_and_test.py test --input_img_size 32 --rescaled_to 32 --test_checkpoint <<best_checkpoint_path>> 

## Citation: TBA



