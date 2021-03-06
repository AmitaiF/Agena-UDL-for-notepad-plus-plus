# Agena UDL for Notepad++
## What is it?
It's a file that declares rules for formatting keywords, comments, numbers, and delimiters for the Agena language.
It can be imported to the Notepad++ app.
## Why do we need it?
When I started programming with Agena, I quickly realized that the official editor of Agena isn't comfortable to work with.
I decided to program using Notepad++ instead, but although Notepad++ comes prepackaged with many Language lexers, Agena isn't included in those packages.
So I decided to create my own UDL for Agena!
## How to use it?
1. Download the AgenaUDL.xml file. You can download it as a zip file, or you can clone it:
```
git clone https://github.com/AmitaiF/Agena-UDL-for-notepad-plus-plus.git
````
2. Open Notepad++.
3. On the menu click on ```Language``` > ```Define your language...```
4. Click the ```Import``` button.
5. Select the AgenaUDL.xml file you downloaded.
## The colors
I'm not a "color expert" or something, and my main goal was to clearly separate between different keywords, comments, etc.
So you might find my color selection horrible. Sorry for that.
You can create your own UDL: [Official NPP docs](https://npp-user-manual.org/docs/user-defined-language-system/)
If you want to use my UDL as a base for your UDL, you can just change the required ```fgColor``` attribute in the AgenaUDL.xml file.
## Example
After the warning above, you can see an example of the UDL:


![alt text](https://github.com/AmitaiF/Agena-UDL-for-notepad-plus-plus/blob/main/Agena%20UDL%20Example.png "Agena UDL Example")
