# Smart Phone Detection using YOLOv3

## Project Overview

Mobile phones are everywhere in the modern, highly digital world and have managed to find a place for themselves as tools in communication, information access, and many other daily activities. This, however, comes with a cost: challenges to environments where their use is considered disruptive or even prohibited. These include educational institutions where mobile phones can be bad for learning; examination settings where they engender cheating; and during professional meetings, their presence may undermine the integrity of the discussions and give way to distractions.

The use of cell phones within school environments has for so long been perceived as a double-edged sword. On the positive side, they are powerfully education-based since students can access either information or learning tools. On the negative side, they have been huge distractors. Students may be lured into scrolling through their social media accounts, playing games, or messaging their friends, hence decreasing the level of engagement and eventually academic performance. Quite often, these mobile phone policies are hard to implement and administrators, as well as educators, end up resorting back to manual supervision, which is not effective and reliable.

In examination situations, mobile phones are a severe threat to the integrity of the process of the examination. Indeed, many incidents of cheating on examinations that involve mobile devices have already been reported whereby students use their phones to either research answers or communicate with other students. This not only undermines the fairness of the exam process but also devalues the class results of students who do not cheat. The logistical challenge of ensuring that no student has access to a mobile phone during exams demands constant vigilance.

Mobile phones may be very disruptive, especially when used in meetings at a place of work. Uproar from the mobile phone distracts the key discussions—therefore, less focus, hence reduced productivity. Moreover, in very high-level meetings where confidentiality is required, the presence of a mobile phone may pose some security risks, for instance, unauthorized recording of information or even leaking out.

In view of these challenges, there is an apparent need for an effective automated solution to detect a mobile phone in real-time. An effective detection system will equip educators, exam invigilators, and professionals with the tools to continue to maintain a controlled environment—a controlled environment in which mobile phones are used appropriately and do not interfere with intended activities.

Current methods of mobile phone detection mostly include physical searches or observation by a human, which is time-consuming and prone to error. Such methods also prove to be quite impractical in large or dynamic environments for continuous monitoring purposes. What is needed is a technological solution that seamlessly integrates with these environments to provide continuous monitoring in real-time without disrupting activities at hand.

In light of this, this project has the objective to design a robust and efficient system for real-time cell phone detection using deep learning techniques. We are going to harness the power of the YOLOv3 object detection model to come up with a solution that provides high-accuracy cell phone detection, speed suitable for real-time applications.

The task suits very well with YOLOv3 due to its well-balanced accuracy and speed. Unlike the conventional technique for object detection, which involves repeated passes over an image, YOLOv3 processes the full image in one pass, making it substantially faster than many other techniques. This will be very important in real-time applications, wherein delays in detection may render the system ineffective. Moreover, the architecture allows YOLOv3 to handle small objects and images of different scales, which is important in detecting mobile phones in various environments.

By training YOLOv3 on a custom dataset of images with cell phones, we have fine-tuned it to be capable of recognizing a cell phone in almost any scenario. That differs in light conditions, backgrounds, and orientations, therefore the model can be well applied in real-world scenarios. The ultimate objective is to deploy the model in environments where mobile phone detection may be of critical importance, just to provide that tool which enhances capability in management and control over mobile phone use effectively.

The project does not only answer a dire need in a myriad of settings, but also contributes to the value obtained in the sprawling field of computer vision by showing the world what deep learning models are capable of when they are put to work. In case of its success, the solution will help bridge gaps in other areas requiring object detection, thus demonstrating the versatility and possibilities of deep learning in the resolution of complex problems.

## Group No - 7
- Tenzin Rinchen
- Nima Arabi 
- Ledi Caushi


## Table of Contents

- CV_project.ipynb
- Model/Yolov3.cfg
- Model/Coco.names
- Model/Yolo.weights

## References

- YOLO: You Only Look Once - Paper Link
  https://arxiv.org/abs/1506.02640
- Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks
  https://arxiv.org/abs/1506.01497
- Deep Learning for Object Detection: A Comprehensive Review nse.com/licenses/mit/)
  https://arxiv.org/abs/1807.05511
