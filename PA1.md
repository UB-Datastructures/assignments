# Project 1: Hello World in Scala!

**Due: Friday 09/16/21 Before 11:59 PM**

**Advising via Piazza may not be available after 4:00PM on the day of the deadline. Plan accordingly**

**Submissions Open: Saturday 09/10/22 Before 11:59 PM**

**Total Points = 30**

## Objectives

In this assignment, you will: 
* Read and understand the course AI policy and late policy
* Review (or learn) Scala basics
    * Where to find/how to use Scala docs.
    * How to edit/compile/debug code in Scala.
    * How to find/read the Scala documentation and use standard libraries
    * How to read and parse a CSV file in Scala

## Useful Resources

Review the lecture notes and provided example code for some insight into the Scala 
syntax.  You will also want to read the Scala references provided below:

* [The Scala API](https://www.scala-lang.org/api/current/index.html)
  * [scala.collections.mutable.Map](https://www.scala-lang.org/api/current/scala/collection/mutable/Map.html)
  * [Scala Collections](https://docs.scala-lang.org/overviews/collections-2.13/introduction.html)
* [Scala Tour](https://docs.scala-lang.org/tour/tour-of-scala.html)
* [Scala Resources](https://docs.scala-lang.org/)
* [ScalaTest: Writing your first test](https://www.scalatest.org/user_guide/writing_your_first_test)
* [Maps in Scala](https://docs.scala-lang.org/overviews/collections-2.13/maps.html)
* [Scala File I/O (Scala Cookbook Excerpt)](https://buffalo.box.com/v/cse250-ScalaCookbookIO)
* [Scala Exercises](https://www.scala-exercises.org/)

## Late Policy

The policy for late submissions on assignments is as follows.  Your project grade is the grade assigned to the latest (most recent) submission you make to autolab (or 0 if no submissions are made).

If your submission is made...

* ... 5 or more days before the deadline, your submission is assigned a grade of 5 bonus points + 100% of the points it earns. 
* ... fewer than 5 days before the deadline, your submission is assigned a grade of 1 bonus point per full day + 100% of the points it earns.
* ... within 24 hours of the deadline, your submission is assigned a grade of 100% of the points it earns.
* ... up to 24 hours after the deadline, your submission is assigned a grade of 75% of the points it earns.
* ... more than 24 hours after the deadline, but within 48 hours of the deadline, your submission is assigned a grade of 50% of the points it earns.
* ... more than 48 hours after the deadline, it will not be accepted.

You will have the ability to use three grace days throughout the semester, and at most 
two per assignment (since submissions are not accepted after two days).  Using a grace 
day will negate the 25% penalty per day, but will not allow you to submit more than 
two days late.  Please plan accordingly.  You will not be able to recover a grace day 
if you decide to work late and your score was not sufficiently higher.  **Grace days 
are automatically applied** to the first instances of late submissions, **and are 
non-refundable**.  For example, if an assignment is due on a Friday and you make a 
submission on Saturday, you will automatically use a grace day, regardless of whether 
you perform better or not.  **Be sure to test your code before submitting**, especially 
with late submissions **in order to avoid wasting grace days**.

**Keep track of the time if you are working up until the deadline**.  Submissions 
become late after the set deadline.  Keep in mind that **submissions will close 48
hours after hte original deadline** and you will not be able to submit your code after 
that time.

## AI Policy Overview

As a gentle reminder, please re-read the academic integrity policy of the course.  I 
will continue to remind you throughout the semester and hope to avoid any incidents.

### What constitutes a violation of academic integrity?

These bullets should be obvious things not to do (but commonly occur):
* Turning in your friend's code/write-up (obvious).
* Turning in solutions you found on Google with all the variable names changed (should be obvious).  This is a copyright violation, in addition to an AI violation.
* Turning in solutions you found on Google with all the variable names changed and 2 lines added (should be obvious).  This is also a copyright violation.
* Use of Github Autopilot (should be obvious).  This is still in murky legal water, and may be a copyright violation, in addition to being an AI violation.
* Paying someone to do your work.  You may as well not submit the work, since you will fail the exams and the course.
* Posting to forums asking someone to solve assignment problems *(even if you do not receive the solution)*
* Accessing solutions to assignment problems.  

**Note:** Aggregating every { stack overflow answer, result from google, other 
source } because you "understand it" will likely result in full credit on assignments
(if you are not caught), and then failure on every exam.  Exams don't test if you know
how to use Google, but rather test your understanding (i.e., do you understand the 
problem and material well enough to arrive at a solution on your own).  Also, other
students are likely doing the same thing, and then you will be wondering why 10 people
that you don't know have your exact solution.

### What collaboration is allowed?

There is a grey area when it comes to discussing the problems with your peers, and I 
do encourage you to work with one another to discuss course *concepts* related to 
an assignment.  That is the best way to learn and to overcome obstacles.  At the same 
time, you need to be sure you do not overstep and not plagiarize.  Discussions pointing
to relevant course materials are OK.  For example, the following is acceptable advice:

> It would be helpful to review the usage of the stack in the recitation slides from
> week XX.

When working with your peers, we ask that you include attribution; In the header 
comment of the Main function of your submission, please list all peers who you have
discussed the project with.

Explaining every step in detail and/or giving pseudocode that solves the problem
is **not ok**.  For example, the following is **not acceptable** advice:

> I copied the algorithm from the week XX notes into my code at the start of the
> function, created a function that went through the given data and put it into a list, 
> called that function, and then sorted the results.

The first example is OK.  The second example, however, is a summary of your code and
is not acceptable.  Remember that you should never show any of your code to other 
students prior to any deadlines.  Regardless of where you are working, you must always
follow this rule: **Never come away from discussions with your peers with any written
work, either typed or photographed, and especially do not share or allow viewing of
your written code**. 

If you have concerns that you may have overstepped or worked too closely with someone,
please address this with me prior to deadlines for the assignment.  **Even if you have
submitted an assignment that may have violated the course academic integrity policy,
if you approach me *prior to detection* you will not face academic integrity 
proceedings**.  We will address options at that point.

### What resources are allowed?

With all of this said, please feel free to use any { files | examples | tutorials } 
that course staff provides, directly in your code.  Feel free to directly use any
materials from lecture or recitations.  You will never be penalized for doing so,
but must always provide attribution/citation for where you retrieved code from. Just
remember, if you are citing an algorithm that is not provided by us, then you are 
probably overstepping.  

More explicitly, you may use any of the following resources (with proper 
citation/annotation in your code: 
* Any example files posted on the course webpage or Piazza (from lecture or recitation)
* Any code that the instructor provides
* Any code that the TAs provide
* Any code from the [Tour of Scala](https://docs.scala-lang.org/tour/tour-of-scala.html)
* Any code from [Scala Collections](https://docs.scala-lang.org/overviews/collections-2.13/introduction.html)
* Any code from [Scala API](https://www.scala-lang.org/api/2.13.0/)
* Additional references may be provided as the semester progresses, but only those provided publicly by course staff are allowed for use.  These will be listed on Piazza under Resources

**Omitting citation/attribution will result in an AI violation** (and lawsuits later 
in life at your job).  This is true, **even if you are using provided resources**.

Again, **if you think you are going to violate/have violated this policy, please come
talk to a member of the course staff ASAP so we can figure out how to get you on track 
to succeed in the course**.  If you have a question about the validity of a resource, 
please ask a TA or your instructor prior to using it.  If you have already used it, 
please discuss with the instructor to determine a workaround and, at the very least,
avoid an academic integrity infraction.  For example, you might send an email such
as the following to the course instructor:

> Clarus T Example<br/>
> **UBIT**: ctexamp<br/>
> **Person** #: 123456789
> 
> Dear Dr. Kennedy/Mikida,
> 
> I believe that I may have submitted work that is *{ not fully my own | not properly
> attributed }*.  I wish to retract my submission to preserve academic integrity in
> the course.
> 
> Signed,<br/>
> &nbsp;&nbsp;Clarus T Example

This policy on assignments is here so that you learn the material and how to think 
for yourself.  There is no cognitive benefit achieved by submitting solutions someone
else has written (which likely already exist in some form).

## Collaboration Policy

The policy for collaboration on assignments is as follows:
* All work for this course must be original individual work.
* You must follow the limits on collaboration as defined in the AI policy (i.e., no shared code/etc...)
* You must identify any collaborators (first and last name) on every assignment.  This can be in a comment at the top of your code submissions or on the first page at the top of your written work, beside your name.

All references must be cited using a comment containing a direct link to the resource, 
as well as a brief description of what was used.  For example, if you reference the 
textbook, a page number and description is sufficient.  If you copy example code from 
the Scala Language API, then include the link to the class page within the API as well
as where the example code resides.

## Project Setup

### Supported Platforms 

Scala is based on the Java Virtual Machine, and so will run on most modern 
operating systems.  However, only the following platforms are officially 
supported by this course.
* Ubuntu Linux
* MacOS with [Homebrew](https://brew.sh)

Instructions for Ubuntu should work without change for any Debian-based Linux 
distribution (Ubuntu, PopOS!, Debian, Mint).  

The [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/about),
along with the [Ubuntu](https://ubuntu.com/wsl) package will allow windows users to
follow the Ubuntu instructions.

**Course staff will make every attempt to assist you if you are using a platform that 
is not officially supported, but may lack the expertise needed to resolve your 
issue**.

### The Command Line

Instructions in class assignments will require running commands from the command line.
You'll need to access the command line with a terminal (type `terminal` in MacOS's 
spotlight or the Ubuntu launcher).  You should see a command prompt.  For example: 
```
-bash-4.2$ 
```
You can type commands at this prompt.  Commands usually have the form
```
[command name] [argument 1] [argument 2] [argument 3] ...
```
Common commands include:
* `pwd`: Print the current working directory (usually starts as `/home/[username]`)
* `ls`: List all the files in the current working directory
  * Files and directories starting with a `.` (dot) are "hidden".  To show hidden files and directories as well, use `ls -a` 
* `cd [dirname]`: Move the current working directory to `[dirname]`.  
  * `.` is a special directory name that refers to the current directory.  E.g., if your current working directory is `/home/zaphod` then `cd .` wouldn't change the directory at all.
  * `..` is a special directory name that refers to the parent directory.  E.g., if your current working directory is `/home/zaphod` then `cd ..` would move the working directory to `/home`
  * `~` (tilde) is a special directory name that refers to your home directory (typically `/home/[username]`).
* `man [command]`: Read the manual page for `[command]`.
* `cat [filename]`: Display (con**cat**enate to the console) the contents of `[filename]`. 

A package manager is like an app-store for the command line.  Ubuntu uses `apt`. MacOS
does not have a built-in package manager, but there are several that you can 
install.  This course assumes that you are using [Homebrew](https://brew.sh).  To
install a piece of software, type:
* **Ubuntu**: `apt install [name of package]`
* **MacOS**: `brew install [name of package]`

To find the name of a package, you can use:
* **Ubuntu**: `apt search [keywords]`
* **MacOS**: `brew search [keywords]`

### Editor + Mill

You will need a text editor and a Scala compiler for this course.  Popular editors 
include
* Emacs (`{brew/apt} install emacs`)
* Vim (`{brew/apt} install vim`)
* [SublimeText](https://www.sublimetext.com/)

Instructions for the course will be given using [SBT](https://www.scala-sbt.org/),
although other build tools exist.  For example, [mill](https://com-lihaoyi.github.io/mill/mill/Intro_to_Mill.html) 
and [bloop](https://scalacenter.github.io/bloop/) can be a little bit faster, but are
also a little less well-documented.

Install SBT with `{brew/apt} install sbt` or the instructions [here](https://www.scala-sbt.org/1.x/docs/Setup.html)

### IntelliJ

You may find it more convenient to use IDE (an all-in-one system that 
includes both an editor and a compiler).  A popular IDE for scala development that 
course staff are familiar with is [IntelliJ](https://www.jetbrains.com/idea/download/).
Installers for Ubuntu are available via [Flatpak](https://flatpak.org/setup/Ubuntu/).

You will need to install the **Scala** plugin (File → Settings → Plugins → Scala).

![The IntelliJ plugins settings wind with the Scala plugin showing](graphics/scalaplugin.png)

### Set up your GIT repository

This template project contains an SBT project definition.  Once you accept the PA1 project, clone it onto your computer

##### On the Command Line

```
git clone git@github.com:UB-Datastructures/fall-2022-pa1-scala-your_username_here.git
```

(replace `your_username_here` with your GitHub username)

##### In IntelliJ

Load the project from Version Control (File → New → Project from Version Control).  Paste in the URL of your PA1 project.

![The IntelliJ load from GIT panel](graphics/intellij_loadfromvcs.png)

The URL usually has the form: `git@github.com:UB-Datastructures/fall-2022-pa1-scala-your_username_here.git` (replace `your_username_here` with your GitHub username).

In order to use IntelliJ to run your project, you will need to add a Run Configuration.  Click "Add Configuration" in the upper right.

![The IntelliJ run toolbar](graphics/intellij_addconfig.png)

Click "Add New..." and select "SBT Task"

![The IntelliJ new run configuration type picker](graphics/intellij_addnewtypepicker.png)

Enter:

* `run` into the **Tasks** field
* `Run` into the **Name** field

![The IntelliJ run configurations setting](graphics/intellij_runconfig.png)

To add support for test cases, add a new "SBT Task" with the **+** button in the upper left.  Enter:

* `test` into the **Tasks** field
* `Test` into the **Name** field

Pick `Test` to run test cases in `src/test/scala/cse250/pa1/`, and `Run` to run the main function in `src/main/scala/cse250/pa1/Main.scala`.

**If you get an error telling you that you do not have a SDK installed, you will need to install one.**

Right-click the CSE-250 project in the menu on the left and choose "Module Settings".
Switch to the "SDKs" tab, click the **+** button, and pick a JVM version to install.  For CSE-250, it should not matter what JDK version you install (The present default: `openjdk-18` should be fine).

![The IntelliJ project settings window with SDK options selected](graphics/intellij_projectsettings.png)

## Instructions

Answer the following questions by:

1. Accept [The PA1 Assignment in GitHub Classroom](https://classroom.github.com/a/S55liqkK).
2. Use the template repository to answer the questions below.
3. Commit **and push** your answers to GitHub
4. [Submit PA1 in Autolab](https://autograder.cse.buffalo.edu/courses/CSE250-f22/assessments/pa1scala) (note: Submissions open September 10).

Make sure your submission is committed and pushed into your GitHub Classroom Git repository.  
Seriously, make sure it's committed.  Yeah you... the person who clicked submit without checking.

**Expect this project to take 8-10 hours of setting up your environment, reading 
through documentation, and planning, coding, and testing your solution.**

### NYS Open Data - Solar Installation Sites

*(30 points)*

We will be making use of a public dataset released by the NYS energy department 
(NYSERDA) of solar energy installation sites.  You can download the dataset at the 
[NYS Open Data Portal](https://data.ny.gov/Energy-Environment/Solar-Electric-Programs-Reported-by-NYSERDA-Beginn/3x8r-34rs)
by clicking on **Export** → **CSV**.  After you download it, place the resulting file 
in the `data` directory of your repository.

Your task with this dataset will be to sanitize and summarize the data file.  There 
are a number of columns that are not of interest to us, so we will create an updated
data file without these columns, while also obtaining some summary statistics.

**Note:** Although the specific tasks you will perform in this assignment are 
simplified to make them viable in the time allotted for the project, they are 
representative of common data processing tasks used for data exploration, 
visualization, and transformation, as well as for machine learning.  

**Problem 1** *(15 points)*: In the object `cse250.pa1.DataProcessor` define the
Scala function:
```scala
splitArrayToRowArray(rowData: Array[String]): Array[String]
```
with the following behavior:
* Assume that `rowData` is the result from taking some line from the Solar Installations dataset and invoking `split(',')`.
* Given `rowData`, place the data into an `Array` corresponding to the columns that would result from opening the original dataset file with a spreadsheet application.

Note that every row processed should produce a return result that contains the same 
number of column entries as the header row for the document.  This means that each
row, even if there are empty cells, should return an `Array` with 38 columns (even
if some are empty strings).  **Hint:** review the documentation for the `split` 
method for the cases where there are empty entries in a row.  **Hint**: Be mindful of
rows that contain cells with commas (see the CSV representation rules below).

A good way to test this functionality is to ensure that the first row of the dataset,
which contains the header, should return a copy of the row.  The second row of the
dataset, which contains successive blank entries, should still return a row with 51 
entries, but should have two empty values for the `ELECTRIC_UTILITY` and 
`PURCHASE_TYPE` fields, respectively.  Feel free to add the tests provided in this 
handout.

**Problem 2** *(5 points)*: In the object `cse250.pa1.DataProcessor` define the
Scala function:
```scala
rowArrayToSolarInstallation(rowArray: Array[String]): SolarInstallation
```
with the following behavior:
* Assume that the input `rowArray` is an `Array` containing 38 entries, corresponding to a row that was correctly processed through `splitArrayToRowArray`.
* Return the `SolarInstallation` object that corresponds to the data stored within the row.

Note that `SolarInstallation` is only meant to hold a limited number of headers from 
the dataset.  The headers that are required to be present are stored in the `Seq` 
named `SolarInstallation.REQUIRED_HEADERS`.  A full list of all headers is stored
in the `Seq` named `SolarInstallation.HEADERS`.  

The required headers correspond to the following headers/columns (where column 
number 0 corresponds to the first/left-most column): 

| Column | Label
| ------ | -----------------------------------------
|      0 | Reporting Period
|      1 | Project Number
|      3 | Street Address
|      9 | Municipality Type
|     10 | Census Tract
|     11 | Sector
|     12 | Program Type
|     14 | Electric Utility
|     15 | Purchase Type
|     17 | Date Completed
|     18 | Project Status
|     19 | Contractor
|     20 | Minority or Women Owned Business Enterprise (MWBE)
|     21 | Primary Inverter Manufacturer
|     22 | Primary Inverter Model Number
|     23 | Total Inverter Quantity
|     24 | Primary PV Module Manufacturer
|     25 | PV Module Model Number
|     26 | Total PV Module Quantity
|     27 | Project Cost
|     28 | $Incentive
|     29 | Total Nameplate kW DC
|     30 | Expected KWh Annual Production
|     31 | Remote Net Metering
|     32 | Affordable Solar
|     33 | Community Distributed Generation
|     34 | Green Jobs Green New York Participant
|     35 | Latitude
|     36 | Longitude
|     37 | Georeference

When you are finished, a `SolarInstallation` should contain exactly 30 entries (one
piece of data associated with each header).  This will cause the resulting updated
output file after running the given code to contain exactly 30 columns in each
row.  See more on the `SolarInstallation` Objects section below.

**Problem 3** *(5 points)* In the object `cse250.pa1.DataProcessor` define the
Scala function:
```scala
computeUniqueInverterManufacturers(dataset: Array[SolarInstallation]): Int
``` 
that determines the number of unique Inverter Manufacturers (corresponding to the
`PRIMARY_INVERTER_MANUFACTURER` column).  You should ignore any empty entry from
your count, as well as the column header.

**Problem 5** *(5 points)* In the object `cse250.pa1.DataProcessor` define the
Scala function:
```scala
computeAverageCostPerKWH(dataset: Array[SolarInstallation]): Float
``` 
that determines the average cost-per-KWH of all solar installations in the state.  This
corresponds to the ratio of the sums of the two corresponding columns:
$$\frac{\textbf{sum}(\texttt{PROJECT\\_COST})}{\textbf{sum}(\texttt{EXPECTED\\_KWH\\_ANNUAL\\_PRODUCTION})}$$

Note that your answer produced should make sense, so you should assume that the energy produced
by each installation should be positive.  If no valid data is found, you should return 0.


### `SolarInstallation` Objects

To represent a single data record, you must use the structure 
`cse250.objects.SolarInstallation` provided in the code skeleton.  
```scala
/**
 * One specific solar installation site.
 */
class SolarInstallation
{
  /**
   * Key-value pairs representing data about the solar site.  See [[SolarInstallation.HEADERS]] for a list of
   * allowable keys, and [[SolarInstallation.REQUIRED_HEADERS]] for a list of mandatory keys.
   */
  val fields: mutable.Map[String, String] = new mutable.HashMap[String, String]
```

Note that the file containing `SolarInstallation` will be overwritten when your 
code is graded, so any changes you make within will be reverted.  

The information stored within a `SolarInstallation` should be stored in the `fields`
attribute, which stores (**key** → **value**) pairs, where the header for the column
(**value** in the respective column in the first row) is the **key** and the value 
is the data found within the row in the corresponding column.  For example, the 
first installation (second row of the file) should be loaded as 

| Key                                     | Value        |
| --------------------------------------- | ------------ |
| `REPORTING_PERIOD`                      | `07/31/2021` |
| `PROJECT_NUMBER`                        | `0000000276` |
| `CITY`                                  | `Ithaca`     |  
|                   ...                                 ||
| `GREEN_JOBS_GREEN_NEW_YORK_PARTICIPANT` | `No`         |

Note that the value for `ELECTRIC_UTILITY` is simply an empty string, and there 
should be an entry for every header.  

### CSV Formatting

The formatting for the data file is CSV (comma-separated values).  CSV files are a 
way to represent columns of data by separating entries within a row by a comma. Each 
line represents a separate row of cells.  Two special cases arise that you must 
handle:
* If a cell contains a comma (`,`) within, the cell contents are enclosed in double quotes (`"`) at the start and end.  For example: `Comma, Cell` would be stored as `"Comma, Cell"`.
* If a cell contains a double quote (`"`) within, the cell contents are enclosed in double quotes (`"`) at the start and end, **and** each double quote in the cell data is duplicated.  For example, `The "Best" Around` would be stored as `"The ""Best"" Around"`

It is also possible that a cell contains both.  Note that if a data file contained the line
```text
First Cell,Second Cell,"The ""Best"" Around","Comma, Cell","""Object-Orientation, Abstraction, and Data Structures Using Scala"""
```
It would correspond to the following cells (e.g., if opened in Excel):

| 1          | 2           | 3                 | 4           | 5                                                                  | 
| ---------- | ----------- | ----------------- | ----------- | ------------------------------------------------------------------ |
| First Cell | Second Cell | The "Best" Around | Comma, Cell | "Object-Orientation, Abstraction, and Data Structures Using Scala" |  

### Suggested Approach

Set up your GitHub Classroom repository as detailed above and set up your programming 
environment.

#### SBT

1. There are three files in the `src` directory.  Open them with your code editor of choice.
2. Launch sbt by navigating to the root of your project directory in a terminal window and typing `sbt`.
3. Start continuous compilation by typing `~compile` at the sbt prompt.  You can exit by typing control-c (^c)

#### IntelliJ

1. Open IntelliJ
2. Select Open (possibly File → Open).
3. Navigate the the directory you checked out above.  Click OK
4. Confirm the request to import an SBT project if prompted.
5. Open `Main.scala` (src → main → scala → cse250 → pa1).  Test that the code builds properly by right-clicking Main → Run "Main".  If it ran correctly, you should see one of the following two errors
   * `Exception in thread "main" scala.NotImplementedError: an implementation is missing`
   * `Exception in thread "main" java.io.FileNotFoundException: data/Solar_Electric_Programs_Reported_by_NYSERDA__Beginning_2000.csv  (No such file or directory)`
6. Download the Solar Installations dataset and move it to the `project-0/data` directory.
   * The data file can then be opened by the filename `data/Solar_Electric_Programs_Reported_by_NYSERDA__Beginning_2000.csv`
   * I recommend you make a smaller test file of entries to work on.  To do this, make a copy of the solar installations file and then remove all of the lines after the first 10 or 100, etc..., and then save the file.
   * **It is not recommended to make modifications to the file in Excel as there may be unintended formatting side-effects upon saving.**
   * If viewing the `.csv` file in IntelliJ, I recommend **not** installing the plugin so you can continue viewing it as text, instead of the view that would be provided by software like Excel.  This is beneficial so you can see how the data you are manipulating looks.
7. Update the copyright statements in the necessary files with your name and UBIT.
8. Begin working on the problems requested. 
   * Note that when working on translating the rows from the csv data file, the last column of the data (when non-empty) contains a comma and should be treated as a single entry.  There may be other data entries that contain commas, as well, so be sure you think about how to handle this (look at the data set in a text editor/IntelliJ to see what the format is).
   * To check that this works, try adding print statements (`println(text)`), or by pausing the program in IntelliJ's debugger with breakpoints to check that the data is being read as you expected.
   * It is suggested to test your code via the file `DataProcessorTests`, although a `Main` class is also provided.
     * To run the `Main` class in SBT, type `run` at the SBT prompt, or type `sbt run` from the command line
     * To run the `Main` class in IntelliJ, right-click the `Main.scala` file and select **Run Main**
     * To run tests in SBT type `test` at the SBT prompt, or type `sbt test` from the command line
     * To run tests in IntelliJ, right click the folder `test` and select **Run 'ScalaTests' in 'test'...**
   * You are welcome to add more testing functions at your discretion, both in the `Main` object and in `DataProcessorTests`.
   * If code is not running properly, make sure your sources and tests root are set properly.  To do this, right click `src/main`, go to **Mark Directory as**, and select **Sources Root**.  Similarly, right click `src/test`, go to **Mark Directory as**, and select **Test Sources Root**.  The `main` folder should appear blue and the `test` folder should appear green if this is set up correctly.  

### Allowed library/container usage

* You may choose the collection classes you wish to use in your function implementation to solve these problems.

## Submission

For **Project 1** you may submit as many times as you want.  Your final score will be the last (most recent) submission


## Revision History
* Fall 2022 - Oliver Kennedy (okennedy@buffalo.edu), Eric Mikida (epmikida@buffalo.edu)
* Fall 2021 - Oliver Kennedy (okennedy@buffalo.edu)
* Spring 2021 - Andrew Hughes (ahughes6@buffalo.edu)
