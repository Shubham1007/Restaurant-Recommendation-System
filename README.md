# Restaurant-Recommendation-System
The task is to generate a top-n list of restaurants according to the consumer preferences. We can simply say that Recommendation engines are nothing but just an automated form of a person who is sitting at shop counter and predict about customer on the basis of their previous experience or customer choice. If customer ask him for a product then he not only to show that product, but also the related ones which you could buy. They are well trained in cross selling and up selling. So, does our recommendation engines. The ability of these engines to recommend personalized content, based on past behavior is incredible. It brings customer delight and gives them a reason to keep returning to the website.




<br/><br/>

<h1>Two approaches were tested:</h1>


a collaborative filter technique and a contextual approach.<br/><br/>
(i) The collaborative filter technique used only one file i.e., rating_final.csv that comprises the user, item and rating attributes.<br/>
(ii) The contextual approach generated the recommendations using the remaining eight data files.<br/>
<br/>
<h1>Files, instances and attributes</h1><br/>
Number of Files: 9<br/>
<br/><br/>
<h1>Restaurants</h1><br/>
1 chefmozaccepts.csv<br/>
2 chefmozcuisine.csv<br/>
3 chefmozhours4.csv<br/>
4 chefmozparking.csv<br/>
5 geoplaces2.csv<br/>
<br/>
Consumers<br/>
6 usercuisine.csv<br/>
7 userpayment.csv<br/>
8 userprofile.csv<br/>
<br/>
User-Item-Rating<br/>
9 rating_final.csv
<br/>
<br/>
<h1>1) Collaborative Filtering </h1><br/>
Content-based recommendation lacks in detecting inter dependencies or complex behaviors. For example: People might like<br/>
smartphones with Good Display, only if it has retina display and wouldn’t otherwise.<br/>
<br/>
Collaborative Filtering algorithm considers “User Behaviour” for recommending items. They exploit behaviour of other <br/>
users and items in terms of transaction history, ratings, selection and purchase information. Other users behaviour<br/>
and preferences over the items are used to recommend items to the new users. In this case, features of the items are not known.<br/>
We have a similar User – Feature Matrix as content based.<br/>
