# CS 4824 / ECE 4424 HW 1 (Programming Portion)

# IF you want the assignment's solution, please add my wechat: fuji12345

Naive Bayes and Decision Trees [15 points]
General Instructions
Upload only those Python files t hat y ou h ave m odified fo r th is as signment. Th ese fil es sho uld include
naive bayes.py, decision tree.py, and crossval.py. You are welcome to create additional functions,
files, or scripts, and you are also welcome to modify the included interfaces for existing functions in the
given files if you prefer a different organization. For this homework, you will build two text categorization
classifiers: one using Naive Bayes and the other using decision trees. You will write general code for crossvalidation that will apply to either of your classifiers.
Data and starter code
In the HW1 folder, you should find t he 2 0newsgroups d ata s et ( also a vailable f rom t he o riginal source
http://qwone.com/~ jason/20Newsgroups/). This data set consists of newsgroup posts from an earlier
era of the Internet. The posts are in different categories, and this data set has become a standard benchmark
for text classification methods.
The data is represented in a bag-of-words format, where each post is represented by what words are
present in it, without any consideration of the order of the words nor their counts.
We have also provided a unit test class in tests.py, which contains unit tests for each type of learning
model (see https://docs.python.org/3/library/unittest.html for more information about unittest). These
unit tests may be easier to use for debugging in an IDE like PyCharm than the iPython notebook. A successful implementation should pass all unit tests and run through the entire iPython notebook without issues.
You can run the unit tests from a *nix (Unix-like OS) command line with the command.
