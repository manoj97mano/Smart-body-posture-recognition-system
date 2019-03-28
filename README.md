## SMART BODY POSTURE RECOGNITION AND GUIDING SYSTEM 

## Problem Statement
  To capture the hand gesture and check whether the hand is placed in the right gesture using image processing system.If the hand is in wrong gesture then arriving at accurate results are not possible.This problem is solved using smart body posture recognition.
## Abstract
  A gesture is a form of nonverbal communication or non vocal communication. Gestures include movement of the hands, face, or other parts of the body. Gestures allow individuals to communicate a variety of feelings and thoughts. Gesture processing takes place in areas of the brain such as Broca's and Wernicke's areas, which are used by speech and sign language. We provide a system that captures the image of the whole body and it recognizes the body posture of an individual and gives them the right posture for calculating the blood pressure through image processing.
## Modules
- Posture module[M.Antony Raj]
- Result module[B.Padmajaa]
- Back end[M.Manoj]
## Posture module
  Captures the image of the hand and compares it with the trained data set.This data set contains the images of the hand that are captured through tensor flow.
## Result module
  This module gets the result image and it analyses the gesture , if the gesture is right it provides the accurate results.If the gesture is wrong it gives the suggestions to have the right posture.
## Back end
  Back end module gets the data set from Open CV and compares the image with the present  image captured by he web cammera ,If the present image and the image in the data set matches it displays  the accurate results.If the present image and the data set image does not match it provide suggestions to have the correct posture.
 ## Project Status
 - Posture module[80% completed]
 - Result module[70% completed]
 - Backend[65% completed]
 ## Pending works
 - Result module[comparison of images]
