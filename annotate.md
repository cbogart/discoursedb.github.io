---
layout: default
published: true
---

The [DiscourseDB data browser](https://erebor.lti.cs.cmu.edu/discoursedb/) allows you to 
browse the discussions that are part of any of the datasets you have been granted access to.
You can choose a dataset in the left panel and navigate through its structure (e.g. forums,
threads, discussion groups), and select multiple conversations you want to see.

<img alt="Drill down to checkboxes in left-hand panel" src="select_subset.png" width="250px">

To analyze these conversations it's often useful to work through a sample methodically and
mark them up to highlight interesting phenomena.  For example an education researcher might
mark instances of [transactive](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5405832/) 
responses to learn more about when students are responding constructively to each other in
an online course.

<h3>The high-level workflow for accomplishing this in DiscourseDB is as follows:</h3>

1. Choose a subset of the dataset you are interested in
2. Open that subset in Brat for annotation
3. Add annotations in the Brat tool 
  * Don't forget to log in!
  * No need to save your work!
4. Return to DiscourseDB, and explicitly re-import the Brat annotations

<h3>The steps in detail:</h3>

1. Choose a subset of the dataset you are interested in
  * Use the left panel to select a subset of the dataset that you are interested in annotating.
  * Click "Remember" in the top-center, and name this selection.  You can only annotate a named selection

<img alt="Click remember then type the name you want to assign" src="save_selection.png" width="250px"> 
  
2. Open that subset in Brat  
  * In the right panel, choose Annotate, and click the Annotate icon 
  * The Brat page will open in your browser.  The Brat tool 
requires a separate login at this time: click "login" in the upper right
corner, and use username 'discoursedb' and password 'discoursedb' 
  * Navigate through the hierarchy to conversations you are interested in
annotating.  Once you are in a conversation, you can move among them with the Next and Previous
links at the top of the page.

<img alt="click Annotate" src="brat_choices.png" width="150px">
<img alt="click Brat in upper right, and log in" src="brat_login.png" width="250px">

3. Add Annotations in the Brat tool
  * <font color="red">IMPORTANT</font>: Select a substring of the <em>header</em> of a contribution
in order to label the whole contribution, as shown in the picture below.  Our current generation of
tools do not work with annotations of particular spans within a contribution, or selections spanning
multiple contributions. 
  * You are limited to the annotations supplied -- if you want a different label, please contact us.
A way to choose your own set of labels is coming soon.

<img alt="select part of the header of a contribution" src="select_header.png" width="250px">

4. Return to DiscourseDB and explicitly re-import the Brat annotations
  * When you are done, just close the Brat window -- your annotations are saved as you go.
  * If the database and subset you've been examining are not selected, select them
  * Open the Annotate pane in the right panel, and click "import" 
  
<img alt="click Annotate" src="brat_choices.png" width="150px">
