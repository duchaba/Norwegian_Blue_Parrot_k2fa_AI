# Norwegian_Blue_Parrot_k2fa_AI
Welcome  to the Norwegian Blue Parrot project. It is a series of articles for demystifying AI and Deep-Learning through jovial, in-depth descriptions, fun  interactive, and a touch of geekiness.

# Introduction

Welcome to the first "Norwegian Blue Parrot" project article. For each AI project, I write the code and show you how it works. You can test it using a mobile phone, tablet, and laptop (on the website, https://nbp3-webclient-2020.web.app/). Furthermore, you can see for yourself the effectiveness and the shortcoming of each AI model.

![introduction](https://nbp3-webclient-2020.web.app/image/undraw_true_love_cy8x.svg)

I have developed dozens of AI projects, and with each AI model, I learn a bit more insights  into the world of Artificial Intelligence.

The audience or point of view  (POV) for demystifying AI is primary for AI enthusiasts and friends with a curious mind. However, I am a full-stack programmer, a solution architect, and an AI scientist, and therefore, I will not shy away from the math and the coding, but I will remain steadfast to the primary POV.

Before digging into the technicalities, we will have fun test-driving  the AI model. After we have a firm grasp on "what" we are trying to demystify, we will travel a full journey from coding to gathering the data. We will take a break to understand the particular data biases , both the conscious biases and the unforeseen consequences. We will reach the journey conclusion at the use-cases, i.e., what is the purpose of this AI project, and what other possibilities could this AI model can be used either ethically or  feloniously.

>## _So if you are ready, let's take a collective calming breath …  … and begin._

The "k2fa" AI project is for kids to learn about farm animals. Think of "k2fa"  as kids wandering through a farm and naming the animal that they see.

More concisely, "k2fa" is Deep Learning Convolutional Neural Network (CNN) image classification model.

Before charging ahead with an in-depth explanation, let's test the "k2fa" kids. Show the "k2fa" kids a picture, and they will identify it. Scroll down  to the "Prediction section" and have fun.

# Prediction

Hello, from "k2fa" kids. Since "k2fa" kids are not robots, you are selected to be the avatar  , i.e., the hands and feet of the "k2fa" kids.

![prediction image](https://nbp3-webclient-2020.web.app/image/undraw_experience_design_eq3j.svg)

Imagine yourself as a "k2fa"  kid, walking around the farm, taking photos  , or uploading them using iPhone, Android phone, tablet, or laptop. This website is mobile-friendly.

Take a picture or upload an image of a dog, a chicken, a cow, a wolf, your face, your friend, or even an armadillo. The "k2fa" kids will immediately  identify which of the thirteen farm animals is the closest match to the image, including the confidence level. Furthermore, the "k2fa" kids will show the top three inferences.

One should run the test many times. It will give a clear understanding of what is possible and what is not.

There are copious statistics that accompany each inference. The in-depth explanation for the statistics, data, insights, biases, and limitations will be in the next section, but for now, enjoy  being a "k2fa" avatar.

### Goto the k2fa website to test it, https://nbp3-webclient-2020.web.app/#predict

A sample result is as follows.

![cat result image](https://media-exp1.licdn.com/dms/image/C4D12AQFcyk7e7VszMg/article-inline_image-shrink_1000_1488/0?e=1602115200&v=beta&t=fZ-OJsgyyT6W7LqdU4s4wkTtja5leFpx74uqUEHT7BM)

![cat stat](https://media-exp1.licdn.com/dms/image/C5612AQFsxUUUvbJ4Ow/article-inline_image-shrink_1000_1488/0?e=1602115200&v=beta&t=c2Ue9AWM7GAvYpz82d3kRTMXsxG_ubFPAmE48IW1_UU)

## Legends:

1. The "Delta Time" is a measurement of the elapsed time for each function.

- The "Predict"  time is the principal value. It calculates the time "k2fa" takes to give a prediction. On average, during high system-load, it is less than half  of a second.

 - The "1_cycle" time is calculated from a moment the device, e.g., iPhone or laptop, issues the request to it received the response from the server. It includes the network time, image upload, and JSON API response time.

 - The "Architecture" section will explain the timing in-depth.

2. The "Model version" shows that the AI model dependents and its software version. The "Model" section will give a full explanation.

3. The "Trained" describes the "k2fa" training statistics. The "Model" and the "Data" section will explain it further.

4. The "AI Deployed System" is the detailed information about the "k2fa" deployed system.

- It is comparable to a "microservices,"  and it is not the massive AI training server.

- There is no GPU  , and the CPU RAM is only 2 GB. The reported "free RAM" for each request is for monitoring memory leaks.

- Google App Engine  enables auto-scaling automatically.

- The "Architecture" section will fully explain it.

5. The "Raw inferences" is raw data response from the API. It contains the thirteen  possible farm animals and the associate level of confidence.

# Deep Learning CNN Model

The Deep Learning convolutional neural network (CNN) model is like the donut of the AI discipline. It's easy. It's sweet, and it is the go-to  solution for image classifier problems.

![CNN Model image](https://nbp3-webclient-2020.web.app/image/undraw_donut_love_kau1.svg)

The following is not a step by step instruction, but it covers the essential notes for an AI scientist to replicate the model independently.

Occasionally, the AI discipline uses specialized terminologies that impede the understanding of simple concepts. It is a bad practice  because it encourages the memorization of vocabulary rather than original thinking. In other words,

>## _A rose by any other name would smell as sweet_

"AI" and "Deep Learning" are the two terminologies that worth more in-depth explanations.

Artificial Intelligence (AI) has no formal, concise, or verifiable universal accepted definition. The popular interpretation is  "a machine or a program that mimics cognitive functions and algorithms."

From Ada Lovelace's programs for Charles Babbage's Analytical Engine in the 19th century to the 1949 IBM-701 Checker program by Arthur Samuel to Apple's Siri, they can all be classified as AI.

The fuzziness  is the level of complexity in the algorithms, i.e., how complex does the algorithm has to be for it to be considering as an intelligent machine? Is human the only intelligent creature on earth? Does everyone on the planet have the same innate intelligence?

Furthermore, in movies, books, and social media, there is an overlap between "consciousness"  and "intelligence." Being conscious does not imply being intelligent, and having intelligence does not mean having consciousness.

For example, a dog has awareness but can't do the math , and the Apple' Siri program can do trillions of calculation per second but can't feel happiness .

To demystify AI, from this point onward, any machine algorithm that has more than  one trillion calculations will be anointed as "Artificial Intelligent."

"K2fa" model has an estimate of 2.7e-14 calculations per fit-cycle, and therefore, "k2fa" is an AI.

"Deep Learning" is a sub-field of the AI discipline. It's loosely model after the inner working of the brain neurons, and hence the innovative name "convolutional neural network" (CNN). It based on the  "universal approximation" theorem (UAT).

The awe-inspiring truth is that this one theorem can tell the difference between a cat and a dog, skin cancer cells from healthy cells, classifying dozens of objects in a picture, identify tweets sentiment, recommend movies, predict sales, and thousands other related tasks in four classifications. They are image classifier, image segmentation, natural language processing (NLP), and prediction using tabular data.

The "awe" in the awe-inspiring is that the UAT does not need to understand the  causality. In other words, the UAT does not use rules-based logic, such as a cat does not have feathers or a cow has four legs.

"K2fa" model is built on the fantastic "fast.ai (https://fasta.ai)" library by Jeremy Howard, Rachel Thomas, and Sylvain Gugger. The goal is for an AI scientist to have essential information to replicate the "k2fa" model independently. The salient point is that it is just math and coding,  no magic. The recipe of the "k2fa" Deep Learning convolutional neural network image classifier is as follows.

![Deep Learning image](https://nbp3-webclient-2020.web.app/image/undraw_blooming_jtv6.svg)

1. ### Collect data

- The full description of collecting data is in the "Data" section below. The steps are as follows.
- Go to  the farms to take pictures and videos.
- Search and download non-copyright images using Google image search, Instagram, and Facebook.
- Use the "Download All Images" app, a Chrome extension by Mobile First.
- Separate the images into one of the thirteen farm animal folders.
- True to form, the data collection takes most of the time in this project.

![collect data image](https://nbp3-webclient-2020.web.app/image/farm.jpg)

2. ### Clean data

- Verify each image in the correct folder.
- Write python scripts to resize, crop, and center each image to 224 by 224 pixels.
- Write python scripts to rename filename to be "chicken1.jpg", "chicken2.jpg", etc. It is optional, but it helps.
- Write python scripts to split each folder to have sub-folder-image "train" and "valid."
- Each folder contains a different number of files, e.g., the rabbit-folder has 612 images, while the dog-folder has 1028 images. Therefore, splitting 20%  per folders for "valid" is fairer than randomly allocating 20% overall for validation.

![clean data image](https://nbp3-webclient-2020.web.app/image/chicken.jpg)

3. ### Calculate the Data-Bunch mini-batch size

- Query the cloud-server (Google Colab-Pro) for CPUs (4), available RAM (24 GB), GPUs (1), available GPU-RAM (16 GB). Refer to Predict section above.
- Verify all trained images are 224 by 224 pixel. The total images are 11750.
- The calculated batch-size is 64 .
- The reason for using mini-batch and stochastic gradient descent (SGD) is because to train all images in one-cycle takes more GPU RAM than most cloud servers have available.

![mini batch size image](https://nbp3-webclient-2020.web.app/image/img-2b.jpg)

4. ### Create the Data-Bunch

- Create "fastai.vision.ImageList" from ".from_folder()" command.
- Separate the "train" from "valid" by doing ".split_by_folder(train='train', valid='valid')" command.
- Assign the label from the folder-name, i.e. using ".label_from_folder()" command.
- Increase the number of train-images with data-augmentation using "fastai.vision.LabelLists.transform" command.
- Create the data-bunch using the fast.ai method. Using ".show_batch()"  command to verify the data-bunch is correct.
- Use "fastai.vision.imagenet_stats" command for image normalization.

![data bunch image](https://nbp3-webclient-2020.web.app/image/databunch1.jpg)



