# batch-gen-templates-for-cp

A tool which generates a batch of templates for each problem automatically in competitive programming

## Intro

This is a convenient tool for setting up files before a programming contest using simple batch command.

By inputting in the **contest name** and the **last alphabet of the problems**, it auto generate a folder and the desired templates.

For example, if I input **Codeforces Round #790 (Div. 4)** and **H**, it generates a folder named "Codeforces Round #790 (Div. 4)" and inside there are files "A.cpp", "B.cpp", "C.cpp", "D.cpp", "E.cpp", "F.cpp", "G.cpp", "H.cpp".

## Preparation

1. Download these files.

2. Edit the **gen.bat**: Replace **template_directory** with the directory of your template file.

3. Add the directory of gen.bat to the **environment variable**.

## User Guide

1. Open a terminal and change the directory to the folder where you want to start a contest.

2. Type gen and then follow the instructions.

3. Enjoy!

## To do list

- Fetch number of the problems of a contest automatically.

- Create 1 problem per file.
