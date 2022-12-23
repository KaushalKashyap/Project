Parkinson's disease is a progressive central nervous system condition that affects movement and causes tremors and stiffness.

It has 5 stages to it and an estimated seven to 10 million people worldwide have Parkinson’s disease.

This is chronic and still has no cure. It is a neurodegenerative disease that affects the neurons in the brain that contain dopamine.

Details About the Data Set

The dataset was created by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, who recorded the speech signals.



df = pd.read_csv('parkinsons.data')
df

# find the distribution of the dataset

def distplots(col):
    sns.distplot(df[col])
    plt.show()
    
for i in list(df.columns)[1:]:
    distplots(i)
    
    ![image](https://user-images.githubusercontent.com/103347507/209315355-772e30bf-3f60-4498-8fc0-b952b95d42b7.png)
