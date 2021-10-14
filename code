#importing libraries
import cv2
import numpy as mp
# reading image
img = cV2.imread("cat.jpeg")
# Edges
gray = cv2.cvt Color (img, cv2. COLOR_BGR2GRAY )
gray = cv2.medianBlur (gray, 5)
edges = cv2.adaptive Threshold (gray, 255,cv2.ADAPTIVE_THRESH_MEAN _C,cv2.THRESH_BINARY, 9, 9)
# Cartoonization
color cv2.bilateralFilter(img, 9, 250, 250)
cartoon = cv2.bitwise_and(color, color, mask=edges)
cv2.imshow( "Image", img)
cv2.imshow( "edges", edges)
cv2.imshow ("Cartoon", cartoon)
cv2.waitkey (0)
cv2.destroyAllWindows()
