# Proliferation of disinformation
![](https://scx2.b-cdn.net/gfx/news/hires/2018/information.jpg)
## The Wrong information spreads way faster than the right one. No thanks to Recommendation systems.

The filter bubble–the idea that online recommendation engines learn what we like and thus keep us only reading things we agree with–has evolved. Algorithms, network effects, and zero-cost publishing are enabling crackpot theories to go viral, and—unchecked—these ideas are impacting the decisions of policy makers and shaping public opinion, whether they are verified or not.

### Social Media Facts

Once People join a single conspiracy-minded [Facebook] group , they are algorithmically routed to a plethora of others so basically rather than pulling a user out of the rabit hole , the recommendation engine pushes them further in.


Facebook’s news feed and personalized search delivers results that are tailored just to us because a social network’s business is to keep us interested and happy. Feeling good drives engagement and more time spent on a site, and that keeps a user targetable with advertisements for longer. Pariser argues that this nearly invisible editing of the Internet limits what we see—and that it will “ultimately prove to be bad for us and bad for democracy.”

Different biases in Machine learning lifecycle in terms of Data science and not Statistics.

![](https://www.oreilly.com/radar/wp-content/uploads/sites/3/2021/06/Adapted-from-Cornell-University-paper-A-Framework-for-Understanding-Sources-of-Harm-throughout-the-Machine-Learning-Life-Cycle-by-Harini-Suresh-and-John-V.-Guttag-1048x697.png)

Lets look at each briefly-

1. **Historical Bias** - "Historical bias is fundamental, structural issue with first step of Data Generation process as people are biased, processes are biased  and society is biased.

The COMPAS algorithm which is used for sentencing and bail decisions in US shows below results as per https://oreil.ly/1XocO

![image](https://user-images.githubusercontent.com/50423343/125200847-42434080-e28a-11eb-8855-3307970b25b0.png)

2. **Measurement Bias** - It occurs when our model is mistaken because we are measuring wrong things, or measuring it in wrong way, or incorporating that measurement into model inappropriately. for eg. using historical electronic health record(EHR) data, factors predict a stroke the most turn out to be following-

*   Prior Stroke
*   Cardiovascular disease
*   Accidental injury
*   Benign breast lump
*   Colonoscopy
*   Sinusitis

However, only top two are directly related to stroke as we are not measuring the root cause of stroke which can be poor blood oxygen supply to brain intead what we have measured who had symtoms, wnet to doctor, got the test and diagnosed.

3. **Aggregation bias** - When Model does not consider all necessary factors or non-linearities for eg. not taking genders, ethinicity into accounts for diabetes patients.

4. **Representation bias** - Researchesrs noticed that models predicting occupation did not only *reflect* the actual gender imbalance in the underlying population, but amplified it. we can refer to below representation in which training dataset has 14.6% of surgeons as women, yet in the model predictions only 11.6% of true positives were women.

![image](https://user-images.githubusercontent.com/50423343/125201790-217cea00-e28e-11eb-8267-e4f117bd39bf.png)

