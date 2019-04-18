# SOEN6611 project final report
# Team name : Team C
#Team Members
| name |
| :------: |
| Wenhui Guo |
| Jing Yang |
| Hengyang An |
| Xintong Chen |
| Shenghong Yan |
# Repository structure
*copy and paste code both in config_coverage.xml and config_mutation.xml to every project's pom.xml*

**specify the targetClasses and targetTests in each project in the pitest config in configuration tag.**

```
SOEN6611
│   README.md  
|
└───configurations // codes need to be added in project's pom.xml
│     config_jacoco.xml  // jacoco plugin config
│     config_mutation.xml //pitest plugin config
│   
└───raw_data //raw data of five project in 5 dictionary
|    └───commons-lang
|    |       └───jacoco-ut
|    |       └───pit-reports
|    └───jspwiki
|    |       └───jacoco-ut
|    |       └───pit-reports
|    └───commons-net
|    |       └───jacoco-ut
|    |       └───pit-reports
|    └───commons-codec
|    |       └───jacoco-ut
|    |       └───pit-reports
|    └───collections  
|           └───jacoco-ut
|           └───pit-reports   
└───processed_data // data after processed
|    └───commons-lang
|    |       └───lang_class_level_metric.csv
|    |       └───lang_project_level_metric.csv
|    └───jspwiki
|    |       └───jspwiki_class_level_metric.csv
|    |       └───kspwiki_project_level_metric.csv
|    └───commons-net
|    |       └───net_class_level_metric.csv
|    |       └───net_project_level_metric.csv
|    └───commons-codec
|    |       └───codec_class_level_metric.csv
|    |       └───codec_project_level_metric.csv
|    └───collections  
|            └───collections_class_level_metric.csv
|            └───collections_project_level_metric.csv  
└───data_analysis_script // data analysis sciprt use R
    └───commons-lang              
```
