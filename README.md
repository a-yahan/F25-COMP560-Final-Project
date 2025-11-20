# F25-COMP560-Final-Project

_Group Members: Alagammai Lavanya Muthiah, CeCe Liu, Alex Liu, Yahan Yang, Akksharvan Senthilkumar\
Report: [COMP560_Final_Report.pdf](https://github.com/user-attachments/files/23664419/COMP560_Final_Report.pdf)\
Presentation: [COMP560_Final_Presentation](https://docs.google.com/presentation/d/10LfA8x3FPNKw0xxLna7sYwLJAdEWy8eIHkeYCSSTGQs/edit?usp=sharing)\

***

Short-term categorical weather forecasts play an important role in urban operational planning across energy, transportation, construction, and public safety. For many real-world applications, simple daily categories are more practical than full numerical weather prediction outputs. This motivates the use of statistical sequence models that rely only on recent observations and require minimal computational resources.

This paper examines the effectiveness of two such models—a first-order Markov chain and low-complexity Hidden Markov Models (HMMs)—in a small-sample setting where only a single year of data is available. Using New York City’s 2019 daily weather discretized into four categories (Sunny, Cloudy, Rainy, Snow), we estimate both models from the same sequence and evaluate one-day-ahead predictions.

The Markov chain achieves an accuracy of 67\%. HMMs offer only marginal improvement, increasing accuracy by approximately 1–1.5\%. Moreover, expanding the number of hidden states from two to three does not yield additional gains, suggesting limited benefit from added model complexity in this data-scarce regime. Performance is assessed using accuracy metrics and confusion matrices.

Overall, the results indicate that while HMMs can slightly outperform a simple Markov model, the advantage is minimal when only a single year of daily observations is available. These findings underscore the practical challenges of applying more complex sequence models in small-sample forecasting contexts.


