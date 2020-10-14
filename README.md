# AliyunTIANCHI
open-sourced procedures of joining ML competions on Aliyun TIANCHI

1. The first project is about the financial risk control -- Loans Default Forecast
I started this project on 15/09/2020, and I hope to learn something useful.

15/09/2020
Stopped at missing values.

16/09/2020
Finished reading the first 2 official guiding chapters.
Still need to review and try to memorize and use more.

18/09/2020
Finished feature engineering (chap 3).
Have to review all the knowledge after finishing reading this project guide.

20/09/2020
Forgot to read carefully, so the 4th chap needs to conduct feature engineering according to baseline.
Must finish this chap tomorrow.
And I think this procedure needs to be ignored, because there is no 'sample', and I can just choose a certain/easy way to complete feature engineering, because my purpose in this chap is to realize model constrcution and parameter adjustment after all.

22/09/2020
Yesterday, I finished chap4 and I completed the whole procedure today, but I didn't output the result file because I still want to conduct Xgboost which has cost so much time and forced me to give it up tonight. Maybe I can try to output tomorrow and review this project.
So there are still some problems remained. First, how to adjust parameters in the model? Second, what's the logic and intuition of the model? Third, need to learn the details in feature engineering.

25/09/2020
Finally, I submitted my first outcome based on the tutorial using lgb model. Maybe the result is not good enough, but I believe I will make progress in the future. The most important point is the tutorial has formed a function and the function returns the final result. So I counld't save the model using pickle or joblib (both are from sklearn library, see https://www.cnblogs.com/Allen-rg/p/9548539.html for more details). I think I also need to pay attention to this problem in the future. Maybe I should try to overwrite the function and make the function return the model as well.
The score is not high (0.7256). The highest score so far is 0.7463, and the no.100 is 0.7296)(0:16 26/09/2020). And I think I still need to use more models, try different models like xgb and so on. I also need to try to adjust the parameters. Btw, I think maybe I should not use cross-validation during parameters adjustment to improve the efficiency and the speed.
That's all for today. Still need to learn to use more models and adjust the parameters. And most importantly, review all that I've learnt.

30092020
Today, I started to run the model on kaggle notebook, which makes the whole process much faster.
And I finally find out how to compute the average of columns with nan, just remember not to reduce memory before filling nans.
Tomorrow I need to do more feature engineering to get a better result with higher accuracy!

10/10/2020
What I need to do is to consider if every feature is valid, and try to remove some useless ones like id, etc.

15/10/2020
I think what I want to do essentially is to select features. There are several different methods of selection, so the first step is think whether the features may cause impact on the result, the second thing is to calculate the relationship to verify the hypothesis in the first step.
