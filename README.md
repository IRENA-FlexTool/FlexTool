![MicrosoftTeams-image](https://user-images.githubusercontent.com/84900647/176460507-0bc578b5-b347-482f-82e3-abfe1fd0bbfb.png)

IRENA FlexTool is an energy and power systems model for understanding the role of variable power generation in future energy systems. It performs capacity expansion planning as well as operational planning.

This is IRENA FlexTool v3.0 in beta testing. Report any bugs or difficulties in the [issue tracker](https://github.com/irena-flextool/flextool/issues). Previous version of IRENA FlexTool can be found in https://www.irena.org/energytransition/Energy-System-Models-and-Data/IRENA-FlexTool.

User guide and documentation are under development, but the current version can be found [here](https://irena-flextool.github.io/flextool/).

## Main alternatives to use IRENA FlexTool

[Use a browser](#-connecting-to-irena-flextool-server) IRENA FlexTool can be accessed with a web browser if you have an account for an IRENA FlexTool server. No public servers available at the moment.
- It is possible to setup a local server and then use a browser to access that server. See https://github.com/irena-flextool/flextool-web-interface
- Install Spine Toolbox and run IRENA FlexTool as a Spine Toolbox project. This gives you the graphical user interface of Spine Toolbox. https://github.com/Spine-project/Spine-Toolbox
- It is also possible to define all the data in Excel and execute IRENA FlexTool workflows that takes the data and scenarios from Excel and returns results in another Excel file. This functionality is still under development.

## Connecting to IRENA FlexTool server

Instruction will be added later

## Setting up local server

See https://github.com/irena-flextool/flextool-web-interface#installation

## Installing Spine Toolbox and IRENA FlexTool on local computer

- Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (or Anaconda)  [Can be ignored if already installed]
- Start anaconda prompt
- `conda create -n flextool python=3.8`  [Also possible to use existing, up-to-date, Spine Toolbox environment]
- `conda activate flextool`
- `conda install git`
- cd to a directory into which both FlexTool and SpineToolbox will make their own folders
- `git clone https://github.com/irena-flextool/flextool`
- `git clone https://github.com/Spine-project/Spine-Toolbox.git`
- `cd SpineToolbox`
- `pip install --upgrade pip`
- `pip install -r requirements.txt`
- `python -m spinetoolbox`
- Open FlexTool3 project in Spine Toolbox (Choose FlexTool folder)

In case of problems when installing Spine Toolbox, more instructions are available at: https://github.com/Spine-project/Spine-Toolbox#installation

## Using Excel as an interface

Functionality yet not available.
