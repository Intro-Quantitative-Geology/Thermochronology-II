# Thermochronology-II
In part two of the [exercises for the final two weeks of the course](https://github.com/Intro-Quantitative-Geology/Thermochronology-I/blob/master/Laboratory-exercise-6-7-overview.pdf) we will combine the thermochronometer age prediction code used last week with an age dataset from the Bhutan Himalaya to quantify the long-term rates of erosion recorded in the thermochronometer data. These results will be presented in detail in your [final report for the course](https://github.com/Intro-Quantitative-Geology/Thermochronology-I/blob/master/Final-report.md).

## Components
1. [Laboratory exercise 7](https://github.com/Intro-Quantitative-Geology/Lab-exercise-7)

## Plotting predicted ages as horizontal lines
I suggest that you add horizontal lines to your plots of the thermochronometer data to show the predicted ages you calculate. If you have read in the data file with the values for latitude stored in a variable `latitude`, you can plot a predicted age `predicted_age` as a horizontal line as follows:

```python
plt.plot([min(latitude), max(latitude)], [predicted_age, predicted_age], 'k-')
plt.show()
```
This will create a horizontal line from the minimum `latitude` to the maximum `latitude` with a vertical value of `predicted_age`. The "trick" here is to put lists into the `plt.plot()` command instead of variables. Lists are values separated by commas within square brackets (`[ ]`), and here we just give 2 values in each list for the *x* and *y* points that define the ends of the line.

## Resources
- Course lecture materials
  - [Basic concepts of thermochronology](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/11-Basic-concepts-of-thermochronology/11-Basic-concepts-of-thermochronology.pdf)
  - [Low-temperature thermochronology](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/12-Low-temperature-thermochronology/12-Low-temperature-thermochronology.pdf)
  - [Quantifying erosion with thermochronology](https://github.com/Intro-Quantitative-Geology/Lecture-slides/blob/master/13-Quantifying-erosion-with-thermochronology/13-Quantifying-erosion-with-thermochronology.pdf)
- Past exercise materials
  - [Python/NumPy tutorial, part I](https://github.com/Intro-Quantitative-Geology/Python-and-NumPy-I)
  - [Python/NumPy tutorial, part II](https://github.com/Intro-Quantitative-Geology/Python-and-NumPy-II)
  - [Better plotting in Spyder](https://github.com/Intro-Quantitative-Geology/Hillslope-diffusion/blob/master/Fixing-Spyder.md)
  - [Formating text strings in Python](https://github.com/Intro-Quantitative-Geology/Hillslope-diffusion/blob/master/Format-Python-strings.md)
  - [Overview slides for Exercises 6 and 7](https://github.com/Intro-Quantitative-Geology/Thermochronology-I/blob/master/Laboratory-exercise-6-7-overview.pdf)
  - [Description of final project report](https://github.com/Intro-Quantitative-Geology/Thermochronology-I/blob/master/Final-report.md)
- Scientific journal articles
  - [Some final report references](https://moodle.helsinki.fi/course/view.php?id=12453#section-4)
  - [Google scholar](https://scholar.google.fi/)
  - [Web of Science](https://webofknowledge.com) (Only works on campus or via VPN)
- Web pages
  - [Helpful tips for completing the exercises with Classroom for Github](https://github.com/Intro-Quantitative-Geology/Python-and-NumPy-II/blob/master/Lesson/Classroom.md)
  - [Codecademy's Learn to program in Python](https://www.codecademy.com/learn/python)
- Books
  - [Learn Python the Hard Way](http://learnpythonthehardway.org/book/)
  - [Dive into Python 3](http://www.diveinto.org/python3/)
