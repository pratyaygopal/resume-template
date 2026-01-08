# resume
This is my custom resume template in typst. 

The LaTEX toolchain is too cooked to install locally. 

Fedora Setup:
```
sudo dnf copr enable claaj/typst
sudo dnf install typst
```

To use this template:
```
typst watch resume.typ
```
The command above will set up a typst watcher which will compile `resume.pdf` everytime you make a change on `resume.typ` and save it

For more documentation on typst click these links: 
- [website](https://typst.app/)  
- [github](https://github.com/typst/typst)
- [compiler docs](https://typst.app/open-source/)
