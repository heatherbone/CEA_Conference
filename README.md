## Materials for CEA Presentation - Using Live Coding to Teach Econometrics with RISE

This github repository contains the presentation files as well as supplementary resources for my presentation at the 2026 Canadian Economics Association Conference. A description of the contents of this depository are below:

### 1. CEA_Presentation

This contains files related to my presentation at the CEA 2026 conference.

**It contains:**
- A copy of the presentation (rendered as a PDF): (Live Coding With Rise.pdf)
- The associated Jupyter notebook: (Live Coding With Rise.ipynb)
- Images embedded in the notebook file

### 2. MGT201_Lecture

This folder contains a sample lecture from the introductory level course that I taught (MGT201: Coding for Business). In this course, live coding was used more extensively as students are assumed to have no previous experience with programming. 

**It contains:**
- A student file (with blanks left for live coded portions): Lec_2_Lists_and_Conditionals_STUDENT.ipynb
- A solutions file (containing the portions that are coded live): Lec_2_Lists_and_Conditionals_SOLUTIONS.ipynb
- A .css file used to control formatting in the lecture environment: (rise.css) 

### 3. MGT301_Lecture

This folder contains a sample lecture from an intermediate course I taught (MGT301: Coding and Data Mining for Business Analytics), an upper-level course where students have already been introduced to programming fundamentals. At this level, students are not expected to code everything from memory; even experienced programmers look things up. However, they should have enough fluency with foundational structures, such as loops, conditionals, and functions, that these basics do not interrupt the larger analytical task.

For that reason, this lecture includes fewer blanks than the MGT201: Coding for Business example. In MGT201, more blanks help students practice the core programming patterns they will need repeatedly. In MGT301, live coding can focus more on adapting code to empirical questions, interpreting output, and making analytical decisions.

**It contains:**
- A student file (with blanks left for live coded portions): Lecture_8_9_Introduction_to_Machine_Learning_and_Classification_SOLUTIONS.ipynb
- A solutions file (containing the portions that are coded live): Lecture_8_9_Introduction_to_Machine_Learning_and_Classification_STUDENT.ipynb
- A .css file used to control formatting in the lecture environment: (rise.css)
- A .csv file containing the data used in the lecture case study: (churn_data_cleaned.csv)

### 4. Links To Additional Resources

1. [Anaconda Navigator](https://www.anaconda.com/products/navigator)

   Anaconda Navigator is a useful local setup option if you are not using a cloud-based coding environment. It gives students a point-and-click way to launch Jupyter Notebook on their own computers, which can be easier for beginners than starting from the command line. Instructors could use the first lecture or lab to walk students through installing Anaconda, opening Navigator, and launching a basic notebook.

   For students, this setup mainly requires installing Anaconda and using it to open Jupyter Notebook. Additional tools, such as RISE, are primarily needed by the instructor for presenting notebooks as slides.
   
2. [RISE Documentation](https://rise.readthedocs.io/en/latest/)

   The RISE documentation provides installation instructions, basic usage guidance, and options for customizing how notebooks appear in slideshow mode. It is a useful reference for instructors who want to present Jupyter notebooks as slides and adjust the layout, slide types, or presentation settings.

3. [Stata Python API Documentation](https://www.stata.com/python/api/)

   The Stata Python API documentation explains how to call Stata from Python, including the use of magic commands in Jupyter notebooks. This is useful for a Python-centered notebook workflow that incorporates Stata code. Students must have a local install of Stata to use this option. 

4. [`nbstata` Documentation](https://hugetim.github.io/nbstata/)

   The `nbstata` documentation explains how to install and use a Stata-centered Jupyter notebook workflow. Unlike the Stata Python API, `nbstata` allows users to write and run Stata code directly in notebook cells, making it useful when the goal is to teach Stata rather than Python.

5. [Ten quick tips for teaching with participatory live coding](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008090)

   This article provides practical guidance for using live coding as a teaching strategy, including how to structure sessions, pace instruction, involve students, and make the coding process visible. It is a useful reference for instructors who want to use live coding intentionally rather than simply writing code in front of students.
