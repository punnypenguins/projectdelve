+++
title = "COVID.SI"
tags = ["distributed computing" "biology" "chemistry" "medical"]
+++

## CITIZEN SCIENCE AND THE FIGHT AGAINST THE CORONAVIRUS (COVID.SI)

View the project [**here**](https://covid.si/en/).

### Overview

“CITIZEN SCIENCE AND THE FIGHT AGAINST THE CORONAVIRUS” is an open project by a collective of good-willed researchers and volunteers, who with to contribute a stone in the mosaic of the full picture of SARS-CoV-2 and COVID-19, with the sum of our work, knowledge and experience. The group is lead by dr. Črtomir Podlipnik and dr. Marko Jukić, experts with years of experience in computer supported molecular modelling, pharmaceutical chemistry and chemo/bioinformatics.

With the help of likeminded volunteers we were able to develop our own technology, which allows distributed computing of molecular docking. The technology is based on a piece of software, which connects the user’s computer to a central server, which distributes a part of our molecular library (currently around 10.000.000 molecules) and collects the docking results, which are computed using RxDock. After analysis of the docked molecules, the results are a list of compounds which have a high potential to bind to a therapeutic target (in our case viral proteins). The next phase is checking the availability of the appropriate compounds and organising in vitro and in vivo testing together with other research groups. The set of unavailable molecules could then be sent to other researchers to be synthesised. In the optimal scenario we would identify molecules interesting for the pharmaceutical industry. In the short term this projects aim is preliminary research, which can help with the development with a cure.

Our solution for distributive computing is open source, and the software for distributive computing (except for [RxDock](https://www.rxdock.org/)) was written from the ground up by our team. The source is available on [GitHub](https://github.com/COVID-si).

### Runs on:
- Linux
- MacOS
- Windows
