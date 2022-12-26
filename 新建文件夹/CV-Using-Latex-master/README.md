<h1 align="center">
  <a href="https://github.com/whatsupabhijit/CV-Using-Latex" title="Documentation">
    <img alt="Abhijit Dutta CV" src="https://github.com/whatsupabhijit/CV-Using-Latex/blob/master/images/profilpicture.png" width="200px" height="200px" style="border-radius: 50%"/>
  </a>
  <br />
  Abhijit Dutta CV and Cover Letter
</h1>

<p align="center">
  LaTeX template for job application
</p>




<div align="center">

  [**Edit Résumé**](https://www.overleaf.com/project/5f3d4d771cf30f0001c5fe7a)

  <a href="https://twitter.com/EddieNit">
    <img alt="Example CV" src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fimg.shields.io%2Fbadge%2Fc" />
  </a>  

  <a href="https://github.com/whatsupabhijit/CV-Using-Latex/blob/master/CV.pdf">
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


|[![Résumé](https://raw.githubusercontent.com/whatsupabhijit/CV-Using-Latex/master/screenshots/CV.PNG)](https://raw.githubusercontent.com/whatsupabhijit/CV-Using-Latex/master/CV.pdf) |


#### Cover Letter

You can see [PDF](https://github.com/whatsupabhijit/CV-Using-Latex/blob/master/coverLetter.pdf)

[![Cover Letter](https://raw.githubusercontent.com/whatsupabhijit/CV-Using-Latex/master/screenshots/coverLetter.PNG)](https://raw.githubusercontent.com/whatsupabhijit/CV-Using-Latex/master/coverLetter.pdf) |

## Quick Start

* [**Edit Résumé on OverLeaf.com**](https://www.overleaf.com/project/5f3d4d771cf30f0001c5fe7a)
* [**Edit Cover Letter on OverLeaf.com**](https://www.overleaf.com/project/5f3d4d771cf30f0001c5fe7a)

**_Note:_ Above services do not guarantee up-to-date source code**


## How to Use

#### Requirements

A full TeX distribution is assumed.  [Various distributions for different operating systems (Windows, Mac, \*nix) are available](http://tex.stackexchange.com/q/55437) but TeX Live is recommended.
You can [install TeX from upstream](http://tex.stackexchange.com/q/1092) (recommended; most up-to-date) or use `sudo apt-get install texlive-full` if you really want that.  (It's generally a few years behind.). 

You can also install MiKTex for windows. Open the cv.tex file and cv.cls file. When the cv.tex file window is active choose typeset as XeLaTex and press the green triangle button to generate the pdf.

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


If you don't know Latex, then you can check the guide under latex folder, index.html file. Alternatively there is a zipped version also with name ``latex.tar.gz``

You can download the file instead and unzip the tar file with below command -
```bash
$ tar latex.tar.gz
```

Credit: I have taken this guide from [NASA's website](https://www.giss.nasa.gov/tools/latex/ltx-tar.html). 


One pre-requisite for all of this commands to run in windows also is - You need to install CMDER and run all this commands not from cmd but from CMDER.

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
  

## Warning
- For Mac users, If you use TexShop, you need to locate the AwesomeFont in your file system and load to your system. It is most probably under ```/usr/local/texlive/2019/texmf-dist/fonts/opentype/public```. Just locate it and double-click install. Then you are good to go.


## Resume Checklist

✅ The resume should be 1 page.  

✅ Add github link, linkedin link and your online portfolio link.

✅ In each bullet point in technical experience mention always how much impact it had to the company. Numbers speak a lot. 

✅ Better to include the keywords from the job description of the company for which you are applying.

✅ Don't add summary/objective in your CV. Its just waste of your space. Also you are limitting to the roles.

✅ “I” should not be used.

✅ Grammatical mistakes and Typos are strict No No.
