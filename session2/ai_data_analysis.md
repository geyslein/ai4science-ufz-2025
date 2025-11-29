# Data Analysis with Generative AI

There are numerous providers that allow us to process data online with generative AI. Their endeavor to collect data and associated scientific research questions plays a key role in this. To use such online services in compliance with data protection regulations, we must strictly separate data. Personal and confidential data, such as research proposal texts, must not be processed online.

To still be able to generate program code that analyzes data, for example, we can either keep the data completely secret from an AI system and iteratively modify the code and sometimes manually curate it until the code performs the data analysis as desired. Alternatively, we can generate data that is similar to our actual data yet fictitious, so that we comply with data protection guidelines.

As an example, the automated analysis of participants in a lecture shall serve. We want to study the distribution of the number of academic semesters and know from which study programs the students participate in the lecture.

## Data Generation

Systems like [ChatGPT](https://chat.openai.com/), [Claude](https://claude.ai/) and [Julius AI](https://julius.ai/) have the ability to generate tabular data as well. For example, you can upload an [empty CSV file](fmi11_student_list.csv). If you do this with your own file, please check once more that it really contains no data from real persons.

You can then instruct the AI system with this prompt:

```
Fill the given CSV file with realistic-looking, random data. 
The students are typically from the study programs 
"BSc Computer Science" and "BSc Digital Humanities". 
They are at least in the 2nd academic semester, on average in the 6th semester and 
there are a few outliers in the 10th semester.
```

After a moment, you can download the filled CSV file again.

## Data Analysis

You can now upload this table to any online platforms for data analysis with or without AI without problems.

In the simplest case, you simply continue working in ChatGPT and ask our research question outlined above:

```
I would like to see the distribution of the academic semester as a histogram and 
a pie chart of the study program the students are from.
```

You could then copy the program code for this analysis and execute it again, for example, on the [Jupyter Hub Platform of the Compute Center in Jülich](https://jupyter.jsc.fz-juelich.de/) (alternatively [Jupyter@NFDI](https://hub.nfdi-jupyter.de/)). Basic programming knowledge is helpful for this to make small code adjustments if necessary. 

## Your Own Data Analysis

Follow the workflow above to analyze publicly accessible data from the internet and analyze it:

* [Leipzig's residents by age (annual figures)](https://opendata.leipzig.de/dataset/einwohner-nach-alter-jahreszahlen): Plot a distribution of age in Leipzig's population. How has the distribution changed between 2002 and 2022?
* [7-day incidence of COVID-19 cases in Germany (Source: Robert Koch Institute)](https://zenodo.org/records/15393229): Plot the distribution of the 7-day incidence from a COVID statistics table (CSV). Which federal state has the highest incidence in January 2021?
* Download the statistics of enrollment numbers in Leipzig and plot how these have changed over the years. Use an AI system to find these numbers online.
