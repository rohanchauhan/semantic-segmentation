# Semantic Segmentation
The dataset consists of images of Guns and Boxes with their RGB Segmented Mask. The goal was to train a semantic segmentation model using Pytorch. The mask for guns is in red, boxes in green and everything else is black.

#### Installation Instructions:
1. Clone the repository or download the zip file and go inside the directory using Command Prompt/Terminal.
2. Make a python3 virtual environment.
```python
python3 -m venv img-env
```
3. Activate the virtual environment.
```python
source img-env/bin/activate
```
4. Install the requirements.
```python
pip install -r requirements.txt
```
5. Download the original dataset in data folder. For example, we have provided 2 files to show folder structure. class_masks is automatically created by notebook.
6. Run jupyter notebook.
```python
jupyter notebook
```

#### Improving the Model
1. Try different combination of architecture and encoders for Semantic Segmentation.
2. Try out different hyperparameters for training the model.
