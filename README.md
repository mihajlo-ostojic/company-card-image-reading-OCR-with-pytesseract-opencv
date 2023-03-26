# Company card image reading OCR with pytesseract opencv
Computer vision project that focuses on reading business card images and extracting relevant information using Optical Character Recognition (OCR) techniques.  The project uses the Python programming language and several popular libraries for image processing, including PyTesseract and OpenCV.


Dateset I'm working with contains images with indentity card that contain name, birthdate, job position, social security number, company name and image of persone. I got this dataset for university project, so i will not upload it. I think it is make using mswordidcards com, and is not available online. Feel free to make your own card or find some dataset online.

Example from dataset:
![image_example](https://user-images.githubusercontent.com/74563726/227800881-f6ff1972-afef-42e2-b65e-50d3a3fe2253.png)


Image rotation and cropping are applied after what we got important part of image.
Example:
![example_crop](https://user-images.githubusercontent.com/74563726/227800971-6aaff713-aafe-4526-9bf4-8e2c886e7ec0.PNG)



After all of that tesseract is applied for reading image text.
All code is explained in provided notebook, "CompanyIdentityDocumentReadingOCR.ipynb".

At the time of making notebook, version of libs were:

cv2 : 4.7.0

np : 1.22.4

re : 2.2.1

pytesseract : 0.3.10
