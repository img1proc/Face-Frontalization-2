# Face-Frontalization-2 <p>
Face Frpntalization (2) <p>
(1)Face-Frontalization-2 , Kazuo Ohzeki<p>
input=several images.jpg in img6F; process frontalization by two parameters(r and s);<p>
output= frontalized images_r.jpg and images_s.jpg if succeeded in img6Fr and img6Fs;<p>
results: You can download result images by zip files <p>
Prerequisites : google colabratory,  Run-time type =T4GPU or CPU-only <p>
April 15th 2024 <p>
references: <p>
Original algorithm by Hassner et al., please cite; <p>
Tal Hassner Tal Hassner, Shai Harel, Eran Paz, and Roee Enbar, "Effective Face Frontalization in Unconstrained Images”, IEEE CVPR, pp. 4295-4304, June, 2015 <p>
Revised by Douglas Souza, combining python, openCV, and matlab. <p>
However, this code currently does not work as is. <p>
So I have improved it this time. According to <p>
Douglas Souza, Joseph Zhong, Face Frontalization on Feb 19, 2018， <p>
https://github.com/dougsouza/face-frontalization <p>
The points I have improved are: python2 to python3. Along with this, the urllib function was changed; Error when dividing into a small number; Fixed bugs that occurred with this fix.<p>
## <p>
If you use or discuss this Face-Frontalization-2, please cite the papers as follows; <p>
Kazuo Ohzeki, aki Saito Shiojiri, Koichi Kamijo, and Masami Suzuki, "Improving the Recognition Rate of Facial Expressions and Behavior through Frontalization and Data Augmentation", Proceesings of the International Conference on Computer and Automation Engineering (ICCAE) March 2024.<p>

FF-files.zip contains all neccesary program files. Unzip as FF-files.zip  <p>
A trained data file, "shape_predictor_68_face_landmarks.dat.bz2"(62MB) is needed. <p>
Please set the file  "shape_predictor_68_face_landmarks.dat.bz2" in dlib_models, <p>
/content/dlib_models <p>

Structure of directory and files:<p>
dlib_models--DataAlign2LFWa.<p>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;  mat,eyemask.mat, <p>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;  model3Ddlib.mat<p>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;  shape_predictor_68_face_landmarks.dat.bz2<p>
img6F<p>
img6Fr<p>
img6Fs<p>
dataAlign2LFWa.mat<p>
FF-files.zip<p>
camera_calibration.py<p>
chexk_resources.py<p>
eyemask.mat<p>
face_detector.py<p>
face_feature_detect.py<p>
frontalize.py<p>
img6F.zip<p>
model3Ddlib.mat<p>
test.jpg (not used in this sample)<p>
