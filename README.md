# ML---EDA
ML - Exploratory Data Analysis

- Introduction: Describe the dataset and its variables.

I det här projektet används Kaggles "Data Science Salaries fil som har som categorical och numerical variabler, work_year, experience_level, employment_type,
job_title, salary, salary_currency, salary_in_usd, employee_residence, remote_ratio, company_location, company_size;

Våra target variable är salary_in_usd:

- Data cleaning and preprocessing: Describe the steps you took to clean and preprocess the data:

Vi inspekterar data med shape(), head() och tail(), value_counts() och dtypes();

Kolumner som behövs inte eller är duplicates, använder vi drop() för att dropna dessa;

Describe() vissar oss numerical data och isnull() om det finns nulla värde som behövs fyla i in.

get_dummies ändrar categori variabler till numerical. Jag ändrade experience_level och company_size till numerical eftersom jag tänker att de kan påverka
target (salary_in_usd);

- Exploratory data analysis: Summarize your findings and insights from each of the EDA techniques you applied:

Vi inspekterade numerical data med describe();

Vi ändrade data från categorical till numerical (get_dummies);

Skapade en ny dataframe bara med variabler som var relevanta;

För visualization: scatterplot

För korrelation: Heatmap

För outlier: Boxplot

Dimensional reduction med PCA (Jag har riktig inte förstått hur dimensional reduction fungerar och därför är använt)
