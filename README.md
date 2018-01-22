# Awesome-OpenSees  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Join the chat at https://gitter.im/awesome-opensees/Lobby](https://badges.gitter.im/awesome-opensees/Lobby.svg)](https://gitter.im/awesome-opensees/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Analytics](https://ga-beacon.appspot.com/UA-112803115-1/github-repo-readme)](https://github.com/Hanlin-Dong/awesome-opensees)

Hi, this is a curated list of OpenSees resources. You may find something awesome that gives you a better experience using or developing OpenSees. Learn more on [OpenSees official wiki website](http://opensees.berkeley.edu/wiki/index.php/Main_Page).

This awesome-list project is inspired by the project [awesome](https://github.com/sindresorhus/awesome). However, as OpenSees itself is rapidly growing, most of the related resources are not so mature. Therefore, the resources listed here may suffer from some limitations, or still under development but inspiring. The author doesn't take any responsibility for the accuracy of anything listed. You should judge whether to use them by yourself.

Contributing to the list is encouraged. Please read the [contribution guidelines](contributing.md) before making pull requests. If you have problems on contributing, please click on the `PRs Welcome` badge above. 

If you find the listed resources useful or rubbish, please move to the `issues` board and vote for them. Each resource listed has an own issue with the lable `vote`. Please give a :+1: or :-1: to the first comment. Also, don't forget to `star` this repository. The authors are grateful to your kind contribution.

## Contents
* [Graphical Processor](#graphical-processor)
* [Stand-Alone Editor](#stand-alone-editor)
* [Editor Plugin](#editor-plugin)
* [Visualiser](#visualiser)
* [API](#api)
* [Procedure and Snippet](#procedure-and-snippet)
* [Tutorial and Example](#tutorial-and-example)
* [Blog and Community](#blog-and-community)

## Graphical Processor
User-friendly graphical pre- and post-processors for OpenSees.

* [GiD+OpenSees](http://gidopensees.rclab.civil.auth.gr/) - An OpenSees add-on for [GiD](https://www.gidhome.com/download/), A general graphical pre/post processor. (Windows, MacOS & Linux)
* [Build-X](https://www.buildx4opensees.eu/) - An Expert Tool for Seismic Analysis and Assessment of 3D Buildings with OpenSees. (Windows only)
* [NextFEM](http://www.nextfem.it/it/home/) - A user friendly Finite Element Analysis program, which can be used alone or to be a pre- or post- processor for several widely used FEM programs (i.e. OOFEM, SAP2000, Midas GEN, OpenSees, ABAQUS/CalculiX, Zeus-NL, and others). (Windows only)
* [OpenSees Navigator](http://openseesnavigator.berkeley.edu/) - A stand-alone Matlab interface allowing users to quickly create models, perform analysis, and look at the results. (Windows & MacOS, `Matlab Compiler Runtime` needed)
* [ETO (Etabs To OpenSees)](http://www.dinochen.com/article.asp?id=149) - A pre- and post-processor which is able to import `.s2k` file generated by ETABS. (Windows only, in Chinese)

## Stand-Alone Editor
Stand-alone editor programs just for OpenSees code.

* [Cypress Editor](http://cypress.hrshojaie.com/en-us/default.aspx) - A better editor for who does OpenSees code. (Windows only)

## Editor Plugin
OpenSees plugins for existing welcomed text editors.

* [Sublime-OpenSees](https://packagecontrol.io/packages/OpenSees) - A [Sublime Text](https://www.sublimetext.com/) plug-in for the OpenSees extension language of TCL. (Windows, MacOS & Linux)
* [OpenSEESAutoComplete](https://github.com/Hanlin-Dong/OpenSEESAutoComplete) - An auto-complete plugin to make writing OpenSees file easier on [Notepad++](https://notepad-plus-plus.org/). (Windows only)
* [Atom Language Package](https://github.com/jamesmaguire/language-opensees) - An [Atom](https://atom.io/) text editor package that provides syntax highlighting and auto-completion for OpenSees tcl scripts.
* [VSCode Language Support](https://github.com/jamesmaguire/vscode-language-opensees) - An extension that adds rich language support for OpenSees flavoured TCL language in [Visual Studio Code](https://code.visualstudio.com/).

## Visualiser
Simple scripts that help visualise OpenSees models or results.

* [OpenSees Model View](https://github.com/jamesmaguire/opensees-model-view) - A Python package that can be used to visualise your OpenSees model as the tcl file is written.
* [OpenSees 3D Visualisation](https://github.com/jamesmaguire/opensees-3d-visualisation) - A Python script that reads OpenSees simulation input and output files to create a 3D visualisation of your displaced model.
* [OpenSees Model Plotter Matlab](https://github.com/gerardjoreilly/OpenSees-Model-Plotter-Matlab) - A Matlab-based plotter for models developed in OpenSees.

## API
Application Programming Interfaces that call OpenSees.

* [OpenSeesAPI](https://github.com/nassermarafi/OpenSeesAPI) - A Python package that is used to write OpenSees tcl scripts quickly.
* [OpenSeesAPI.m](https://github.com/andrewdsen/OpenSeesAPI.m) - An OpenSees API for MATLAB.
* [Script Generation via Templates](https://github.com/ucgmsim/OpenSees_script-generation) - An inspiring example of using Python template engine [Jinjia2](http://jinja.pocoo.org/) to generate massive tcl scripts.
* [Node-OpenSees](https://github.com/lge88/node-opensees) - A [Node.js](https://nodejs.org/) bind for OpenSees. (Not maintained, just for inspiration)

## Procedure and Snippet
Reuseable procedures and snippets. All the files are stored in the `tcl` directory.

## Tutorial and Example
Official and unofficial tutorials and examples in a variety of languages.

* [Official Getting Started Manual](http://opensees.berkeley.edu/wiki/index.php/Getting_Started) - A brief introduction to get started.
* [Official Examples Collection](http://opensees.berkeley.edu/wiki/index.php/Examples) - All the examples provided by the OpenSees developing group.
* [Getting Started Tutorial in Chinese](http://www.hanlindong.com/2017/opensees-bootstrap/) - A simple but powerful tutorial for brand new users. (in Chinese)

## Blog and Community
Personal blogs, communities or forums where you can find help.

* [Official Community](http://opensees.berkeley.edu/community/index.php) - The official community where you can get help from software developers.
* [dinochen.com in Chinese](http://dinochen.com/) - Blog of Dr. Chen Xue Wei, Senior Associate, WSP Hong Kong Ltd.

## Contributing
If you are interested in contributing, please read the [contribution guidelines](contributing.md). You can either contribute to the list, or contribute to the tcl codes. Your efforts are highly appreciated by the authors.

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Hanlin Dong](http://www.hanlindong.com) has waived all copyright and related or neighboring rights to awesome-opensees. This work is published from: Mainland China.
