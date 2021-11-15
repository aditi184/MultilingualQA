# Multilingual Question Answering

This work is on the task of question answering in Indian languages, Hindi and Tamil. It is used for submission in a Kaggle competition, [chaii - Hindi and Tamil Question Answering](https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/overview), which is an initiative of **Google Research India** to improve the performance of NLU models in Indian languages.

**chaii-1** is a question answering dataset in Hindi and Tamil. Given a context and question, the goal of question answering is to predict the answer to the question by selecting a span from the context. Consider the following example from the dataset: 

**Context**: मानव कंकाल शरीर की आन्तरिक संरचना होती है। यह जन्म के समय 300 हड्डियों से बना होता है और यवाव ु स्था में कुछ हड्डियों के संगलित होने से यह २०६ तक सीमित हो जाती है।[1] तंत्रिका में हड्डियों का द्रव्यमान ३० वर्ष की आयु के लगभग अपने अधिकतम घनत्व पर पहुँचती है। मानव कंकाल को अक्षीय कंकाल और उपांगी कंकाल में विभाजित किया जाता है। अक्षीय कंकाल मेरूदण्ड, पसली पिजर ं और खोपड़ी से मिलकर बना होता है। उपांगी कंकाल अक्षीय कंकाल से जड़ुा हुआ होता है तथा असं मेखला, श्रोणि मेखला और अधः पाद एवं ऊपरी पाद की हड्डियों से मिलकर बना होता है। मानव कंकाल निम्नलिखित छः कार्य करता है: उपजीवन, गति, रक्षण, रुधिर कणिकाओं का निर्माण, आयनों का भंडारण और अतं : स्रावी विनियमन। मानव कंकाल अन्य प्रजातियों के समान लगिैं क द्विरूपता नहीं रखता लेकिन मस्तिष्क, दंत विन्यास, लम्बी हड्डियों और श्रोणियों में आकीरिकी के अनसार ु अल्प अन्तर होता है। सामान्यतः महिला कंकाल के अवयवों उसी तरह के परुुषों की की तलना ु में कुछ मात्रा में छोटे और कम मजबतू होते हैं। अन्य प्राणियों से भिन्न, मानव परुुष का लिगं स्तंभास्थि रहित होता है।[2] सन्दर्भ श्रेणी:कंकाल तंत्र 

**Question**: जन्म के समय शिशुके शरीर में कितनी हड्डियाँ होती है? 

**Answer**: 300

### Model

[XLM-RoBERTa (large-sized model)](https://arxiv.org/pdf/1911.02116.pdf)

### Datasets

1. [Chaii-1](https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/overview) given in the competition 
2. [MLQA](https://www.kaggle.com/rhtsingh/external-data-mlqa-xquad-preprocessing) (MultiLingual Question Answering) released by [Facebook Research](https://github.com/facebookresearch/MLQA)
3. [Google translated SQuAD2.0 to Hindi and Tamil](https://www.kaggle.com/tkm2261/google-translated-squad20-to-hindi-and-tamil)

### Authors

- Shubham Mittal
- Aditi Khandelwal

[NLP Course Assignment](https://www.cse.iitd.ac.in/~mausam/courses/col772/autumn2021/A4/A4.pdf) by [Prof. Mausam](https://www.cse.iitd.ac.in/~mausam/)
