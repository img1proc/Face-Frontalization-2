# Face-Frontalization-2
Face Frpntalization (2)
(1)Face-Frontalization-2 , Kazuo Ohzeki
input=several images.jpg in img4F; process frontalization by two parameters(r and s);
output= frontalized images_r.jpg and images_s.jpg if succeeded in img4Fr and img4Fs
resulys: download by zip files
Prerequisites : google colabratory,  Run-time type =T4GPU
April 15th 2024
references:
Original algorithm by Hassner et al., please cite;
Tal Hassner Tal Hassner, Shai Harel, Eran Paz, and Roee Enbar, "Effective Face Frontalization in Unconstrained Images”, IEEE CVPR, pp. 4295-4304, June, 2015
Revised by Douglas Souza, combining python, openCV, and matlab.
However, this code currently does not work as is.
So I have improved it this time. According to
Douglas Souza, Joseph Zhong, Face Frontalization on Feb 19, 2018，
https://github.com/dougsouza/face-frontalization
The points I have improved are: python2 to python3. Along with this, the urllib function was changed; Error when dividing into a small number; Fixed bugs that occurred with this fix.
##
If you use or discuss this Face-Frontalization-2, please cite the papers as follows;
Kazuo Ohzeki, aki Saito Shiojiri, Koichi Kamijo, and Masami Suzuki, "Improving the Recognition Rate of Facial Expressions and Behavior through Frontalization and Data Augmentation", Proceesings of the International Conference on Computer and Automation Engineering (ICCAE) March 2024.

FF-files.zip contains all neccesary program files and trained data. Unzip FF-files.zip 

Structure of directory and files:<p>
dlib_models--DataAlign2LFWa.<p>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;  mat,eyemask.mat, <p>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;  model3Ddlib.mat<p>
img5F<p>
img5Fr<p>
img5Fs<p>
dataAlign2LFWa.mat<p>
FF-files.zip<p>
camera_calibration.py<p>
chexk_resources.py<p>
eyemask.mat<p>
face_detector.py<p>
face_feature_detect.py<p>
frontalize.py<p>
img5F.zip<p>
model3Ddlib.mat<p>
test.jpg<p>
