<h1>Ajay Bodla's submission for the Impact Hacks hackathon</h1>

<h3>An attempt to find lifestyle choices and genetic traits that most highly correlate with obesity</h3>

<h4>Goal</h4>
To create a model to accurately predict someone's weight class and find the factors that were most important in making that guess.

<h4>Parameters</h4>

Using a Random Forst classifier I attempted to correlate genetic traits including: 

- Age
- Height
- History of Obesity
- Gender

In addition, I also tried to correlate lifestyle choices such as: 

- Calorie Consumption
- Number of main meals
- Cups of Vegetables Consumed
- Technology use in hours
- Amount of phyiscal activity
- Whether snacks were consumed
- Calorie Tracking 
- Cups of Water Drunk
- Consumption of Alcohol

<h4>Datasets</h4>

Using 2 different datasets one that included lifestlye choices and genetic traits and one that only incldued lifestyle choices I trained two 
different models. One was based on 13 diffrent traits that included genetic and lifestyle traits to find correlation between these factors
and obesity. The second model was based only lifestyle traits with 9 different traits. 

<h4>Results</h4>
Model 1: Lifestlye Traits                    Accuracy: 87.7068%
Model 2: Lifestyle + Genetic Traits.         Accuracy: 73.5224%

Model 1's higher accuracy shows that there is significant correlation between a person's weight and their genes. However Model 2 proves that
there is also a somewhat weaker but still strong correlation between one's lifestlye and their weight. 

The most significant factors for Model 1 were (in order):
- Age (∼15%)
- Vegetables (∼14%)
- Height (∼13%)
- Main Meals (∼8%)

The most significant factors for Model 2 were (in order):
- Vegetables (∼20%)
- Water (∼16%)
- Technology (∼16%)
- Physical Activity (∼15%)

Using this data we can derive that one of the most important lifestyle changes that one could make is eating more vegetables.




**DISCLAIMER: THIS IS JUST AN INTERPRETATION OF THE DATA NOT A SCIENTFIC STATEMENT**
