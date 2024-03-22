In this tutorial you will learn how you can seamlessly get started with Harness CI for ```Python```. In this pipeline we will be implementing a Hello World Server in `Python`.
### Step 1: Fork the repository 
- Go to [Python-Pipeline-Samples Repo](https://github.com/harness-community/python-pipeline-samples)
- Now fork this repository in your Github [Forking a repository in Github](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
### Step 2: Create your Harness Project

- Move to the Harness Platform & click on Project -> New Project
- Configure the project settings as below

  `Name: (Default Project Name)`


  `Organization: Default`
 
 <img width="1792" alt="Screenshot 2022-09-09 at 10 24 17 AM" src="https://user-images.githubusercontent.com/109092049/192598400-7254737b-ff8b-4e1c-bdc8-6efd2895f011.png">


[^1]: This is the first footnote. It can contain additional information or references.
[^2]: This is the second footnote. You can use footnotes to add explanatory notes or citations.

::uml:: format="png" classes="uml myDiagram" alt="My super diagram placeholder" title="My super diagram" width="300px" height="300px"
  Goofy ->  MickeyMouse: calls
  Goofy <-- MickeyMouse: responds
::end-uml::

- Select CI Module in the modules sections


### Step 3: Pipeline Creation & Configure Stages

- Click on `Pipelines` -> Create a Pipeline 
- Configure the pipeline as below

  `Name: CI-Python-Quickstart`

  `Set up pipeline as: Inline`

<img width="1792" alt="Screenshot 2022-09-09 at 10 32 57 AM" src="https://user-images.githubusercontent.com/109092049/192598502-92912fe7-3102-4b77-845c-ba914b684754.png">

To know more about Pipelines [check out the docs here](overview.md)
Next, we are going to add Stages and steps to our Pipeline and compile our Python code.

Click on **[Build step](build.md)**


<div class="custom-class">
This div has a custom class attribute.

</div>

!!! info "Information"

Term 1
: Definition 1

Term 2
: Definition 2


This^text^contains^carets^interspersed^within^words.

<details>
<summary>Click to expand</summary>
This is a collapsible details block created using the details extension.

</details>

:smile:


 ==highlighted text==


 <kbd>Ctrl</kbd>+<kbd>C</kbd>

 #1234 

==This text is marked using the mark extension.==

=== "Tab 1"
Markdown content for Tab 1. This can include multiple paragraphs, lists, and other Markdown elements.

=== "Tab 2"
More Markdown content for Tab 2. You can add various elements like lists, code blocks, and text here.

===! "New Tab Set"
Starting a new tab set explicitly with different content.

=== "Tab A"
Content for Tab A in the new tab set.

=== "Tab B"
Additional content for Tab B in the same tab set.

===+ "Selected Tab"
Markdown content for a tab that is selected by default when the page loads.
