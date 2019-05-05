### RHex - Fly fishing related dynamic simulations

The applications of the RHex project create realistic dynamic 3D computer simulations that will interest both fly fishers and fly-rod builders.  There are two main applications, RHexSwing3D and RHexCast3D.

The first shows the behavior of a fly-line, leader, tippet, and fly combination that is laid down on the surface of a stream and then allowed to swing under the influence of the stream's various water velocities, rod tip motion and line stripping. The results of these simulations give insight into the effects of line setup, fly choice and fisher action on fly presentation. Some of the things you see are likely to surprise you. Although the primary focus of this simulation is on swing streamers, the program can also be used to elucidate czech and indicator nymphing.

The second application displays the behavior of a fly rod and line combination during an aerial cast as they respond to motions of the rod handle.  This simulation has much to say about the details of rod and line design, as well as to casting technique.

### Distribution

You can download RHex executable packages by clicking the links below:

[RHex_Exe-0.1.0-Mac](https://github.com/RHexMan/RHexMan.github.io/???)

### Some details

Each program has an interactive control panel that allows setting, saving, and retrieving of complex parameter sets, running the simulations, and plotting and saving the results, both as text and as static graphic files. The primary outputs of these programs are 3D mouse-rotatable plots that show the rod and/or line as a sequence of traces representing the component configuration at equally spaced times. The earliest traces are shown in green and the latest in red, with the intermediate ones shown in brownish shades that are the combination of green and red in appropriate proportion. Open circles, solid circles, diamonds and squares mark the locations of the rod tip, line-leader and leader-tippet junctions, and the fly. In addition to the rotation, the plots may be zoomed and translated in real time, which allows comprehensive inspection of the data. The last section of this document describes how to effect the various transformations.

An auxilliary program, RHexReplot3D, allows the replotting of saved text data, with a possibly different choice of line and point markers and reduced time range and frame rate.

The control panel of each of the programs has a help menu in the upper right corner which gives access to a general discussion of the program, its license, detailed descriptions of the user-settable parameters, including their allowed and typical value ranges, and an exposition on gnuplot view manipulations.

RHexCast3D and RHexSwing3D both make use of external files that allow nearly complete freedom to customize the details of the rod and line setup and driving motion. The distribution includes a number of folders that organize these files and that contain examples. Except for one sort of rod driving specification which requires a graphics editor, all the files are text, and can be opened, read and written with any standard text editor. Each example file has a header with explanatory information. The idea is that when you want a modified file, you copy the original, make changes in your copy, and save it, with a different name, to the same folder.

### History

The RHex project was preceded by the static Hexrod project of Wayne Cattanach, which was itself a computer updating in BASIC of the historical hand calculations of Garrison (see "A Master's Guide to Building a Bamboo Fly Rod", Everett Garrison and Hoagy B. Carmichael, first published in 1977). Frank Stetzer translated Cattanach's code into CGI/Perl in 1997, and continues to maintain and upgrade it (www.hexrod.net).









## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/RHexMan/RHexMan.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/RHexMan/RHexMan.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
