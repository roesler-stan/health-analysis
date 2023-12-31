These notebooks help you gain insights about your health.  They assume you're tracking your symptoms in a Google sheet like [this](https://docs.google.com/spreadsheets/d/1ZZP9MqIlzUlu6MgsLTdogAXfqFi91Oi59sjLXQch_qQ/edit#gid=1102650863).

### Setup

1. Set up a Google Sheets API authentication [here](https://console.cloud.google.com/apis/credentials?pli=1), and copy your JSON key into a directory called "keys".  Paste the key's path in constants.ipynb. Also see [this page](https://console.cloud.google.com/iam-admin/serviceaccounts).

2. Pip install the required packages (requirements.txt) or manually install the packages used in the notebooks.  Sorry I didn't use a virtual environment - requirements.txt lists all packages I installed on my laptop. :/

3. Make a directory called "output" to store images and HTML files.

4. Run 3_parent.ipynb to generate insights!

### Example insights
1. Menstrual cycle charting (based on cervical mucus).
![cycle charting](output/charting_2023-12-31.png)

2. Pelvic pain in relation to menstrual cycle.
![pain by cycle](output/pelvic_pain_inferred_valid_only_True.png)

3. Change in pelvic pain by sleep score.
![change in pain](output/pelvic_pain_vs_7_days_by_sleep_score.png)

### Feedback
Please reach out to katroesler@gmail.com with any feedback or questions.  I'd be happy to run the code for you or update it to meet your needs.
