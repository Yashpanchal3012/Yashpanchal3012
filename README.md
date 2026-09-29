## Yash Panchal

Data analyst, working mostly in Python and SQL.

The project below is one dataset taken properly: 590 sensors, 440 of them worth
testing, and a correction for the fact that running 440 tests hands you about 22
false positives whether or not anything is going on. The sensor with the largest
effect in the data is not in my final recommendation, because it stops working in
the last month.

### Featured project

**[SECOM Manufacturing Analysis](https://github.com/Yashpanchal3012/SECOM-Manufacturing-Analysis)**
Which process sensors are associated with failed semiconductor production runs?

1,567 production runs, 590 anonymised sensors, 104 failures. The pipeline runs end to
end from a checksum-verified download through cleaning, statistics and figures, and
every number in the README is printed by a script you can re-run.

- Cleaning removes 150 sensors that cannot carry information, leaving 440
- Mann-Whitney U per sensor, chosen over a t-test because 298 of 446 sensors are badly
  skewed, with Benjamini-Hochberg and Bonferroni corrections over 440 tests
- 86 sensors come in under raw p<0.05 against 22 expected by chance; 20 survive
  correction and collapse into 16 correlation groups
- The strongest sensor in the dataset is left off the final recommendation because its
  effect disappears in the last month of data, which looks like process drift

`Python` `pandas` `SciPy` `statsmodels` `matplotlib`

### Tools

Python (pandas, NumPy, SciPy, statsmodels, matplotlib), SQL and MySQL, Excel, Tableau,
Jupyter, Git.

### Contact

- LinkedIn: [linkedin.com/in/yashpanchal30](https://www.linkedin.com/in/yashpanchal30/)
- Email: yash.panchal1793@gmail.com
