# EmoteCare

Website: https://vanivaranya.github.io/EmoteCare/
<br>
PPT Canva link: https://www.canva.com/design/DAF8ToHueOw/ipq2jKKHJupJdcCbh_OoyQ/edit?utm_content=DAF8ToHueOw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
<br>
Demo video link: https://www.loom.com/share/f6668ff386894aa88f38b48e2f01922a?sid=f1d62f10-7db7-43a7-a56c-e8f0a2d9c4f8

## Problem Statement

Many individuals hesitate to seek therapy due to societal taboos and fear of judgment, while personalized one-on-one therapy sessions are often inaccessible and financially burdensome. This leads to prolonged suffering, a lower quality of life, with depression and suicide in extreme cases.

## Solution
Our platform addresses the stigma surrounding mental health with accessible and affordable online therapy sessions. Powered by advanced AI, CNN, we offer therapists real-time emotional insights for personalized care. Users benefit from the extended website features, enhancing their well-being beyond therapy.
Our problem comes under SDG Goal 3: Good Health and Well-being.

## Key Features
- *Destigmatizing Mental Health:* Accessible and affordable online platform for therapy sessions with scheduling options.

- *Real-time Emotional Insights:* AI-driven facial emotion detection providing therapists with real-time data for better understanding, countering any loss due to virtual space .

- *Personalized Care:* Ability to track emotional trends over time, allowing therapists to tailor treatment plans and interventions.

- *Extended Website Features:* Access to a chatbot, self reflect sessions, weekly report, therapist allocation, session scheduling, and mental health resources, for overall well being.

## Improvments

- *Added a chatbot* used openai api chatbase.co for integrating a chatbot that is empathetic and friendly.

![alt text](https://github.com/s-sweta/Emote-Care/blob/2311364a9a40a5df9f111dab785789aea06ed317/images/website_with_chatbot.png)

- *Improved Accuracy* Combined another dataset with the previous one which improved accuracy from 63% to 67%.


### Dataset Information
- https://www.kaggle.com/datasets/msambare/fer2013
- https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer

## Tech Stack
### AI/ML

*Framework:* TensorFlow; *Model:* CNN 

Worked on CNN and VGG16 models. Combined two datasets. While the CNN model offers much better accuracy, VGG16 gives a simpler architecture with fewer trainable parameters. But we proceeded with CNN as we focus more on the accuracy.

### Frontend 
HTML, CSS, Javascript 

### Backend
Flask, SQLite, OpenCV

## Future Scope

**Improving accuracy and architecture:** Will be improving the efficiency of the model by training it on the data gradually received from the users.


**Community Engagement:** Partnering with advocacy groups and organizations to reduce mental health stigma and promote awareness of online therapy options.
