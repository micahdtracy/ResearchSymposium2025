# ResearchSymposium2025
## Predicting Anxiety Severity from Social Media Use: Differential Evolution as an Optimizer
## Micah Tracy

### Abstract
Anxiety disorders are the most common mental health disorder worldwide, affecting an estimated 4% of the global population. Various studies have shown that social media use may contribute to heightened anxiety. Using information about individuals’ social media use, we wish to predict the probability that they have moderate to severe anxiety. This project uses differential evolution as an optimizer to train a logistic regression model. Differential evolution is a population-based evolutionary algorithm that works in two phases: initialization and evolution. The initialization phase randomly generates a uniformly distributed population, which undergoes mutation, crossover, and selection within the evolution phase until a stopping criterion is met. We will compare the performance of logistic regression using a traditional optimization method versus differential evolution, in hopes that the latter will lead to comparable, if not better, results. Further work could include the implementation of differential evolution as an optimizer in PyTorch for use in neural networks, since it is not currently supported. By showing social media’s impact on an individual’s probability of having moderate to severe anxiety, we see that it is important for social media users to be mindful of how their use of these social media platforms affects their mental health. In turn, hopefully this prompts them to make changes concerning their time on social media, or to turn to a medical professional for help. 

Data from https://pmc.ncbi.nlm.nih.gov/articles/PMC8627992/.


### References
https://www.who.int/news-room/fact-sheets/detail/anxiety-disorders  
https://www.motleyrice.com/social-media-lawsuits/anxiety  
https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/410326#google_vignette  
https://builtin.com/articles/timing-functions-python  
https://docs.vultr.com/python/third-party/numpy/argsort  
https://matplotlib.org/stable/gallery/lines_bars_and_markers/barchart.html  
https://en.wikipedia.org/wiki/Logistic_regression  
https://mlu-explain.github.io/logistic-regression/  
https://developer.ibm.com/articles/implementing-logistic-regression-from-scratch-in-python/  
https://www.sciencedirect.com/science/article/abs/pii/S095219762030004X  
https://www.linkedin.com/pulse/balancing-act-navigating-precision-vs-recall-ai-emily-ux75c#:~:text=In%20healthcare%2C%20these%20metrics%20serve,diagnosis%20could%20have%20severe%20consequences  
https://pmc.ncbi.nlm.nih.gov/articles/PMC8627992/  
