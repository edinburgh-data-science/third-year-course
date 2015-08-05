# You must *really* want to be a data scientist!

In what follows I sketch a curriculum for the third in a series of three optional courses designed to teach data science to undergraduate economics students.

## Applications of Data Science

*Applications of Data Science* would focus on applying the skills from the first two courses to address the type of questions that data scientists would likely face in industry.  Most all industry applications of data science will involve large amounts of complex data.  Such data will typically be stored in SQL databases (and increasingly in NoSQL databases) and the first few weeks of the course will be devoted to teaching the basics of working with databases.

### Course syllabus

#### Week 1: Shock and awe
The first week of the course would be spent impressing students with all of the cool things that they will learn how to do during the course.

#### Relational (i.e., SQL) databases (weeks 2-3)
Three common options for storage are text files, spreadsheets, and databases. Text files are easiest to create, and work well with version control, but then we would have to build search and analysis tools ourselves. Spreadsheets are good for doing simple analyses, but they don’t handle large or complex data sets well. Databases, however, include powerful tools for search and analysis, and can handle large, complex data sets. 

##### Topics covered

1. [Selecting Data](http://swcarpentry.github.io/sql-novice-survey/01-select.html)
2. [Sorting and Removing Duplicates](http://swcarpentry.github.io/sql-novice-survey/02-sort-dup.html)
3. [Filtering](http://swcarpentry.github.io/sql-novice-survey/03-filter.html)
4. [Calculating New Values](http://swcarpentry.github.io/sql-novice-survey/04-calc.html)
5. [Missing Data](http://swcarpentry.github.io/sql-novice-survey/05-null.html)
6. [Aggregation](http://swcarpentry.github.io/sql-novice-survey/06-agg.html)
7. [Combining Data](http://swcarpentry.github.io/sql-novice-survey/07-join.html)
8. [Data Hygiene](http://swcarpentry.github.io/sql-novice-survey/08-hygiene.html)
9. [Creating and Modifying Data](http://swcarpentry.github.io/sql-novice-survey/09-create.html)
10. [Programming with Databases](http://swcarpentry.github.io/sql-novice-survey/10-prog.html)

#### Applications (weeks 4-10)
Remainder of the course will draw example applications from a variety of sources including [*Data Science at the Command Line*](http://datascienceatthecommandline.com/), [Mining the Social Web](http://miningthesocialweb.com/), [Data Science From Scratch](http://joelgrus.com/2015/04/26/data-science-from-scratch-first-principles-with-python/), and [Programming Collective Intelligence](http://shop.oreilly.com/product/9780596529321.do).  While the exact applications covered is still to be decided, each applicationg will focus on applying the 5 steps of the data analysis pipeline...

1. Obtaining data
2. Scrubbing data
3. Exploring data
4. Modeling data
5. iNterpreting data

...by the end of the course students should be prepared to undertake a substantial data analysis project for their final exam.  Ideally the final exam project would serve as a basis for an honours thesis.
