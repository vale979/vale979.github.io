---
title: "My Journey on Getting Certified As Google Cloud Professional Data Engineer From Zero"
date: 2023-01-22T04:29:44+07:00
draft: false
tags: ["data engineering", "english", "career"]
author: "Valerian"
math: true
---

So, you want to be a Google-certified data engineer?

![Google Professional Data Engineer](https://res.cloudinary.com/ddtggb6fb/image/upload/c_scale,w_725/v1674334178/POST_GCPDE/GCPDE_valer_jkiksy.jpg)

<!--more-->

Over the last several months I have been taking courses and doing hands-on labs to learn Google Cloud Platform for data engineering. I prepared for the exam for about 2-3 months. Then I passed the exam to officially be a Google-certified data engineer. And I started with a zero data engineering experience. Here's my journey.

*Note: I took the exam on January 18, 2023. If you read this far in the future (thanks!), the exam might have had some update. Please always refer to the official material first if you want more information about the exam.*

## What's Here
- [The Start](#The-Start)
- [The Course](#The-Course)
- [Before the Dawn](#Before-the-Dawn)
- [The Exam Day](#The-Exam-Day)
- [FAQs](#FAQs)

## The Start
I joined Merkle Indonesia as data engineer intern at November 2022. During the interview, I honestly said that I have zero experience in data engineering. However, I also said that I had some basic programming skill and interest on learning the required skill (which is proven by my performance in the technical test, kinda). Not so long after joining, I got introduced to Google Cloud Skills Boost -- a learning site by Google to learn various skills about Google Cloud. Naturally after that, I got challenged to complete Google Cloud Professional Data Engineer certificate. 

Well, the first natural thing that I did was to check on the official website to get information about the exam (which can be found [here](https://cloud.google.com/certification/data-engineer)). If you open it, you will see this in the page:

|![GCPDE-recommendation](https://res.cloudinary.com/ddtggb6fb/image/upload/c_scale,w_725/v1674330229/POST_GCPDE/gcp_recommended_hoqprd.png)|
|:--:|
|They recommend you to have 3 years of industry experience for the exam!|

Okay, this looks like a challenge. So, I'll do it :D. To be fair, this is just a recommendation and not hard prerequisites, so it's still technically not an impossible feat.

First things first, since Merkle Indonesia is a Google partner, I can sign up to [Google Partner Certification Kickstart (PCK) program](https://inthecloud.withgoogle.com/pck-page/register.html?linkId=8052588). After waiting for a while, I got an email from Google informing my learning path for this certification. They give me a 10 weeks deadline. If I can clear the program in under 10 weeks, they will give me a voucher to take the exam free of charge. This is very nice, since the exam costs 200 USD.

Before actually started with the courses provided, I took my time to review the [exam guide](https://cloud.google.com/certification/guides/data-engineer) and [official sample questions](https://docs.google.com/forms/d/e/1FAIpQLSfkWEzBCP0wQ09ZuFm7G2_4qtkYbfmk_0getojdnPdCYmq37Q/viewform). I copy-pasted the guide into my Notion notes and started building my notes around the guides. During my first time attempting the sample questions (which is not as hard as the actual exam, by the way), I was completely destroyed. I had no idea what Cloud Spanner is, let alone know what Google best practice recommendation to improve its performance. I know BigQuery, sure, but what is Bigtable? Dunno. So I just guessed many of the questions. Now fortunately they gave us a review. Not only they give us the correct answer, but also the reasoning and relevant documentation link. This is VERY helpful! The documentation is your guiding light when learning for this exam and getting exposed to this from the very beginning is great. Whenever you have doubt during your learning process, you should always [RTFM](https://en.wikipedia.org/wiki/RTFM) and consult the documentation.

## The Course

|![Week 1 - 3](https://res.cloudinary.com/ddtggb6fb/image/upload/v1674333190/POST_GCPDE/week1-3_euvx23.jpg)|
|:--:|
|The course plan from Google|

I started to grind the course. The first week introduced me with eagle-view of various Google Cloud product used for data engineering, like BigQuery ML, Pub/Sub, Vertex AI, etc. There is also a hands-on quest with a challenge to set-up VM clusters and load balancer on Google Compute Engine under a given time pressure. This is my first time learning about what a load balancer is and the difference between L4/L7 load balancer (and what the heck an OSI layer is).

After that I found the second and third week material quite a bit easier. I finished the third week material on my second week. One of the main point that I learnt here is about how to handle streaming data (and why is it different from handling batch data). 

|![Week 4 - 6](https://res.cloudinary.com/ddtggb6fb/image/upload/v1674333921/POST_GCPDE/week4-6_mu5s2w.jpg)|
|:--:|
|The course plan from Google|


The course material for the fourth week is probably the hardest. It introduce you to a lot of hands-on with Dataflow, including continuous integration and continuous deployment of pipelines using Cloud Build and Cloud Composer (a managed Airflow solution). They had two hands-on lab version on each topics: one with Java and one with Python. To complete, you have to clear both version of the labs. Before this, I never wrote a line of Java code. I had to actually learn how to write an Apache Beam pipeline with Java for this course (though with boilerplates already provided).

I still managed to finish them in a week (and so can you!). Then, I took a new year break (our company had a week-long break from Christmas to New Year) and continue to get the needed skill badge. For the `Perform Foundational Data, ML, and AI Tasks in Google Cloud`, I got a bit of problem because one of the lab is under maintenance, so I had to wait several days before getting the skill badge. The `Engineer Data in Google Cloud` introduced me to use Dataprep to clean and prepare data for analysis, write an ETL pipeline with Dataflow (again!), hands-on with BigQuery ML, and use Cloud Composer to do an inter-region data transfer. For the challenge lab, we are required to prepare the data and do a prediction with machine learning with BigQuery ML. I failed several times on this challenge lab because of the time pressure lol. They gave us 1 hour to do data preparation (that took me at least 15-20 minutes already, if I don't make a big mistake), training the model, and do batch prediction. Eventually I cleared it and hence, finished the program. I asked the chat support regarding the voucher, and after several hours, my voucher was granted.


|![The Voucher](https://res.cloudinary.com/ddtggb6fb/image/upload/c_scale,w_709/v1674335256/POST_GCPDE/voucher_email_avwmik.jpg)|
|:---:|

Somehow the email said "Professional Cloud Architect", but alas, I can still use it to register for the Professional Data Engineer exam. So, no problem.

## Before the Dawn

So, I finished the course. I also registered for the on-site exam (I pick about two weeks from the registration date). Now what?

My coworker who had already passed the exam send me [this link](https://www.examtopics.com/exams/google/professional-data-engineer/) for practice exam. Keep in mind that a lot of the answer given in that site is just straight up wrong, so you need to read the discussion and, again, RTFM. I grinded through the problem there and the problem from the official sample questions. I had lost count on how many passes I have done on those two, just to make sure I'm confident enough about the topics. I also read Dan Sullivan's book `Professional Data Engineer Study Guide` and worked through the problems on the book. All this to build up my confidence for the exam day.
![](https://m.media-amazon.com/images/I/51bNoPRhVwL._AC_SY580_.jpg)

Another very helpful resources bank is [this Github repository](https://github.com/sathishvj/awesome-gcp-certifications) by Satish Vj, which gave you a general guide on various GCP certifications. You should definitely take a look at that if you're planning to take GCP certification.

Furthermore, I also watched various video about Hadoop ecosystem and read some article about data engineering implementation (like [this one](https://engineering.atspotify.com/2016/03/spotifys-event-delivery-the-road-to-the-cloud-part-ii/)) to get a better sense of data engineering infrastructure. This has been proven useful for me, since the exam also assume familiarity with open source solution for data engineering and the Google-managed equivalent solution (i.e. Apache Kafka vs Pub/Sub, Hadoop vs Dataproc, Redis vs Memorystore, etc -- hence the recommended industry experience, I think).

## The Exam Day

I took the exam at 11:15 AM, basically the latest time available at that date on that exam center. Mainly because I tried to avoid the traffic, and also because I don't want to be late for the exam. One day before the exam I still had other works to do, so I just focus on that rather than reviewing for the exam. At least it gave me a break from the grind. 

I also prefer to take the exam on-site, so that I don't need to bother with administrative preparation other than printing the registration email and making sure I bring the required ID on the exam day. I took the exam at PT NetTrain Informatika on The East building, Mega Kuningan, Jakarta. I would highly recommend you to take the onsite exam if it's available near you, because it's just much easier to do. You don't need to worry about online proctor, setting up webcam, making sure your room is locked, etc. 

During the exam, I was locked in a small room alone with a computer (already logged-in to secure browser) and a CCTV behind. The exam was 2 hours and I got 50 questions on the exam (Google says that you can get 50-60 questions on the exam). I don't know whether it was intentional or not, but I feel that the first 10 questions on the exam is probably the hardest that my groggy meter starts to increase. This is a tough exam, even more when you have less than 6 months of experience like me. The question is not a simple "What is the managed solution in GCP for Airflow?" but more like a situation/case with several lines of description. You need to actually understand how to choose, for example, storage solution in a given situation (i.e., when they said "high throughput time series data", you should be already thinking about Bigtable). You also need to understand IAM and managing access. You also should know about tradeoffs between options (i.e., when to use HDFS persistent storage instead of GCS on Dataproc Hadoop clusters). There are also questions about machine learning. At this point, you should already know basic concept of machine learning that are described on the exam guide. 

If you had taken this exam in the past, you might seen a long case study questions. I believe this is not the case anymore. Most questions are usually around 2-5 lines long instead of several paragraphs. It took me about 45 minutes to complete first  complete scan. Nearly 50% of the questions was marked for review, because I was not too sure about the answer (or because I don't believe myself to not make a reading mistake lol). I did second scan in about 20 minutes. I feel more confident at that point, but still worried to fail. I YOLO'd and pressed the "Submit Exam" button. I was so nervous that I just skipped the optional feedback survey. I want to see the result ASAP. 

![](https://res.cloudinary.com/ddtggb6fb/image/upload/c_scale,w_916/v1674337865/POST_GCPDE/2457565_wbzwph.jpg)

I jumped from my chair when I saw this. It feels like all heavy weights on my shoulder suddenly disappeared. The exam site staff offers me an opportunity to take that picture, which I gladly take (though to be fair you can also see that from your WebAssesor account too). 

If you're asking, yes, the exam doesn't provide any other feedback than Pass/Fail. They did not tell you about the passing grade nor they tell you about your score (unlike AWS exam). This feels better (if you pass) because all you know is that you had passed, not to worry about score.

They said that it took 7-10 days for the official results to come, but in my case I got my certificate a day later.

![](https://res.cloudinary.com/ddtggb6fb/image/upload/v1674338214/POST_GCPDE/certified_yay_mx8p9p.jpg)

On the perks webstore, you can pick one from various options of swags (jacket, tumbler, mug, bags, etc). I wanted the jacket, but unfortunately they ran out of stock at that time, so I picked the bag instead. You can also opt-in to make the certificate be publicly available, which I did (my certificate is [here](https://www.credential.net/8ce1f76a-523d-4ad6-bb18-f878d53815cc)).

## FAQs

Q: I want to get started. What should I do first?
A: Read the official exam guide and try the sample question. Recognize the gap between the question and your knowledge. Then, start learning.

Q: I'm not currently working/my workplace is not a Google partner. How can I prepare for the exam?
A: There are various other resources on the internet to prepare. You can try courses on Udemy/Coursera (I haven't tried those, but I have heard good things about the Google Coursera course), find free courses on YouTube, read Dan Sullivan's book, etc. Try visitting the official exam pages first and the Github repository I mentioned before.

Q: Should I took the exam online or on-site?
A: People have preferences. Personally I'd prefer to take the exam on-site if I can do it, because I'm too lazy to setup specialized exam browser and to prepare my room for the exam (been there done that for the online TOEFL exam). However, if you prefer taking it online, you do you! Just make sure your device can run the exam, especially if you're not using your own device (i.e. work device).

Q: Is it enough to just use Cloud Skills Boost to prepare?
A: I don't think so. While it's very helpful, there are many things that are covered too briefly the course. There are also various stuffs that you had to read yourself to familiarize with (especially for non-Google solution like HBase, Hive, Redis, Kafka, etc).

Q: Okay, is it enough to just do practice from ExamTopics?
A: No. You will get tired really quickly if it's all you do. You need to actually do some hands-on and read the documentation (while doing the hands-on). I believe this will feel easier for you as well. GCP offers a free 300 USD credits for the first 3 months if you are willing to give them your card info (you can just use virtual card number if you want :D). Utilize this well, as it's very helpful.

Q: How many questions from ExamTopics are actually on the exam?
A: Many people said that most of their exam question came from there. However, this is not the case when I took the exam. Therefore, I need to repeat myself again: you had to actually understand the topics. Don't really on memorizing the answer from there by heart. You will had a hard time on the exam if that's what you did.

Q: Can I take a pen and paper to take notes during the exam?
A: No, and you will not need it.


If you wish to take the exam after reading this, good luck! And for those who passed, welcome to the club!