# sublime_text

## Description
This is an adaptable sublime syntax-colouring scheme which when applied can, for instance, highlight certain symbols, punctuation, or patterns that are of interest to TN. 

[Click here to see a preview of the tool, and how it can color text](https://ibb.co/nnvzhYt)

## Setting up the sublime-syntax colouring scheme:
- Install sublime text [here](https://www.sublimetext.com/3)
- For Ubuntu, paste the `TN.sublime-syntax` & `Monokai.sublime-color-scheme` in the following folder: `/home/{USER}/.config/sublime-text/Packages/User`
- For Windows or other OS, to find out where the `../User` folder is by using the GUI navigation in Sublime:
	+ Preferences > Browse Packages > User
- Install **package control** by opening the Sublime **command palette**; on Ubuntu the shortcut is: **ctrl+shift+p**
- Open the **command palette**, and type 'select color scheme' and choose **Monokai**.
- Open the **Command palette** again, and type: **Set Syntax: {name of your sublime-syntax file}**

The effects should be observable immediately in your text files. 

## In addition:
- both the sublime-syntax and the colouring scheme can be easily configured, respectively, in both files. 
	+ Use regex and [Scope](https://www.sublimetext.com/docs/scope_naming.html) conventions to adapt pattern colouring parameters in `TN.subime-syntax`
		* But if you want to keep it simple: e.g. in the `TN.sublime-syntax` file, under the section `Keywords`, in Regex format, add/delete a keyword of your choosing (perhaps have your textfile open in a 2nd tab in Sublime (alt+shift+2), and observe the effect.)
	+ In the `Monokai.sublime-color-scheme` one can change/add colours per defined **Scope**.
