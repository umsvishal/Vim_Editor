# Vim_Editor_Usage

[ vim - ] ---- Takes the input in the Buffer. 

-> :%! sort -u ---- used for sorting.
-> :%! grep -v [Excluding keyword] (Here, V means invert removing keyword.)
-> o  ---  Make changes in file.
-> esc ---- to go previously.
-> :wq!  --- write in the file and quit.
-> :qall!  ---- Quit without any pop up.
-> /  ----- For searching (/\.$)
-> $ ----- going at the end of every line.
-> :w results (For saving in a file called result)
-> n --- for next search
-> :%! --- Current File and ! (Bang) Run this in a shell [That means piping the data into a process and get back to vim.]
-> :%! grep -v "Keyword" ---- deleting that line which matches that keyword.
-> crtl + v --- for selecting more than one (Visual Mode).
-> x ---- for deletion.
-> :%! xargs --- takes multiple line and traverse through it.
-> :%s/searchword/replacementword   --- for searching and replacing.
-> ctrl+shift+v   ---- for pasting text in the vim editor.
-> shift+gg  ---- going last line of the vim editor.
-> gg  --- first line of the vim editor.
-> :%s/^firstcharacter//   --- to remove first character.
-> Visual mode (ctrl+v) and x ---- To remove the selected.
-> Press y to copy it, or d to cut it and P to paste.
-> :%!unfurl -u domains  ----- sorting unique subdomains from list.
