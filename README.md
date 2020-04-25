# COVID19-Diagnosis

![Kaggle Image COVID](https://www.pyimagesearch.com/wp-content/uploads/2020/03/covid19_keras_header.jpg)
In this tutorial, you will learn how to automatically detect COVID-19 in a hand-created X-ray image dataset using Keras, TensorFlow, and Deep Learning.

Like most people in the world right now, I’m genuinely concerned about COVID-19. I find myself constantly analyzing my personal health and wondering if/when I will contract it.

The more I worry about it, the more it turns into a painful mind game of legitimate symptoms combined with hypochondria:

I woke up this morning feeling a bit achy and run down.
As I pulled myself out of bed, I noticed my nose was running (although it’s now reported that a runny nose is not a symptom of COVID-19).
By the time I made it to the bathroom to grab a tissue, I was coughing as well.
At first, I didn’t think much of it — I have pollen allergies and due to the warm weather on the eastern coast of the United States, spring has come early this year. My allergies were likely just acting up.

But my symptoms didn’t improve throughout the day.

I’m actually sitting here, writing the this tutorial, with a thermometer in my mouth; and glancing down I see that it reads 99.4° Fahrenheit.

My body runs a bit cooler than most, typically in the 97.4°F range. Anything above 99°F is a low-grade fever for me.

Cough and low-grade fever? That could be COVID-19…or it could simply be my allergies.

It’s impossible to know without a test, and that “not knowing” is what makes this situation so scary from a visceral human level.

As humans, there is nothing more terrifying than the unknown.

Despite my anxieties, I try to rationalize them away. I’m in my early 30s, very much in shape, and my immune system is strong. I’ll quarantine myself (just in case), rest up, and pull through just fine — COVID-19 doesn’t scare me from my own personal health perspective (at least that’s what I keep telling myself).

That said, I am worried about my older relatives, including anyone that has pre-existing conditions, or those in a nursing home or hospital. They are vulnerable and it would be truly devastating to see them go due to COVID-19.

Instead of sitting idly by and letting whatever is ailing me keep me down (be it allergies, COVID-19, or my own personal anxieties), I decided to do what I do best — focus on the overall CV/DL community by writing code, running experiments, and educating others on how to use computer vision and deep learning in practical, real-world applications.

That said, I’ll be honest, this is not the most scientific article I’ve ever written. Far from it, in fact. The methods and datasets used would not be worthy of publication. But they serve as a starting point for those who need to feel like they’re doing something to help.

I care about you and I care about this community. I want to do what I can to help — this blog post is my way of mentally handling a tough time, while simultaneously helping others in a similar situation.

I hope you see it as such.

Inside of today’s tutorial, you will learn how to:

Sample an open source dataset of X-ray images for patients who have tested positive for COVID-19
Sample “normal” (i.e., not infected) X-ray images from healthy patients
Train a CNN to automatically detect COVID-19 in X-ray images via the dataset we created
Evaluate the results from an educational perspective
Disclaimer: I’ve hinted at this already but I’ll say it explicitly here. The methods and techniques used in this post are meant for educational purposes only. This is not a scientifically rigorous study, nor will it be published in a journal. This article is for readers who are interested in (1) Computer Vision/Deep Learning and want to learn via practical, hands-on methods and (2) are inspired by current events. I kindly ask that you treat it as such.

To learn how you could detect COVID-19 in X-ray images by using Keras, TensorFlow, and Deep Learning, just keep reading!

More Information : https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/
