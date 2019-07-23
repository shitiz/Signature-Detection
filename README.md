# Signature-Detection
It is to detect whether the contract files are manually signed or not. The input can be any type of contract file in the form of image with single or multiple signature blocks. Each signature block can be signed or un-signed.

I have referred one research paper written by İlkhan Cüceloğlu & Hasan Oğul which I have uploaded to the same repository path with the filename "cvww14.pdf". Though I have referred it to implement only few of the sections but could be helpful for the people working on the same problem.

First, I am reading the contract image and passing it to "SaveCroppedSigImages" function to save the croppped images with block of signatures. After which all the cropped signature blocks are read and preprocessed with Open CV Erode function to make the image more clear for detection. Then connected components are found with countours on it to check whether there are signatures present or not in each of the cropped block of signature. 

Please mail me for any comments or suggestions at shitizaggarwal.ai@gmail.com
