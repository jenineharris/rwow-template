## Using the RWoW R Markdown Template

### Requirements

1) Some experience with R and R Studio are necessary to use this template
2) R and R Studio software are necessary to use this template
3) Install the `posterdown` package in R Studio before using the template

### Download and Save Workshop Materials

Download the participant files and save them together in the same folder on your computer:

<ul>
<li> Click on the green Code button toward the top of this GitHub page
<li> Choose Download ZIP
<li> Unzip the downloaded zip file and save all the files in a single folder on your computer
</ul>

### Updating the YAML

The code between the `---` at the top of the document includes formatting details.

The following should be changed to fit your project:

<ul>
  <li> Change the title, "Brown School RWoW Poster Template for your Fabulous Project" to your project title. Leave the `title: <br>` as it is.
  <li> Change the author name, "by Jenine K. Harris, PhD" to your name. Leave the "author:" and "- name: /<br/>" as it is.
</ul>

The following are optional changes: 

<ul> 
  <li> Change any of the color RGB codes to other colors from the <a href ="https://marcomm.wustl.edu/resources/branding-logo-toolkit/color-palettes/">WUSTL style guide</a>.
  <li> Make other changes to the look and feel in the YAML based on <a href = "https://github.com/brentthorne/posterdown/wiki/posterdown_html">this guide</a> that was the basis for the RWoW template.
</ul>

### Other formatting edits to be aware of

Tables are difficult to format in R Markdown knitted documents. The template shows an example using `table1` to create your table. Other table code has not been tested so this is the recommended way to incorporate a table. Here is the <a href = "https://cran.r-project.org/web/packages/table1/vignettes/table1-examples.html">table1 vignette</a> for more information.

If you have a `table1` table in your poster, you must leave the css at the top for it to work (or it will be teeny tiny): 

<style type="text/css">

table.Rtable1 {
   font-family: "Palatino";
   font-size: 45px;
}
</style>

### HAVE FUN! What better place to have an R poster than R-WoW!
