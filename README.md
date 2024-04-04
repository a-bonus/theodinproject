# theodinproject

This is where I'm keeping track of all of my notes as I go through the entirety of The Odin Project

<h3> Git Cheatsheet </h3>

<p>
This is a reference list of the most commonly used Git commands. 

> Commands related to a remote repository:
`git clone git@github.com:USER-NAME/REPOSITORY-NAME.git`
`git push` or `git push origin main` (Both accomplish the same goal in this context)

> Commands related to the workflow:
`git add .` 
`git commit -m "A message describing what you have done to make this snapshot different"`

> Commands related to checking status or log history
`git status`
`git log`

> The basic Git syntax is program | action | destination.

> For example,
> git add . is read as git | add | ., where the period represents everything in the current directory;
> git commit -m "message" is read as git | commit -m | "message"; and
> git status is read as git | status | (no destination).

> Git best practices
Two helpful best practices to consider are:
1. atomic commits
2. leveraging those atomic commits to make your commit messages more useful to future collaborators.

> Atomic commit is a commit that includes changes related to only one feature or task of your program. 
<h4> There are two main reasons for doing this <h4>
1. If something you change turns out to cause some problems, it is easy to revert the specific change without losing other changes

2. It enables you to write better commit messages. 

</p>

## CSS notes
- To reference a class ID in CSS, use a period (.) before the class name
- To reference an ID in CSS, use a hashtag (#) before the ID name
- To use RGB color in CSS, use the following syntax: rgb(255, 0, 0)
- If css file is red, it means that the file is not linked to the HTML file or there are syntax errors in the css file
- To link a css file to an HTML file, use the following syntax: <link rel="stylesheet" type="text/css" href="style.css">
- When using a class id for example <p class="example">, in order to reference it in CSS, use the following syntax: .example
- To chain classes in CSS, use the following syntax: .example1.example2, where example1 and example2 are the classes you want to chain, the purpose of this is to apply the same styling to both classes without having to repeat the same code twice 
- To chain classes in HTML, use the following syntax: <p class="example1 example2">, where example1 and example2 are the classes you want to chain, and the CSS code would look like this: .example1.example2 {color: red;}. This means that the text in the paragraph will be red. But why not just use one class, like example 1? The reason is that you might want to apply the same styling to other elements in the future, so it's better to chain classes.  
- To use a class in CSS, use the following syntax: .example {color: red;}, where example is the class name and color: red; is the styling you want to apply to the class
- Border box is a property in CSS that includes padding and border in the width and height of an element, for example 
```  
  .example {
    box-sizing: border-box;
    width: 100px;
    padding: 10px;
    border: 5px solid black;
  }
```

- The Box model is a model in CSS that consists of the following properties: margin, border, padding, and content. The margin is the space outside the border, the border is the border of the element, the padding is the space between the border and the content, and the content is the content of the element. 

