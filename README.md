# EC601 Homework 1: Face Detection in Python with OpenCV

## Authors
- Brian Appleton appleton@bu.edu
- Tony Cao tonycao@bu.edu

## Repository contents
- README.md: What you're reading now
- Trello.jpg: Screenshot of Trello workspace
- HW1: Directory containing the local files required to run our software

## Project description
The foremost goals of this assignment were to acquaint ourselves with GitHub, Slack, and Trello. To this end, we embarked on a week-long effort to customize the input and output of a face detection application that is supplied with OpenCV.

[OpenCV] (http://opencv.org/) is a powerful, open-source computer vision library that offers a host of functionality for image and video processing. Its capabilities include object detection, machine learning algorithms, GPU-accelerated processing, and motion detection.

Because both of us were less familiar with Python than C++, we chose to use Python for this assignment.

The demo application **facedetect.py** that was supplied with OpenCV performed face and eye detection on a still image to which random noise was added. We have modified the application to accept a *custom video* as input and detect the face and *smile* of the subject.

Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, "Rapid Object Detection using a Boosted Cascade of Simple Features". It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

## Build instructions




