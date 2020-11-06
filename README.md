# HTMLchecker
This project was created in my Java class, which is about checking the HTML syntax. The project checks the html tags <> and corrects them using maps and stacks. It checks if the previous tag was closed before starting a new one or not. The way it checks is it puts the tags into the stack when they are opening, and if it enocounters any closing tag. It checks the top value in the stack if the opening tag matched the closing tag or not. If it matches then the opening tag gets removed from the stack, if the closing tag didnt matched opening then we add the closing tag. Also removes the opening tag in the stack and checks the next closing tag value. 
If in the end there are no closing tags then we add the closing tags for the opening tags that are still in the stack.

