# jenkinsfile_notepad_plus_plus
Custom Language settings for Jenkinsfiles with Groovy

First check to see if http://docs.notepad-plus-plus.org/index.php?title=User_Defined_Language_Files list has been updated with a Jenkinsfile option.

If not, you can import mine. It includes the following:
- pipeline
- agent 
- post 
- stage 
- stages 
- steps 
- script 
- (params. 
- currentBuild.
- abs  
- any  
- append  
- asList  
- asWritable  
- call  
- collect  
- compareTo  
- count  
- div  
- dump  
- each  
- eachByte  
- eachFile  
- eachLine  
- every  
- find  
- findAll  
- flatten  
- getAt  
- getErr  
- getIn  
- getOut  
- getText  
- grep  
- immutable  
- inject  
- inspect  
- intersect  
- invokeMethods  
- isCase  
- join  
- leftShift  
- minus  
- multiply  
- newInputStream  
- newOutputStream  
- newPrintWriter  
- newReader  
- newWriter  
- next  
- plus  
- pop  
- power  
- previous  
- print  
- println  
- push  
- putAt  
- read  
- readBytes  
- readLines  
- reverse  
- reverseEach  
- round  
- size  
- sort  
- splitEachLine  
- step  
- subMap  
- times  
- toInteger  
- toList  
- tokenize  
- upto  
- waitForOrKill  
- withPrintWriter  
- withReader  
- withStream  
- withWriter  
- withWriterAppend  
- write 
- writeLine
- environment 
- options 
- parameters 
- triggers 
- stage 
- tools 
- input 
- when 
- try 
- if 
- else 
- catch 
- def
- unstable 
- failure 
- cleanup 
- mail to 
- subject 
- body 
- deleteDir 
- checkout 
- $class: 
- branches: 
- doGenerateSubmoduleConfigurations: 
- extensions: 
- submoduleCfg: 
- userRemoteConfigs: 
- name: 
- description: 
- choice 
- string
- #!groovy

How to use?
1.  Open notepad++
2.  Select "Language"
3.  Select "Define your language"
4.  Select "Import..."
5.  Browse to the file location where you downloaded the notepad_plus_plus_jenkins-groovy.xml file.
6.  Hit okay.
7.  Close Notepad++
8.  Open Notepad++
9.  Open a Jenkinsfile
10. Select "Lanugage"
11. Select "Jenkinsfile"

