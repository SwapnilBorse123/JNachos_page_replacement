### Project Title ###
JNachos v1.0

### Getting Started ###
Download the JNachos source code from Prof. Patrick McSweeney's page.
http://www.cis.syr.edu/~pjmcswee/cis657/

### Prerequisites ###
Install Java and set the JAVA_HOME environment variable.
You can use a Java IDE like Netbeans, Eclipse, IntelliJ

### Installing ###
1) Install Java
2) Install Java IDE
3) Download JNachos zip file from Prof. Patrick McSweeney's page.
4) Unzip and import the Java project in the IDE.


### SWAP FILE ###
Created using the JavaFileSystem class.

### Page Replacement Algorithm Used ###
FIFO : First-In-First-Out (FIFO) Replacement. On a page fault, the frame that has been in memory the longest is replaced. FIFO is not a stack algorithm. In certain cases, the number of page faults can actually increase when more frames are allocated to the process.

### RAM SIZE ###
64

### PAGE FAULT EXCEPTION ###
* Program starts with all pages of the executable program written in swap space.
* When a page fault occurs, page fault handler finds the first free available slot on the RAM and copies the new page on that slot.
* If the RAM is full, the handler evicts the page that has been the longest on the RAM.
* The process's memory is cleared from the RAM and swap file once it exits.

### Versioning ###
Used Bitbucket for version control. Project developed on master branch.

### Contribution ###
Prof. Patrick McSweeney (EECS Department Syracuse University)
Ankita Gadage (EECS, Masters in Computer Science, 2017-2019)
Swapnil Borse (EECS, Masters in Computer Science, 2017-2019)

### Acknowledgements ###
Prof. Patrick McSweeney
Three Easy Pieces OS Textbook
Galvin