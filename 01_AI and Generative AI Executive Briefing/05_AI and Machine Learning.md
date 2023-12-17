## AI and Machine Learning
```
Over the past few years, the most common, most successful most practical approach to implement A I has been with machine learning and it's led to some confusion about those terms, machine learning and artificial intelligence are mentioned together. So often it can sound like they mean the same thing they don't. Artificial intelligence is a broad and OK, sometimes vague term that we could basically consider all the various different approaches and methods that people have used to make a computer program, do something smart and machine learning is a set of specific techniques to do that. But machine learning is not the only way to implement A I, machine learning or ML is a type of A I. It's a subset of it. All machine learning is artificial intelligence. But the broader field of artificial intelligence does include other techniques than just machine learning. But if you want to understand what machine learning does, let's first consider a normal computer program that doesn't use ML or any kind of A I you see in regular conventional computer programming, which includes most applications on your desktop or your laptop or your phone. A software developer tries to solve a problem by providing a bunch of rules and very specific instructions. If this number is greater than that number, then add these two things together. If this date is less than that other date, generate this error message. If the position of the asteroid on the screen is now the same as the position of the spaceship, then play boom, sound effect and display game over now make no mistake. Conventional rule driven computer programming is fantastic when you know what all the rules are and you can cleanly define them. But with machine learning, you don't begin by trying to figure out and define all the rules in advance. Instead you begin by gathering examples to learn from. Here's what I mean, let's say I wanted a computer program that could take a small digitized image and be able to recognize handwritten numbers, handwritten digits in that image. Well, let's make it even simpler. Let's say I want to write a program that could recognize the number three. Now, if I take the conventional programming approach, I might try writing code that would take each image and look at every individual pixel one by one. Figure out TIFF. It's light or dark and then try and envision and describe all the different ways people might ever write a number three in this grid. Sometimes it's straight, sometimes it leans to the left or to the right. Sometimes the top loop is smaller than the bottom loop, etcetera, etcetera. And that would be the conventional programming approach, figure out all the rules go step by step, try and envision every possible eventuality and to be clear, it would be very hard tedious work. And with this particular problem, extremely easy to get it wrong. Now, if we instead take the machine learning approach, we don't begin by trying to figure out all those rules in advance. Instead we begin with actual data, real data. In this case, the data would be thousands of different images of a handwritten number three. And we use that data to build our program. And before doing anything first, we need to clean and prepare the data. Make sure there's nothing extra, nothing missing. If I'm trying to teach a computer to recognize a number three, then I don't want this data to also include images with a two or a four or some other character. I don't want blank images. Now, once the data is cleaned and prepared, we take all of it and feed it into a machine learning algorithm in a process which is called training a model. And after we've trained the model with all that data, we could then expect to be able to take a new piece of input a new image, pass it over to that newly trained model and have it evaluate. Does this new image look like a three or not? We've provided enough examples that it could recognize the characteristics of that thing. And this is one of the tasks, machine learning is very, very good at classification and it doesn't just apply to images. Classification is used with all kinds of data because it's a very common problem in computing to get some new data and be able to ask, what is this? When we've got incoming emails, could we quickly classify them as these ones look like spam and these ones look legitimate machine learning's ability to categorize or classify helps in all sorts of situations. It's used for diagnosing medical conditions, fraud detection, evaluating social media comments. But classification isn't the only area where machine learning can help. There's a few other kinds of problems, it's very good at including regression where we'd still begin with data to analyze and learn from. But instead of using that data to classify or categorize things with regression, we use the data to predict a number of some kind like an amount, a price or a time, some kind of numerical value based on analyzing all the other data that might affect that value. Our classic example of regression is using it to predict a house price based on multiple other factors like square footage, number of bedrooms, location, age of the house, et cetera. But in agriculture, you might use regression to predict crop yields based on multiple other variables like the type of crop, the current weather conditions, the soil quality. If we had prior data about medical procedures and patient characteristics, we could then use regression to make better predictions that for a new patient having this procedure at this age with these comorbidities, what is the likely length of their hospital staying regression and classification are two of the most common applications of machine learning. There are other things we can do with it like clustering and anomaly detection. But that's outside the scope of this course. If you're interested in knowing more about machine learning IDE do have a course just on that, that goes a little deeper. But there is a catch machine learning can only work if you have data to learn from and not just a little bit, you need a lot of data and good quality data. This is why there's been such a focus on data collection and big data in the business world over the last few years. Because if you haven't gathered enough data, you will have nothing for your machine learning algorithms to learn from.
```

## Notes
- Relationship Between AI and Machine Learning:
  - Artificial Intelligence (AI) encompasses various methods to make computer programs perform intelligently, whereas Machine Learning (ML) is a specific technique within AI.
  - ML constitutes a subset of AI, not the entirety of it, and involves specific methods to enable computers to learn from data.

- Conventional Programming vs. Machine Learning:
  - Conventional programming involves providing explicit rules and instructions to solve a problem, whereas ML begins with examples to learn from.

- Machine Learning Approach:
  - Example: Recognizing a handwritten digit (e.g., number three) - In conventional programming, envisioning all possible variations of writing '3' would be challenging and error-prone.
  - ML approach involves using real data (images of '3') to train a model without defining explicit rules in advance.

- Training a Model in Machine Learning:
  - Data cleaning and preparation precede feeding the data into a machine learning algorithm to train a model.
  - Trained models can then evaluate new input (new images) based on the learned characteristics, excelling in classification tasks.

- Machine Learning Applications:
  - Classification: Identifying and categorizing data into groups (e.g., distinguishing spam emails from legitimate ones).
  - Regression: Predicting numerical values based on analyzing various factors (e.g., predicting house prices, crop yields, or hospital stays).

- Importance of Data in Machine Learning:
  - ML heavily relies on having abundant and quality data for training algorithms effectively.
  - The emphasis on data collection and big data in business is due to the necessity of substantial data for successful machine learning implementations.

The text elaborates on the distinction between AI and ML, the approaches of conventional programming versus machine learning, the process of training models, and various applications of machine learning techniques like classification and regression. It emphasizes the significance of having substantial, high-quality data for effective machine learning outcomes.