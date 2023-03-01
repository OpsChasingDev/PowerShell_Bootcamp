# INTRODUCTION
Welcome!  The Lesson Plan below contains a curriculum of what content will be covered during the course of this multi-session class on PowerShell.  Hands-on demonstrations throughout will help build a true sense of competance and comfort level with leveraging PowerShell in any situation.  No prior experience is required, and by the end of it, you will have deep and practical knowledge of one of the most powerful system administration tools known to the technical community.


# LESSON PLAN

### WHAT IS POWERSHELL
- Brief history on where PowerShell comes from, what it's used for, and where it is now
  - PowerShell is NOT cmd (ping vs Test-NetConnection)
  - Jeffrey Snover stressed the importance of a shell-based management tool
  - .NET and C#
- Windows PowerShell vs PowerShell (core)

### GETTING STARTED WITH USING POWERSHELL
- Installing PowerShell
- Installing Windows Terminal
- Setting up the aesthetics of your shell (this is actually important)
- What is PowerShell capable of doing for us and why do we care?
  - makes bulk administration and automation easy for operations engineers and systems administrators
  - built-in providers
  - built on a highly capable framework
  - easy-to-use documentation and help system
  - cross-platform
  - highly secure
  - broad spectrum of community-driven modules
  - we get to work with objects!
- SysAdmins are NOT Developers
  - PowerShell acts as a programming language, but how we use it is not like a developer (normally)
  - if this is the first computer language you're really learning, do not be afraid! (and you picked one of the best)

### DISCOVERABILITY
- the cmdlet structure
- finding cmdlets to use
- finding help on specific cmdlets
- finding help on larger concept topics
- finding modules

### VARIABLES
- setting and calling variables
- seeing what variables can hold
- environment variables
- working with objects in variables

### DATA TYPES
- string
- int
- float
- double
- bigint
- bool
- .NET data types

### WORKING WITH OPERATORS
- arithmetic
- logical
- comparison

### WORKING WITH COLLECTIONS
- what is a collection?
- arrays (lists)
- using index to access members of a list
- hash tables (dictionaries)
- using key to access members of a hash table

### OBJECTS AS THE FOUNDATION OF POWERSHELL'S POWER
- what makes objects special (revisit ping vs Test-Netconnection)
- ipconfig vs Get-NetIPAddress
- identifying what kinds of objects you're working with
- seeing object members
  - Get-Member
  - dot-sourcing technique
- properties vs methods
- the pipeline
- how objects link through the pipeline
- sorting and filtering output
- significance of '$_'

### DATA STREAMS
- standard output
- error output
- warning output
- host output
- verbose output
- suppressing output using $null

### REMOTING
- enabling PowerShell remoting
- implicit remoting using cmdlet parameters
- interactive remoting
- session remoting
- retrieving information from remote sources
- a note on scoping
- passing variables to remote sessions
- running scripts on remote computers

### WORKING WITH PERSISTENT DATA
- thus far, we have only dealt with volatile memory
- generic export/import cmdlets
  - Out-File
  - Get-Content
- common data structures (csv, xml, json)
- cmdlets used for importing and exporting data structures

### INTRODUCTION TO SCRIPTING
- a PowerShell script in its most basic form
- execution policy
- no more shortcuts or aliases
- a note on tidiness, indentation, and overall readability

### TOOLS FOR SCRIPTING
- PowerShell ISE
- VSCode
- version control with git
- Github

### LOOPING AND LOGIC CONSTRUCTS
- if-then
- foreach
- for
- while
- do-while
- switch
- (more on the try/catch/finally loop later on)

### FUNCTIONS
- why make functions?
  - eliminate copy/paste coding
  - formalize scripts for portability and reusability
- creating functions
- calling functions
- allowing user input with parameters
- adding common PowerShell engine support to functions
- begin/process/end

### MORE ON PARAMS
- parameter attributes
  - mandatory
  - specifying data types
  - validateset/validatepattern
- enabling pipeline input
- parameter sets

### ADDING HELP
- in-line comments (ILC)
- comment-based help (CBH)
- parameter descriptions

### ERROR HANDLING
- global variable $Error
- digging into what the error data stream holds (guess what, it's objects!)
- terminating vs non-terminating errors
- controlling errors with try/catch/finally
- controlling actions upon encountering errors

### MODULES
- creating our own modules
- a note on scoping
- using script-level variables in modules