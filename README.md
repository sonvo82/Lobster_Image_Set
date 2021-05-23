# Lobster_Image_Set

**Description of Dataset:**

This is the raw image dataset of Southern Rock Lobster used for the research on automatic grading and identification.

**Dataset information:**

- Location of data collection: at a lobster processor in Tasmania - Australia.
- Number of lobsters picked from tanks from data collection: 238.
- Number of images per lobster: between 21 to 33.
- Image resolution: 1944x2592 pixels.
- Name of image: SRLxxxxx.jpg. The first three "xxx" is for lobster number and the last two "xx" is for image number per lobster.
- Camera setup : using a set of 3 Raspberry Pi camera V.2 (8MP). These three cameras were setup above the objects with the distance to the PVC pipe surface (not the ground) at around 36cm corresponding to approximately 28 cm to lobster’s carapace. This height allows the sensor frame to reasonably fit various sizes of animals.
The lens of Pi cameras was manually modified to direct the focus to the animals for best image quality. The side cameras in this setting create a skew angle of around 20 degrees to the central one. This setting allows multiple image versions of the same object to be generated for training and testing with recognition techniques.
- Lighting condition: using both available roof lights in the room and two extra diffused lamps placed on both sides of the animals.
- In addition the image set, the software also produces a csv logfile that contains information of the lobsters including:
SRLid, imgname, sex (male or female), colour group (dark red or pale red), middle camera distance (mm), carapace length (mm), lobster weight (g). Because different calipers were used to measure carapace of lobsters, it is recommended to use the sizes of last 100 lobsters to validate your automatic grading results.

**If you are using this dataset for your research, please cite one of the following papers:**

Vo, SA, Scanlan, J & Turner, P 2020, 'An application of Convolutional Neural Network to lobster grading in the Southern Rock Lobster supply chain', Food control, p. 107184.

Vo, SA, Scanlan, J, Turner, P & Ollington, R 2020, 'Convolutional Neural Networks for individual identification in the Southern Rock Lobster supply chain', Food control, p. 107419.




