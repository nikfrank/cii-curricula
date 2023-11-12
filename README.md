# courses for code israel

## itinerary

 - preamble
 - course listings
   - dedication
   - topics
   - lesson spec
   - runtime
 - schedule
   - development
   - operation


### preamble

these are the courses I wish I had when I learned how to be a web developer.
Each should be possible to learn entirely on one's own, with a friend or group, or in an organized classroom.
To this end, the documentation should be terse and give direction, and the tests should run first to give meaningful feedback and second to be complete.
The topics are fundamental tools for operating machines, not specific frameworks or runtimes.
Our goal here is to be capable of thinking our way through the next problem.

### course listings

 - commands (bash)
 - functions (javascript)
 - the internet (cloud dev in cdk)

#### commands (bash)

##### dedication

This is a course I was asked to write many years ago for a bright learner much wiser than his years.
It is based on what I've learned from teachers and coworkers.
Operating your machine effectively will serve you in any role and ensure your value to your team.
What we learn here should deprecate most GUIs that your parents ask you how to use.


##### topics

 - bash basics
   - using your command prompt to:
   - move, make, remove, ... files
   - understand the state of the system and its permissions
   - read and edit files
   - install and run programs   
 - write scripts to automate our tasks
   - pipe programs together
 - use git to track work
 - network via http(s) and ssh
 - use various CLI tools to operate:
   - databases
   - cloud services
   - programs we write (npm)
 - tricks of the trade
   - jq
   - flags on everything!


##### lesson spec

... copy paste the topics and flesh out ...

eg

   - use git to track work
     - git is just emailing diffs around for you! (preamble)
     - git init
     - git status
     - git add
     - git diff
       - `-w`
       - `HEAD~1`
       - `commit/branch commit/branch`
       - ` ... > some-diff.patch
       - git apply
     - git commit
       - :wq!
       - `-am`
     - git branch
       - `-a`
     - git remote
       - add, remove
       - `-v`
     - git push
        - `-f`
     - git pull
     - git rebase
     - git merge
     - git log
     - git stash, apply
     - git reset
       - `--hard`
     - git fetch
     - git ls-files
     - git mv
     - github, pull requests
     - .git
     - githooks
     - git tag
     - fixing broken git states 
     
     


##### runtime

bash running in a *nix compatible terminal

what we write can be tested by checking the resultant state of the directory

once we get to writing scripts, those scripts can be run by automatic tests

ideally, a session can be intercepted in order to interactively teach keyboard shortcuts on the command line
however, this has proven non-trivial, so for now these topics will likely be taught with gifs!

some github lessons might be on the honor system.



#### functions (javascript)

##### dedication

This is the newest version of a course I wrote for a wonderful class of mutineers I had the privilege of learning with.
It is inspired by learnyounode
Each test should be learned repeatedly as a kata for thorough results.


##### topics

 - installing and running js (browser, node, etc)
 - repl
 - inputs
   - implicit types
   - partial evaluation
 - outputs
   - NPEs
   - destructuring output
   - curried functions
 - console.log
 - routines
   - loops
   - array .map .reduce .filter
   - non-termination
   - nesting
   - recursion
   - algorithms I learned in school
   - data structures I learned in school and actually use
 - purity in code
   - impurity in code
 - naming variables and why it matters
   - data is a lt commander, not a variable name
 - prototypes and lexical scoping
 - new syntax and when it rocks
   - when it doesn't
   - old syntax
 - tricks with objects, arrays, strings, numbers, parentheses, functions
   - one time use fns
 - patterns
   - middleware
   - convention over configuration
   - single source of truth
   - single responsibility
   - optimizing for deletability
 - proxies and why you don't need a proxy
 
 

##### lesson spec

... js tactics from github, with focus on the topics listed above ...



##### runtime

this should run in the command line with jest as an automated continuous testing env

tests should have two sets of cases

 - tests with meaningful outputs
 - tests which are comprehensive




#### the internet (cloud dev in cdk)

##### dedication

This course is dedicated to the dreamers.
You have ideas in your imagination, let this course give you the tools to operate your imagination in Feynman's straightjacket.
Nothing will stop you - nobody can tell you no.


##### topics

 - http(s) networking
   - DNS
   - certificates
 - REST
   - GET to the browser
   - POST to the server
   - the rest of the verbs
 - APIs
   - paths
   - verbs
   - lambdas
     - with node_modules
     - with layers
     - triggered by ...
   - databases
     - S3
       - files
       - hosting
       - uploads
     - dynamo
       - indices
       - queries
   - other cloud services
 - permissions
   - security
   - KMS
 - environments
   - regions
   - staging / prod
 - automation!
   - cfn
   - cdk
 - testing

##### lesson spec

... needs work ...

##### runtime

aws cli, aws accounts required







### schedule
   - development
   - operation