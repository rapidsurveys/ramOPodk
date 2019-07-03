# ramOPodk: Rapid Assessment for Older People XLSform and Xform survey instruments

[![DOI](https://zenodo.org/badge/138555975.svg)](https://zenodo.org/badge/latestdoi/138555975)

The Rapid Assessment Method for Older People (RAM-OP) is a rapid assessment method for measuring the nutritional status and needs, and other related factors that affect older people in humanitarian situations. It includes a questionnaire, a sampling method, and software for data analysis. It needs to be finalised and tested to produce guidelines. It will allow humanitarian workers to gather evidence on the nutritional vulnerability of older people in emergencies and plan the response accordingly.

Developed by [HelpAge International](www.helpage.org) in collaboration with [Valid International](http://www.validinternational.org) and [Brixton Health](http://www.brixtonhealth.com), and with funding from [Humanitarian Innovation Fund](http://www.elrha.org/hif/home/), the method is quick because it requires a sample size of just 192 and the process can be achieved in just two weeks, including training and data collection, entry and analysis.

Using the standard questionnaire developed for RAM-OP, the following survey instrument in [XLSform](http://xlsform.org/en/) and [Xform](https://en.wikipedia.org/wiki/XForms) standard for [Open Data Kit (ODK)](https://opendatakit.org) has been developed as an alternative electronic data collection tool for use in RAM-OP surveys.

## Usage

### 1. Using ODK Aggregator or other similar ODK servers
The [XLSForm](http://xlsform.org/en/) can be uploaded to a remote server-based ODK Aggregator or other ODK servers such as [ONA](https://ona.io/home/), [SurveyCTO](https://www.surveycto.com), [KoBoToolbox](https://www.kobotoolbox.org) and the like. The form is validated and then converted into XML format which can then be retrieved from the server into mobile devices as blank forms.

### 2. Convert to XML and transfer to mobile devices via USB cable connection
The XML version of this form can then be transferred to the mobile devices (into the device's `odk` folder) via local USB connection. This can be done by following the instructions [here](https://docs.opendatakit.org/collect-forms/#loading-forms-directly). The associated media files for the forms (found in the folder called `media` in this repository) will also need to be transferred to the mobile device. This can be done by following the instructions [here](https://docs.opendatakit.org/collect-forms/#loading-form-media). 

## Author
Ernest Guevarra

## License
MIT License
