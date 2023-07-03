# cnn_tf
contains the dataset processing, model construct and training, model quantization and convert


# 目录
## config
## dataset
  tfrecord_data.py 
  
    ```
    class TFrecordData():
      def __init__(tfr_dir, ...)

      def create_tfrecord():

      def decode_tfrecord():
    ```
    
  data_generator.py
  
    ```
    def get_datagenerator()

    
    ```
  data_augument.py
  
  ```
  def keras_aug():

  def image_aug():

  
  ```
## metrics
  计算各种指标的脚本
## quantization
  量化代码

## train

## test

## utils

## visualization 
  可视化
  data_visual.py

  loss_visual.py
  ...
## yaml


##
