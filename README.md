# Anomaly-Detection-Notes

An outlier or anomaly is a data point that is noticeably different from the rest. They represent errors in measurement, bad data collection, or simply show variables not considered when collecting the data.

Anomaly detection is a statistical technique that identifies rare events, observations, or items that deviate from the majority of data and don't conform to a defined notion of normal behavior. 

Anomaly detection made easy🔥
based on personal experience *

Outliers / Anomaly အကြောင်း


ကျွန်တော်တို့က 
model မတည်ဆောက်ခင်
data တွေက
ဘယ်လိုပုံစံ ပြန့်နေလဲဆိုတဲ့
distribution နဲ့
အချင်းချင်း ဘယ်လို 
ဆက်သွယ်မှုရှိလဲ ဆိုတဲ့
Ontology ဆိုတာရှိပါတယ်


_______ Outlier (or) Anomaly ________


Anomaly လိူ့လဲခေါ်တဲ့
Outlier ဆိုတာကတော့
ပုံမှန် data distributionနဲ့မတူဘဲ
 သီးခြားကွဲထွက်နေတဲ့
data point တွေပေါ့

 ပုံမှန်ဒေတာတွေမှာ 
model က result 
ခန့်မှန်းဖို့ လွယ်ပေမယ့် 
Outlier တွေမှာဆိုရင်တော့
 model က result ကို
ခန့်မှန်းဖို့ကခတ်ပါတယ် ။ 


false prediction 
တလွဲတွေ
ထုတ်မယ်ပေါ့
false alarm အပြင်
တစ်ခါတလေ 
anomaly ကိုယ်တိုင်က
သီးခြား feature အနေနဲ့
စစ်ထူတ်ရတာရှိပါတယ်


ဥပမာ 
FinTech က Fraud နဲ့ 
Cyber security လို
နေရာတွေမှာပါ


_____
ကျွန်တော်တို့အလုပ်မှာဆို
အပိုင်း step တွေထဲက
data pre-processing အဆင့်မှာ
EDA
Explornary Data Analysis ဆိုတာ
လုပ်ရပါတယ်
Dataset ထဲမှာ ရှိတဲ့
outlier တင်မကဘဲ
အခြေအနေနဲ့
ပြသနာအကုန်လုံး
ဖော်ထုတ်ပေးပြီး
လိုတာတွေ ပြင်
clean data ပြောင်းပြီးမှ
Model training လုပ်ရတာပါ

____________

Personally,
တော်တော်များများက

anomaly detection ဆို
အရမ်းခက်ခဲတယ်ဆိုတဲ့ပုံစံတွေနဲ့
ပြောကြတာတွေ့ရ ရင်

ကျွန်တော် တော်တော်လေး
စိတ် ကသိကအောက်ဖြစ်ရပါတယ်

Theory အရ
ပိုခက်တာတွေကျ
လုပ်နေကြပြီး

ဒါကိုကျမှ Big Deal လို
ပြောနေတာဆိုရင်ပေါ့

{

ခက်တယ် ပြောကြတာက
tutorial ရှားလို့ပါ

သူ့ထက်ပိုခက်တာတွေက
tutorial ပေါကြတော့
ကူးကြိတ်ပြီးမှ
ခက်မှန်း မသိကြဘဲ

ဒါကို tutorial ရှားလို့
ခက်ပါတယ်
ပြောကြတာများတယ်

}

အဲဒီတော့ outlier တွေကို
ခန့်မှန်းရတာလွယ်လားခတ်လား?

ကျနော်သိလာတာတစ်ခုကတော့

အဲဒီ Outlier တွေကို
ခန့်မှန်းဖို့ဆိုတာက
dataset မှာမူတည်ပြီးတော့

simple ဖြစ်ပြီး
လွယ်တာလည်းရှိသလို

အရမ်းခတ်တာလည်းရှိတယ်

အဖြေကတော့
တစ်သက်မတ်ထဲ မဟုတ်ဘူး
it depends on dataset လို့ပဲ ပြောရမယ်

_________________ HARD ____________________

ယေဘူယျ ပြောရမယ်ဆို
Outlier ရှာရ တာ ပိုခက်တဲ့
Data တွေက

- Financial Fraud Detection:

transaction တွေနဲ့ဆိုင်တဲ့
dataset မှာ
fraud ဖြစ်တာတွေက
ပုံမှန် behavior နဲ့မတူတဲ့
outlier (anomaly)တွေပါ

ဒါပေမဲ့ သူ့ကို ရှုပ်ထွေးစေတာက
real world data မှာ
data distribution pattern
ပြောင်းလဲတာ မြန်လို့ပါ

••••••••••••••••••••••••••••••••••••••••••

- ရောဂါ ခန့်မှန်းရတဲ့ Diagnosis အလုပ်တွေ

Medical ပိုင်းမှာ
ဖြစ်တောင့်ဖြစ်ခဲ
ရှားပါးရောဂါ

အမျိုးအစားတွေက

outlier အနေနဲ့
ပါလာတတ်ပါတယ်

