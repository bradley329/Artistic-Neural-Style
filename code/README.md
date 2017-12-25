Course project for computer vision

to run Gatys' single neural style transfer, run
python3 single_neural_transfer.py
content image and style image can be changed in single_neural_transfer.py
output image will be saved in current directory

to train neural net work for neural style transfer, run
python3 neural_style/neural_style.py train --dataset <dataset dir> --style-image <style-img dir> --save-model-dir <model-save dir> --epochs <epoch number> --cuda <whether cuda is available>