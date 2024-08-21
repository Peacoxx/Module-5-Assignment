Pymaceuticals - Module 5 Assignment

What's This About?

This project dives into a study by a pharmaceutical company to check out how different drug regimens affect tumor growth in mice. We’re comparing four treatments: Capomulin, Ramicane, Infubinol, and Ceftamin. All the number crunching, plotting, and analysis was done using Python with a little help from Pandas and Matplotlib.
What’s Inside?

pymaceuticals_starter.ipynb: The main Jupyter Notebook where all the magic happens—data analysis, plotting, and more.
data/: This is where the datasets live:
Mouse_metadata.csv
Study_results.csv
README.md
How I Tackled This

Getting the Data Ready:
First off, I combined the mouse metadata with the study results to get everything in one place.
Cleaned up any duplicates to make sure our data was as accurate as possible.
Crunching the Numbers:
I ran the stats on tumor volumes for the four regimens—looking at the mean, median, variance, standard deviation, and SEM.
Visual Goodies:
Bar Plots: To show how many observations we’ve got for each drug regimen.
Pie Charts: For a quick look at the male-to-female mouse ratio.
Box Plots: To spot outliers in tumor volumes.
Line and Scatter Plots: To explore the relationship between mouse weight and tumor size, especially for Capomulin.
Outlier Hunt:
Calculated the IQR to spot any tumor volumes that were way off.
What Did I Find?

Capomulin and Ramicane seem to be the top performers, reducing tumor sizes more effectively than Infubinol and Ceftamin.
Infubinol had some outliers, indicating inconsistent results.
There’s a noticeable link between mouse weight and tumor size in the Capomulin group—the bigger the mouse, the bigger the tumor.
Final Thoughts

This analysis sheds some light on which drug regimens are doing a better job at shrinking tumors. Capomulin and Ramicane really stood out, but the visualizations and stats give a clear picture of how each treatment affected the mice.

Assistance: Assistance via ChatGPT and Xpert Learning. Some structure guidance from SQL for Dummies book.