ရောဂါလက္ခဏာရဲ့
pattern တွေလေ့လာပြီး
ontology
relationship တည်ဆောက်ပြီး
ရောဂါ ခန့်မှန်းတဲ့
Model တွေအတွက်ကတော့

ဘယ်လိုမှ predict မလုပ်နိင်ဘဲ
Result အမှားတွေ ပြမိတတ်ပါတယ်

••••••••••••••••••••••••••••••••••••••••••

- Cybersecurity ပိုင်း

Network နဲ့ System log တွေကို
read လုပ်ပြီး prediction လုပ်ရလေ့ရှိတယ်

Attack နည်းပညာ
အသစ်တွေက
pattern အသစ်တွေနဲ့လာလိူ့

outlier အနေနဲ့ ပေါ်လာတတ်ပါတယ်

ပိုဆိုးတာက
လူတွေတောင် ဘယ်တုန်းကမှ
မသိခဲ့တဲ့ New Threat ဆို

Model ကလည်း
pattern ကို လေ့လာဖို့
data မလောက်လို့
အလွယ်တကူ
မခွဲနိင်ပါဘူး

_________________ EASY____________________

Outlier ရှာရတာ ပိုလွယ်လေ့ရှိတဲ့
အပိုင်းတွေကတော့

- စက်မှု လုပ်ငန်းတွေက Quality Controlပိုင်း

အနာအဆာ defect တွေက
ရှားပါးလေ့ရှိတဲ့အပြင်

manufacturing မှာ
sensor data နဲ့ တွဲ သုံး
ontology လုပ်ရင်
အလွယ်တကူ
outlier အနေနဲ့
ပေါ်လာတတ်ပါတယ်

••••••••••••••••••••••••••••••••••••••••••

- Energy ပိုင်းက Anomalies ရှာတာ

လျပ်စစ်လို ဓာတ်အားသုံးစွဲမှုက
ယျေဘူယျဆို
normal distribution နဲ့ပဲ
ရုတ်တရုတ် ထိုးကျတာ
ဆောင့်တတ်သွားတာက
တစ်ခုခု ချို့ယွင်းတဲ့
Outlier အနေနဲ့
ခွဲထုတ်လို့ရပါတယ်

••••••••••••••••••••••••••••••••••••••••••

Essay Scoring Systems တွေ

သက်ဆိုင်ရာ tect data မှာ
train ထားတဲ့
model အတွက်က

မသက်ဆိုင်တဲ့ Topic မှာ
ရေးထားတဲ့ စာတွေက
Outlier ဖြစ်နေမှာပါ

အလွယ်တကူ
ပေါ်လာတတ်ပါတယ်

____________ Influencing FACTORS __________

ဘာတွေက
လွယ်တာ ခက်တာကို
ဆုံးဖြတ်ပေးတာလဲ?

ပထမတစ်ခုကတော့
EDA လုပ်ရုံနဲ့ဖြစ်ဖြစ်

outluer နမူနာ ရှာရလွယ်လား
ဆိုတာပါ

dataset မှာ
မကြာခဏပေါ်လား

နမူနာရှာထည့်လို့ရလားပေါ့

•••••••••••••••••••••

နောက်တစ်ခုကတော့
သက်ဆိုင်ရာ feature distribution နဲ့
outlier ပေါ်တတ်တဲ့ ပုံစံနဲ့
ဆင်တူတာနည်းလေ
ရှာရလွယ်လေပါ

•••••••••••••••••••••

နောက်ဆုံးတစ်ခုကတော့
ကိုယ်က
complex model သုံးထားရင်
non linear data တွေပါ
ခန့်မှန်းနိင်တာက အားသာချက်ပါ

အဲ့အားသာချက်ရဲ့
ပြသနာကတော့
Outlier တွေကို
false prediction ထုတ်ပြီး
overfit သွားဖြစ်နေတာပါ


________________________________________

အရိုးရှင်းဆုံးကနေ စပြောမယ်

one class classification ဆိုတာလေးနဲ့
မိတ်ဆက်ပေးပါရစေ
ပုံမှန် classification တွေမှာဆိုရင်
တော့ class နှစ်ခု or
နစ်ခုထက်ပိုတာကို
classification ခွဲကြတယ် ။

one class classification မှာဆိုရင်တော့
class တခုတည်းကိုပဲခွဲခြားဖို့လုပ်တယ် ။

Training လုပ်တဲ့အချိန်မှာ
class တစ်မျိုးထဲအတွက်

ရည်စူးတဲ့တဲ့ data ကို
Train လုပ်တယ် ။

ပြောရမယ်ဆိုရင် တော့
Class တခုတည်းမှာ
dustribution နဲ့ relationship
ဘာပါလဲဆိုတာသိရင်

သူနဲ့မသက်ဆိုင်တဲ့အရာတွေ
outlier (anomaly) ကိုလည်း
ခွဲထုတ်ပြီးသားဖြစ်ပါတယ်။

ဥပမာပေးရမယ်ဆိုရင် တော့
စက်ရုံတရုံမှာ
machine တခုဟာ
99.9 ရာခိုင်နှုန်းလောက် မှာ

အမြဲကောင်းကောင်းမွန်
run တယ် ထားပါတော့

