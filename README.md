# Ketan-Verma-21je0468-open-CV
This project conatins codes of python , which is in use to read the aruco markers and a image  that have some shapes of definite colour which are matched to the aruco marker ids.
In this project, firstly the shapes in the image was identified and the colour of the shapes was aslo found with help of a bunch of cv2 functions
after finding the shapes and the colour , the aruco marker we read nad it's id was determined.
As we got the id , we matched it with the colour codes .
Then the main work was started , which is to paste the aruco markers over the shapes in the proper orientation , taking care that the aruco code was exactly same as the colour code.
Now to paste the aruco marke over the shapes , the aruco markrs had to be aligned in the proper manner. so to do that the aruco markers should be roted in the same fashion in which th shapes are.
After successfull rotation , the aruco markers were pasted over the shapes and hence the task was done.
Here are the function which were used to do this task:
(a) User Defined fuctions:
    (1)countorfind()
    (2)rotate_img()
    (3)augmenting()
    (4)find_aruco()
(b) Function of cv2,numpy,aruco and  math library
     # functions of cv2
    (1)imread()
    (2)threshold()
    (3)findContours()
    (4)approxPolyDP()
    (5)boundingRect()
    (6)minAreaRect()
    (7)boxPoints()
    (8)getRotationMatrix2D()
    (9)warpAffine()
    (10)findHomography()
    (11)warpPerspective()
    (12)fillConvexPoly()
    (13)cvtColor()
    (14)aruco.detectMarkers()
    (15)resize()
    (16)inRange()
    (17)bilateralFilter()
    (18)GaussianBlur()
    (19)imwrite()
    (20)waitKey()
    (21)destroyAllWindows
    # functions of numpy 
    (1)array()
    (2)float32()
    # functions of math
    (1)sqrt()
    (2)atan()
    # functions of aruco
    (1)aruco.Dictionary_get()
    (2)aruco.DetectorParameters_create()
    
