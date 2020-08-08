# Horiseon Code Refactor

## Description

This code has been refactored in order to better organize, navigate and access the code. It has also been optimized to be better accessible to search engines. 

### Technologies Used

* Github
* VS Code
* Google Developer Tools

### Repairs and Modifications 

On the original web page there were several functions with errors. The header's Search Engine Optimization button did not navigate to the SEO portion of the page and the 'Horiseon' logo of the page provided no function. In order to repair these errors, a href element was addded to them. Taking agency, I also added a jumbotron-style and modified the title name to the companies name. 

### HTML Organization and Additions

In order to better navigate the HTML code notes have been added, telling which portion of the web page the code is connected to. The HTML code had minimal errors but has been better organized with proper indentation and notes to permit a better understanding to visitors of the webpage. Descriptions were added to each of the images on the main content page for better accessibility.

### CSS Organization and Consolidation 

The styling sheet of the web page contained a lot of unnecessary overlapping styles. Much of the styling has been consolidated and notated to give easier navigation to developers and anyone that is curious. 

### What I Learned

This challenge provided excellent practice to properly create an effecient code for a web page. An important portion that I found helpful was consolidating the CSS Style Sheet. Initially the style sheet had a lot of repetitive styling, but what I learned was that you could consolidate the styles by putting the parent element, followed by the child element. Example provided below.
   
    .benefits div img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

Another important thing I learned was how to properly clone a repository from github and then clone its contents to your own local repository. A major issue I had at the beginning of the assignment was that when I copied the repository to my local repository it would cause issues such as trying to push to its original origin master. However, after some googling I found the command to remove the origin (git remote rm origin) then apply my github url as the origin (git remote add origin <url>).


## Credits

### Xander Rapstine https://github.com/Xandromus
Provided the repository with the original code to be modified.

### Michelle Lam https://github.com/michelleklam
Provided great help to reviewing the code. 



