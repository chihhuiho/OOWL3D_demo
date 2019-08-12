# OOWL3D_demo
This is a visual demo website for OOWL3D dataset provided by UC San Diego Statistical Visual Computing Lab. This dataset is still expanding. Please contact Chih-Hui Ho (chh279@ucsd.eng.edu) for your usage.

## Usage
1. Dowload the dataset (around 5GB)
```
git clone https://github.com/chihhuiho/OOWL3D_demo.git
cd models
```
2. All models are stored in hierarchical structure: Class --> Objects --> .ply, .obj

## Contribute 3D models
1. Dowload the dataset (around 5GB)
```
git clone https://github.com/chihhuiho/OOWL3D_demo.git
cd models
```
2. Create a class directory if it does not exist
```
mkdir <class_name>
cd <class_name>
```
3. Create an object directory
```
mkdir <object_name>
cd <object_name>
```
4. Upload 4 files (.jpg, .mtl, .obj and .ply). The filename should be the object name.
5. Repeat 2-3 until all new models are uploaded
6. Create HTML for every object
```
python generate_html.py
```
7. Push new 3D models
8. Check your new models online http://www.svcl.ucsd.edu/projects/OOWL/oowl3d

## Acknowledgement
The website is created based on https://github.com/xxv/jsc3d/tree/master/jsc3d. Thanks for all the contributers.