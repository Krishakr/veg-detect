# veg-detect
Where you can use simple edge impulse to classify images. It is pretty easy to do and for this one I am detecting the difference between potato's, tomato's and broccoli. But you can do whatever. 

It uses supervised learning. Which means you label the data you collect. This is a good way to do it because you can label your data so your AI doesn't become confused.

It uses a transfer-learning model with a backbone of MobileVet2. This is for image classification, depending on what you classify your model will change.

The AI models it uses is Yolo-Pro and FOMO 
  - Stands for faster objects more objects
  - Most  models spend a lot  of computing power trying to figure out the exact height and width of a image
  - Fomo cuts the image into a grid
  - It basically trains/classifies by each box in the grid
  - Can be used for counting things and traking the basic position of small item
  YOLO - PRO:
  - Stands for "YOU ONLY LOOK ONCE"
  - Edge impulse created YOLO-Pro
  - Used for  knowing the exact scale,size and to classify an image
  - Needs more power than FOMO
