# Machine Learning with Horse Races
![Horse racing in hong kong final](https://user-images.githubusercontent.com/39209157/81891128-4b912a00-956d-11ea-868b-cbbc2ac6a6f0.png)
## Objective

My goal is to predict the outcome of some of the biggest horse races in the world. The Hong Kong Jockey Club is world renowned and a big part of the culture in Hong Kong. The HKJC has two racetracks, Sha Tin and Happy Valley. They attract tons of citizens, tourists, and about 17.86 million USD per race, more than any other track in the world.

## Data
![Annotation 2020-05-13 230828](https://user-images.githubusercontent.com/39209157/81891680-b131e600-956e-11ea-8007-02441b98f2fc.png)

All of the current race horses information and race history is available on the HKJC website. The data includes the jockey, trainer, finish time, horse weight two days before the race (Declar. Horse Wt.), jockey wieght (Act Wt.), win odds, placement and more.

## Insights

Feature engineering is where I spent most of my time on the project. Some of the features I found to be important where 
the weights (horse and jockey), how the horse compares to its race class, Speed (obviously), and the Horse and Jockeys history together.

![f_imp](https://user-images.githubusercontent.com/39209157/81892166-028ea500-9570-11ea-8939-43e002db7852.png)

This graph shows these features importance in relation to all of my features.

## Results

When trying to predict the winner.
On roughly 4,000 races, the model was making confident predictions about 6% of the time. Of those predictions the model was correct on 88% of them.

When tring to predict the top two horses.
The model became slightly more confident. Placing bets on about 7% of the races. Of those predictions the model was correct on 99% of them.

## Process

1. All data was collected from hkjc.com
2. The data was then processed into a clean usable format for modeling
3. The majority of the work is done here on Feature Engineering
4. XGBoost was then used to model the data.

## Presentation
You can view further analysis here:
https://www.canva.com/design/DAD1gctonHc/298fNLI1KWdSNntu6-2VfA/view?utm_content=DAD1gctonHc&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton
