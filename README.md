<h1 align="center">
  <a href="https://github.com/whatsupabhijit/CV-Using-Latex" title="Documentation">
    <img alt="Abhijit Dutta CV" src="https://github.com/whatsupabhijit/CV-Using-Latex/blob/master/images/profilpicture.png" width="200px" height="200px" style="border-radius: 50%; img:hover{transform: scaleX(-1);}"/>
  </a>
  <br />
  Abhijit Dutta CV
</h1>

<p align="center">
  LaTeX template for job application
</p>

<div align="center">
  <a href="https://www.overleaf.com/project/5f3d4d771cf30f0001c5fe7a">
    <img alt="Overleaf" src="https://img.shields.io/badge/cv-pdf-green.svg"/>
  </a>
  <a href="https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/cv.pdf">
    <img alt="Example CV" src="https://img.shields.io/badge/cv-pdf-green.svg" />
  </a>
  <a href="https://github.com/whatsupabhijit/CV-Using-Latex/blob/master/coverLetter.pdf">
    <img alt="Example Coverletter" src="https://img.shields.io/badge/coverletter-pdf-green.svg" />
  </a>
</div>

<br />

## Preview

#### Résumé

You can see [PDF](https://github.com/whatsupabhijit/CV-Using-Latex/blob/master/CV.pdf)


|[![Résumé](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume-1.png)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume.pdf) |


#### Cover Letter

You can see [PDF](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter.pdf)

[![Cover Letter](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter-1.png)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter.pdf) |

## Quick Start

* [**Edit Résumé on OverLeaf.com**](https://www.overleaf.com/project/5f3d4d771cf30f0001c5fe7a)
* [**Edit Cover Letter on OverLeaf.com**](https://www.overleaf.com/project/5f3d4d771cf30f0001c5fe7a)

**_Note:_ Above services do not guarantee up-to-date source code**


## How to Use

#### Requirements

A full TeX distribution is assumed.  [Various distributions for different operating systems (Windows, Mac, \*nix) are available](http://tex.stackexchange.com/q/55437) but TeX Live is recommended.
You can [install TeX from upstream](http://tex.stackexchange.com/q/1092) (recommended; most up-to-date) or use `sudo apt-get install texlive-full` if you really want that.  (It's generally a few years behind.). You can also install MiKTex for windows.

#### Usage

At a command prompt, run

```bash
$ xelatex {your-cv}.tex
$ xelatex {your-coverletter}.tex
```

You can also store the commands in a file and then run using shell command
```bash
$cat cmd.sh
xelatex cv.tex
xelatex coverLetter.tex
$ sh cmd.sh
```

This should result in the creation of ``{your-cv}.pdf`` and ``{your-coverletter}.pdf``


## Credit

[**LaTeX**](http://www.latex-project.org) is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia.

[**LaTeX FontAwesome**](https://github.com/furl/latex-fontawesome) is bindings for FontAwesome icons to be used in XeLaTeX.

[**Roboto**](https://github.com/google/roboto) is the default font on Android and ChromeOS, and the recommended font for Google’s visual language, Material Design.

[**Source Sans Pro**](https://github.com/adobe-fonts/source-sans-pro) is a set of OpenType fonts that have been designed to work well in user interface (UI) environments.

This CV is inspired by the design of [**Awesome CV**](https://github.com/posquit0/Awesome-CV), [**Latex_CV**](https://github.com/muratcankaracabey/latex_cv), [**Mcdowell-CV**](https://github.com/dnl-blkv/mcdowell-cv).

## Contact

You are free to take my `.tex` file and modify it to create your own resume. Please don't use my resume for anything else without my permission, though!

If you have any questions, Click [here](https://www.linkedin.com/in/abhijit-dutta-3150a622/) to connect.

Good luck!





### How to tweak it?
- With minimum effort, you can use the [CV.tex](https://github.com/muratcankaracabey/latex_cv/blob/master/CV.tex) as it is provided with the high level functions such as ```\datedexperience```, ```\explanation```, ```\explanationdetail``` to add elements to your CV. You can create skill elements with ```\newcommand{\skillname{\createskill{<Skill Category>}{<explanation>}}}``` and finally create the list of skills with ```\createskills{<comma seperated skills list>}```. 
- You can also use it for your **cover letter** by just using
  ```
  \setcompanyname{GOOGLE INC.}
  \setcontactperson{Mr.Brown}
  \setclaimedposition{Junior Data Scientist} 
  \coverletter{ %
  <coverlettertext>
  }
  ``` 
  and deleting the rest of sections.
  

### Warning
- For Mac users, If you use TexShop, you need to locate the AwesomeFont in your file system and load to your system. It is most probably under ```/usr/local/texlive/2019/texmf-dist/fonts/opentype/public```. Just locate it and double-click install. Then you are good to go.

