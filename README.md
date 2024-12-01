# Terrorism-project
## Semester 4 terrorism group prediction project
### Executive Summary
This project uses algorithms and AI to predict the number of kills from terrorist attacks using the Global Terrorism Database (GTD). Given the use of machine learning systems to reflect biases in training data, the objective was to assess the biases and develop a model that does not perpetuate social inequalities with an accompanying report.
### Research questions
Quantitative: How accurately can a hurdle model, utilizing Global Terrorism Database (GTD) data, predict the number of fatalities that result from terrorist attacks?
Sub-Quantitative: How does attack sophistication impact the number of kills?
### Navigating the repo
- The "DATA" folder has our data cleaning processes
- The "GRAPHS LONEWOLFS AND REGIONS" displays the distribution of kills according to attacker type (eg. lonewolfs etc.) and region.
- Under "MODELS", the `mindless_machine_model.ipynb` is our model without bias reduction measures
- Likewise, the lethality models folder contains the various attempts to make an ML model to predict the lethality of the attacks and assess the lethality of attacks per region.

**For an additional experiment, we were tasked to use an AI model in our predictions. So, we labelled the attacks in our dataset using mistral and ChatCPT APIs on how sophisticated the attacks are. Sophistication in this case being how complex the attack would be, for example, an individual using a knife vs a group of 3 people using military grade explosives.**