အဲဒီလိုအခြေအနေမှာဆိုရင် တော့
One class classification နဲ့
အလုပ်လုပ်နေတဲ့စက်မှာ
ရလာတဲ့အချက်လက်တွေနဲ့ပဲ
training လုပ်မယ် ။

တစ်ခုခုလွဲမှားပါရင်
မတူညီတဲ့ဒေတာ
အချက်အလက်တွေရလာမယ် ။

အချိန်ကျရင် တော့ outlier ပေါ့ ။

ဒီနည်းကတော့ အရိုးရှင်းဆုံးနည်းဖြစ်လိမ့်မယ် ။

train ဖို့ data မှာ

Outlier တွေ့ချင်ရင် တော့
break down ဖြစ်အောင်
damage ပေးလိုက်လို့လည်းရတယ်
( joking but တကယ်ရတယ်)

one-class classification ကို
algorithms အမျိုးမျိုးနဲ့ သုံးလို့ရတယ်

SVM, 
isolation forest, 
autoencoder တွေလိုပေါ့


______________________________


Outlier ရှာတဲ့ နည်းကတော့ အစုံရှိတယ်

library တွေ အောက်ဆုံးမှာ
ရေးထားမယ်

_______ Statistical Method မှာဆို ________

Z-Score လို့ခေါ်တဲ့
mean ကနေ ယှဥ်ရင်
standard deviation တွေကို
လိုက်ယှဥ်ပြီး
ရှာတဲ့နည်း

•••••••••••

IQR (Interquartile Range) ဆိုတဲ့
forst to third Quartiles လောက်ကို
ramge ချပြီး ယှဥ်တဲ့နည်း

________ Machine Learning မှာဆို __________

Isolation Forest:

forest ဆိုတဲ့အတိုင်း
ensemble learning ပါ
decision tree တွေကို
bootstrap aggregation
(Bagging) လုပ်ပြီး
avarage path length တွေကို
ယှဥ်တာပါ

•••••••••••

One-Class SVM
(Support Vector Machine):

ခုနက ပုံမှာ ပြောသွားတဲ့
နည်းပါ class တစ်ခုပဲ
Trainပြီး မဆိုင်တာဆို
အလွယ်တကူ
outlier သတ်မှတ်တာပါ

•••••••••••

Autoencoders တွေက

neural networks တွေကိုသုံးတယ်
data တစ်ခုစီကို
သူ့ distribution အလိုက်
encode ပြီး
decode ပြန်လုပ်ရင်
အရင်အတိုင်းပြန်ရလား
error ဖြစ်သွားပြီး
မရ ရင် Outlier ဆိုတဲ့နည်း

•••••••••••

K-Means လိုမျိုး Clustering နည်းတွေ
membership လျော့နေတဲ့
data point တွေက Outlier တွေပေါ့

•••••••••••

Density-Based Spatial Clustering of
Applications with Noise(DBSCAN)

အဲ့တာက လည်း
ဘယ် data အစုအဝေးမှာမှ
မပါတဲ့ Outlier ရှာဖို့ သံုးတဲ့နည်း

______ Time Series နည်းစနစ်တွေ ________

ARIMA
(AutoRegressive Integrated Moving Average)

သူကတော့ Time series ပိုင်းမှာပဲ
အဓိက သုံးတယ်
forecast error ကိုကြည့်ပြီး
စစ်ထုတ်တာ

•••••••••••

Prophet:
Facebook (META)ကနေ ထူတ်ထားတဲ့နည်းပါ

ဒီမှာ အသေးစိတ်
tab တွေပြောင်း
ဖတ်လို့ရတယ်👇

https://facebook.github.io/prophet/docs/outliers.html

_______တခြား လွယ်တဲ့ Library တွေ _________

𝐏𝐲𝐎𝐃

outlier detection က
unsupervosed ဖြစ်တာများပြီး
instable model ဖြစ်တတ်တယ်

အဲ့တော model အစုံ ပေါင်းပေးတာက
PyOD ပါ

𝐏𝐲𝐎𝐃 က သုံးရတာအရမ်းလွယ်တယ်

documemtation👇
https://pyod.readthedocs.io/en/latest/

density-based methods နဲ့ ensemble
algorithm 30 လောက်သုံးလိူ့ရတယ်
ဥပမာဆို
- Average of scores
- Maximization of scores
- Average of Maximum of scores
- Maximum of Average of scores
- Majority Vote

အဲ့တာတွေကို ပေါင်းသုံးရုံပဲ

••••••••••

သူ့လိုပဲ နောက်ထပ်သုံးရလွယ်တဲ့
library တစ်ခုကတော့

Puncc ပါ

Outlier (anomaly) အပါအဝင်
တခြား
conformal prediction
အမျိုးအစားတွေအတွက်ပါ

အရမ်းခက်ပါတယ်ဆိုတဲ့
case တွေတောင်

ဒါနဲ့ဆို လုပ်လို့ရတယ်

Conformal prediction ရဲ့
threshold တော့
လိုက်ချိန်ရပါတယ်


github👇
https://github.com/deel-ai/puncc

doc👇
https://deel-ai.github.io/puncc/theory_overview.html#
