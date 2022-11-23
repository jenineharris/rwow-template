## Using the RWoW R Markdown Template

Make a research poster like this one using the R Markdown template for RWoW:

<img src = "https://github.com/jenineharris/rwow-template/blob/main/tiny-poster-image.jpg">

### Requirements

1) Some experience with R and R Studio are necessary to use this template
2) R and R Studio software are necessary to use this template
3) Install the `posterdown` package in R Studio before using the template

### Download and Save the Template Files

<ul>
<li> Click on the green Code button toward the top of this GitHub page
<li> Choose Download ZIP
<li> Unzip the downloaded zip file and save all the files in a single folder on your computer
</ul>

### Test the Poster Template Before Using

<ul>
  <li> Double click the rwow-template.Rproj to open the R project where the template is stored
  <li> Open the RWoW Poster Template.Rmd R Markdown file
  <li> Knit the file as-is before making changes to make sure it works
  <li> If it works, continue on!
</ul>

### Update the YAML

The code between the `---` at the top of the document includes formatting details. Anything you change here can change the look and feel of the document. It is recommended that you make only necessary changes to the title and author.

The following should be changed to fit your project:

<ul>
  <li> Change the title, "Using R for RWoW&#58; An R Markdown Poster Template for your Fabulous Project" to your project title. Leave the "title: &lt;br&gt;" as it is. Note that if you use an punctuation in your title, you maybe have to change it to <a href="https://www.ee.ucl.ac.uk/~mflanaga/java/HTMLandASCIItableC1.html">ASCII</a> so it renders properly.
  <li> Change the author name, "by Jenine K. Harris, PhD" to your name. Leave the "author:" and "- name: &lt;br&gt;" as it is.
</ul>

The following are optional changes: 

<ul> 
  <li> Change any of the color RGB codes to other colors from the <a href ="https://marcomm.wustl.edu/resources/branding-logo-toolkit/color-palettes/">WUSTL style guide</a>.
  <li> Make other changes to the look and feel in the YAML based on <a href = "https://github.com/brentthorne/posterdown/wiki/posterdown_html">this guide</a> that was the basis for the RWoW template.
</ul>

### Update the Content

Replace the `# Introduction` and everything afterwards with your project text, code, and output using regular R Markdown formatting features.

Anytime you use a single hashtag to denote a section, this will result in a gray section header, see the knitted version for an example.

### Other Formatting Edits to be Aware Of

Tables are difficult to format in R Markdown knitted documents. The template shows an example using `table1` to create a table. Other table code has not been tested so this is the recommended way to incorporate a table. Here is the <a href = "https://cran.r-project.org/web/packages/table1/vignettes/table1-examples.html">table1 vignette</a> for more information on using the `table1` package to make tables.

If you have a `table1` table in your poster, you must leave the css at the top for it to work (or your table will be teeny tiny): 

<style type="text/css"><br>

table.Rtable1 {<br>
   font-family: "Palatino";<br>
   font-size: 45px;<br>
}<br>
</style><br>

### HAVE FUN! What better place to have an R poster than R-WoW!
