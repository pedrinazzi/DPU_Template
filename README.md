<!---

This template is intended to be used for describing UnifiedViews plugins as README.md. 

- Copy this README.md to root directory for the plugin to be described.  

- Replace <<descriptive information>> with proper values.

- If no values are available, replace <<descriptive information>> with 'N/A'.

- Use <BR> tag for creation of multi-line cells (in case the length of text exceeds the width of page, it is wrapped automatically to multi-line cell).

- Enclose each configuration parameter name with ** for highlighting the text as bold. 

- Add '(optional)' to Type of input or output if it is not mandatory (all inputs and outputs are mandatory by default). 

- Delete these template comments after the completion of the document.  

-->

# <<DPU name>> #
----------

###General###

|                              |                                                               |
|------------------------------|---------------------------------------------------------------|
|**Name:**                     |<<DPU name>>                                                   |
|**Description:**              |<<DPU description>>                                            |
|                              |                                                               |
|**DPU class name:**           |<<name of main DPU class (that implements DPU interface)>>     | 
|**Configuration class name:** |<<name of POJO configuration class>>                           |
|**Dialogue class name:**      |<<name of class for dialogue to be displayed in GUI for user>> | 

***

###Configuration parameters###

|Parameter                        |Description                             |                                                        
|---------------------------------|----------------------------------------|
|<<configuration parameter name>> |<<configuration parameter description>> |

***

### Inputs and outputs ###

|Name                |Type       |DataUnit                         |Description                        |
|--------------------|-----------|---------------------------------|-----------------------------------|
|<<input or output>> |<<i or o>> |<<FilesDataUnit or RDFDataUnit>> |<<description of input or output>> |


***

### Version history ###

|Version            |Release notes                                   |
|-------------------|------------------------------------------------|
|<<version number>> |<<release notes and changes from last version>> |                                


***

### Developer's notes ###

|Author            |Notes                 |
|------------------|----------------------|
|<<author's name>> |<<developer's notes>> | 

