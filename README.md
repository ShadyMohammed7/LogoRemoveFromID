# LogoRemoveFromID
This is a case where I was tasked to detect the logo containing ( جمهورية مصر العربية بطاقة تحقيق شخصية ) from given Egyptian IDs and remove it then return the image. I used SIFT for this task with some preprocessing. Then used inpainting with TELEA fill technique to remove the tracks of logo removal from image.

I have also included my YOLO v8 model and its parameters as a history for what I have been through. It's just a proof of concept not a full solution.


Disclaimer:

IDs were retreived from kaggle https://www.kaggle.com/datasets/mostafaebrahiem/egyptian-ids. They were publicly available.
