# Wiki Tips

[[Wiki Home Page|Home]]

https://help.github.com/articles/adding-links-to-wikis/

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code

To escape any code (markdown, js and so on) either use a tab or 4 spaces.

### Add an image to wiki from Github repository (change sandbox when using different repo):

    [[https://github.com/jmarsh-gh/sandbox/blob/master/img/img_name.png|alt=error]]

# Test_title

### To add syntax highlighted code:

    ```javascript
    function cbFunc(value){
	for(var x = 0; x < holdString.length; x++){
		alert(holdString[x]);
		if(value === holdString[x]){
			holdString = holdString.replace(holdString[x],'');
			alert(holdString);
			return true;
		} 
	}
	return false;
    }
    document.write(bool);
    ```

which looks like:

```javascript
function cbFunc(value){
	for(var x = 0; x < holdString.length; x++){
		alert(holdString[x]);
		if(value === holdString[x]){
			holdString = holdString.replace(holdString[x],'');
			alert(holdString);
			return true;
		} 
	}
	return false;
}
document.write(bool); 
```

### To add a table:

    Colons can be used to align columns.
    
    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |
    
    There must be at least 3 dashes separating each header cell.
    The outer pipes (|) are optional, and you don't need to make the 
    raw Markdown line up prettily. You can also use inline Markdown.
    
    Markdown | Less | Pretty
    --- | --- | ---
    *Still* | `renders` | **nicely**
    1 | 2 | 3

which looks like

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

and

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


[intrapage link 1](Github-Wiki-Guide#Wiki Tips)
[intrapage link 2](Github-Wiki-Guide# Wiki Tips)
[intrapage link 3](Github-Wiki-Guide#Test_title)
[intrapage link 4](Github-Wiki-Guide# Test_title)