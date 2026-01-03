# TamJai-Samgor-Loyalty-Program-Evaluation

I was responsible for "***Current Problems of the Loyalty Program***". The following part "***Improvements Could Be Done***" was based on my part and proposed possible solutions to resolve the existing problems. [->PDF](TamjaiLPSlides.pdf)

## 1. Data Colletion & Pre-processing
[-> Web Scraping Notebook](codes/TamjaiWebScraping.ipynb)

![](images/GooglePlay.png)
Data was scrapped on Google Play and "Newest" comments were selected to make sure those comments were representing the latest status of the loyalty program. <br><br> <!--need 2 breaklines-->

![](images/Comments.png)
Based on the comments, the existing problems were classified into **7 different categories**. <br><br>

## 2. Visualizations on Findings
[-> Visualizations Notebook](codes/TamjaiLP.ipynb)
### 7 Problem Categories
> 1. **Forced Joining** (Forcing customers to join the loyalty program)
> 2. **Functionality Issues** (Dine-in ordering system is loading very slowly, but customers are able to place their order eventually)
> 3. **App / System Issues** (Some key features are not performing their function normally, and cannot place the order)
> 4. **Payment Issues**
> 5. **Login / Account Issues**
> 6. **Privacy Issues** (Requiring too much personal information to sign up an account)
> 7. **Others** (Expressing their anger without mentioning the specific problem)
>> **User Experience** was removed since all the problems will lead to unpleasent experience.

![](images/ProblemCategories.png)

<br><br>
![](images/Ratings.png)  
There were 1021 ratings on the App, but 681 of them gave it a low rating (1 or 2 stars). -> **~67%**  
Which means customers generally do not satisfied with it. 
<br>
## 3. Proposed Solutions 
### Remove “Forced Joining” Barrier
- Let customers choose whether joining the loyalty program or not
- Provide incentives or motivations for customers to join the program

### Fix the Functional and System Reliability
- Stabilize QR ordering & server response
- Regular app maintenance
- Develop in‑app bug‑report button (Reward users with points for feedback)

### Build Privacy Trust 
- Cancel unrelated question (too deep and private)
- Change wordings (e.g. Home address -> Which store(s) you visit the most?) 
- Be clear why data is collected and how it’s used

### Provide Value to Customers
- Redesign the reward program or structure (e.g. [The "Spicy Passport" or "18 Districts in 180 Days" Challenge](TamjaiLPSlides.pdf))
