# SDSS_2020
Symposium on Data Science and Statistics 2020 Poster Presentation

PDF of poster created and presented at the Symposium on Data Science and Statistics 2020. 

https://ww2.amstat.org/meetings/sdss/2020/onlineprogram/AbstractDetails.cfm?AbstractID=308479



## Data Science at the Mayo Clinic: Implementation of the Discovery, Translation, and Application (DTA) Framework in Outpatient Palliative Care Practice


### Abstract:  
The Mayo Clinic Data Science team develops and implements predictive algorithms in clinical practice following the DTA (Discovery, Translation, Application) framework. This framework is initiated by clinical need (Discovery), followed by collaborative model development (Translation), and the implementation of an algorithm in clinical practice (Application). One project called the outpatient Control Tower is successfully passing through the DTA framework. The Control Tower is a central analytics center for outpatient monitoring. Control Tower Operators (CTO) are presented alerts about high risk patients with unmet needs from a predictive algorithm. The CTO then forwards appropriate candidate patients to care providers. This limits alarm fatigue and increases the propensity to take action by integrating the CTO into a definitive action plan. The project began with palliative care practice addressing the need for an algorithm that identifies high risk patients in real time. With consultation from clinical experts, we gathered and processed disparate, complex, and clinically relevant EHR data. We then engineered features to construct a training dataset for the algorithm. The team fit a Gradient Boosting Machine (GBM) model for time to event (i.e., palliative care consult) with 10-fold cross validation. We then developed a standalone platform via a cron job to run the algorithm in a production setting. The cron job extracts fresh data, runs the GBM, and generates a weekly patient report that is displayed in an RShiny user interface. The CTO then determines if each patient in the report is an appropriate candidate for a palliative care consultation. We hope to evaluate the efficacy of the algorithm in practice with a clinical trial in the near future. Most of the focus in our field has been on the algorithm development, but all steps of the DTA framework are critical to extract practical benefit out of modern predictive modeling approaches in healthcare.
