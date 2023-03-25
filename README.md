# Apki Aawaz


Our web application is specifically designed to help bridge the communication gap between individuals who are deaf or hard of hearing and those who do not know Indian Sign Language. With the help of this application, users can easily communicate with each other using sign language gestures that will be translated into letters.

This application is particularly useful for people living in India, where millions of individuals rely on Indian Sign Language for communication. By enabling people to communicate more easily, regardless of their familiarity with sign language, we hope to make communication more accessible for everyone. Our goal is to help promote inclusivity and improve communication for all.

# Video Demonstration


https://user-images.githubusercontent.com/68243425/227705573-3eb4b5f9-17e7-4604-8401-84f774f93c9b.mp4


## Presentation 

### [Apki Aawaz Presentation.pdf](https://github.com/radhika0910/Apki-Awaz/files/11066090/Hackathon.pdf)


## Model demonstration 

Here the model is detecting the signs shown to it in run time .
![Model detecting alphabet "A"](https://user-images.githubusercontent.com/97309084/227619083-2e441f24-2f88-4a4a-97f5-b7579459a46d.png)
![Model detecting b](https://user-images.githubusercontent.com/97309084/227619558-481ca5f1-cbeb-4502-ba96-7a752d939043.png) 


Demonstration of the model linking frequently asked questions to letters, making it easier for deaf individuals to effectively communicate their feelings.


![model detecting the ](https://user-images.githubusercontent.com/97309084/227619601-217d5d66-c533-4d07-a3d8-7daf4b2b9e5e.png)
![Screenshot (5)](https://user-images.githubusercontent.com/97309084/227619676-4aae46ad-6848-4915-92e7-74dc362afcb9.png)



## Run Locally

Clone the project

``` sh
git clone https://github.com/jay-arora31/Apki-Aawaz.git
```

Go to the project directory
``` sh
cd Apki-Aawaz

```

Install dependencies

```sh
pip install -r requirements.txt
```

Start the server

### Our project aims to develop an application that facilitates communication for individuals who are deaf or hard of hearing. The app comprises of three components:


#### 1. Sign-to-text converter: This feature allows users to input sign language, which is then converted to text and displayed on the screen.
```sh
streamlit run app.py
```

#### 2. FAQ section: The app includes a FAQ section that is linked to specific letters. Users can select a letter and view the corresponding FAQ.

```sh
streamlit run text.py
```

#### 3. Voice converter: The app also includes a voice converter that can read out the answers to the FAQs
```sh
streamlit run speak.py
```




## Team Web Warriors
- [@ jay-arora31](https://github.com/jay-arora31)
- [@radhika0910](https://github.com/radhika0910)
- [@Vivek_Devkar](https://github.com/vivekdevkar123)



