Table of contents:


# Visual Studio Code

VS Code (Visual Studio Code): 
https://github.com/viatsko/awesome-vscode

VS Code Shortcuts for code newbies [mac/windows][
https://dev.to/iraamoni/vs-code-shortcuts-for-code-newbies-mac-windows-gif-h6c

Productivity and tracking extensions for Visual Studio Code 
https://dev.to/lampewebdev/productivity-and-tracking-extensions-for-visual-studio-code-1h84

13 Must-Have Browser Extensions for Web Developers: 
https://medium.com/better-programming/13-must-have-browser-extensions-for-web-developers-7f4f3b1c623d

Shortcuts in VSCode:
https://link.medium.com/8Cl3Um0iN1

Additional Tips and Extensions:
https://viatsko.github.io/awesome-vscode/

Setting up Windows Cmder to be your default VSCode integrated terminal/shell:
https://medium.com/@qjli/how-to-setup-custom-terminal-in-visual-studio-code-e0a4be28130e

15 VS Code Extensions to Save Your Time and Make You a Better Developer
https://levelup.gitconnected.com/15-vs-code-extension-to-save-your-time-and-make-you-a-better-developer-506f79baec53

Set Up Remote Development With VS Code in Your Browser:
https://medium.com/better-programming/set-up-remote-development-with-vs-code-in-your-browser-4b5750d3d141


### VS Code Extensions 

Also see:
https://viatsko.github.io/awesome-vscode

Interface Generator - creates an interface definition from a typescript class. Supports import statements, comments, public properties and methods, generics and optional:
https://marketplace.visualstudio.com/items?itemName=dotup.dotup-vscode-interface-generator


Filter Lines - Filter in/out lines in the currently open file by either Regex or String matching.
https://marketplace.visualstudio.com/items?itemName=earshinov.filter-lines

Bookmarks - Set and jump to bookmarks in the code:
https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks

REST Client:
https://marketplace.visualstudio.com/items?itemName=humao.rest-client

Language support for Java by Red Hat:
https://marketplace.visualstudio.com/items?itemName=redhat.java

Debugger for Java:
https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug

Maven for Java:
https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven

Lombok - Adds support for Lombok annotations within VSCode. 
https://marketplace.visualstudio.com/items?itemName=GabrielBB.vscode-lombok

Gi - Generate .gitignore lines easily
https://marketplace.visualstudio.com/items?itemName=rubbersheep.gi 

Git History:
https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory

Git Lens:
https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens

Paste JSON as Code - Paste JSON text and generate a model class for it in several languages including TypeScript, Java, Python, Go, Ruby, C#, Swift, Rust, Kotlin, C++, Flow, Objective-C, JavaScript, Elm, and JSON Schema:
https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype

Path IntelliSense - Autocomplete filenames:
https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense

Auto Close Tag - Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text
https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag

Sort Lines - Sorts lines in the selected text:
https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines

Surround - A simple yet powerful extension to add wrapper templates around your code blocks.  Great for generating try/catch blocks around lines of code like in Eclipse or IntelliJ:
https://marketplace.visualstudio.com/items?itemName=yatki.vscode-surround

Browser Preview - Launch a browser (Chrome, IE, etc) in a new window with your current VSCode window's code running in it:
https://marketplace.visualstudio.com/items?itemName=auchenberg.vscode-browser-preview

Live Share Extension Pack:
https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack

Live Share Whiteboard - Live Share Whiteboard enhances the existing Visual Studio Live Share experience, by enabling you to open an integrated whiteboard, without needing to use a seperate tool or service. All participants within a Live Share session can collaboratively draw on the whiteboard, and see each others changes in real-time. For certain use cases (e.g. technical interviews, mentoring/classrooms), this can provide a useful means of communication, in addition to an audio call and co-editing and debugging.
https://marketplace.visualstudio.com/items?itemName=lostintangent.vsls-whiteboard

Angular Follow Selector - Enables clicking on Angular selectors in your HTML files and being redirected to their component definition, as well as the other way around by clicking on templateUrl and styleUrls in your component.
https://marketplace.visualstudio.com/items?itemName=sanderledegen.angular-follow-selector

json2ts - Convert a JSON from clipboard to TypeScript interfaces.
https://marketplace.visualstudio.com/items?itemName=GregorBiswanger.json2ts

Angular Snippets From John Pappa (Version 8):
https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2

Jira and Bitbucket - Bringing the power of Jira and Bitbucket to VS Code - With Atlassian for VS Code you can create and view issues, start work on issues, create pull requests, do code reviews, start builds, get build statuses and more:
https://marketplace.visualstudio.com/items?itemName=Atlassian.atlascode

Break from Comma - Adds line breaks after commas in a highlighted block text:
https://marketplace.visualstudio.com/items?itemName=jzarzoso.break-from-comma

import-cost - VS Code extension that shows import sizes of each import:
https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost


### VS Code from the command line: 

#Run VSCode from command line
code

#Get help
code --help

#Open VSCode in a new window instead of re-using an existing one
code -n

#Force VSCode to open using the last known open window
code -r

#Get VSCode version
code --version

#Show all the extensions currently loaded in VSCode
code --list-extensions

#Show all the extensions currently loaded in VSCode and show their versions
code --list-extensions --show-versions

#VSCode opens file example.txt and positions to line # 55, character 30
code example.txt:55:30

#VSCode disable all extensions
code --disable-extensions

#Print process usage and diagnostics information.
-s, --status	

-p, --performance	Start with the Developer: Startup Performance command enabled.

--disable-gpu	Disable GPU hardware acceleration.

--verbose	Print verbose output (implies --wait).

--prof-startup	Run CPU profiler during startup.

--upload-logs	Uploads logs from current session to a secure endpoint.