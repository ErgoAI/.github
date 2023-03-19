
# About ErgoAI

ErgoAI  is an advanced object-oriented platform for knowledge representation and
reasoning in an enterprise. It is a dialect of F-logic with numerous extensions,
including meta-programming in the style of HiLog, logical updates in the
style of Transaction Logic, and defeasible reasoning. Applications include
intelligent agents, Semantic Web, knowledge-based networking, ontology
management, integration of information, security policy analysis, and more.

ErgoAI is an enterprise-level extension of the well-known
[Flora-2 system](https://flora.sourceforge.net/).
After having been open-sourced by
[Coherent Knowledge Systems](http://coherentknowledge.com/),
ErgoAI subsumes Flora-2 for all purposes.

ErgoAI can interact with applications written in several major languages,
such as Python, Java, and C/C++; it can talk to databases and the Web; and
it has connectors to major data formats like JSON, XML, and CSV.

ErgoAI comes with comprehensive documentation, tutorials, and Example
Bank - a collection of advanced examples.

## Documentation, Examples, Help

### Getting Started

If you are new to ErgoAI, the best place to start is with the [FAQ](https://docs.google.com/document/d/1J_ASpGjDwgqMDzNgB-hqQC3keA8sIMZIHHs8gmJXG04/), 
[ErgoAI Tutorial](https://sites.google.com/coherentknowledge.com/ergoai-tutorial/),
and [ErgoAI Studio Manual](https://docs.google.com/document/d/1k_zNnvnEeWWuhvM4cn93i3nFi0VxKCdrNEypYtzhKEY/).  A basic knowledge of Prolog is helpful in
understanding ErgoAI.  Prolog tutorials and textbooks, for example [Learn
Prolog Now](http://www.learnprolognow.org/), can be found online.  As you advance to the next stage,
[ErgoAI Reasoner User's Manual](https://drive.google.com/file/d/1UzI2bV7DwSOWvmZBKZY-bhyEvbZVmCt-/view?usp=share_link) is a complete reference to the
system.  [Guide to ErgoAI Packages](https://drive.google.com/file/d/1SiIqWk5p6g15r-4pdtjI3b_sqCDFK1x4/view?usp=sharing) provides all the details you will
need to connect your ErgoAI knowledge base to the outside world.  
[ErgoAI Examples Bank](https://sites.google.com/coherentknowledge.com/ergoai-tutorial/example-bank-of-advanced-uses) provides runnable, annotated examples for a variety of
tasks using ErgoAI to augment the basic  examples found in ErgoAI Tutorial. 
[ErgoAI and XSB Users Forum](https://groups.google.com/a/coherentknowledge.com/g/ergoai-xsb-forum)
is the place to post questions, find
answers, share projects, and build collaboration. Finally, the XSB
manuals
are useful to those who need to supplement their knowledge bases with
low-level primitives that an experienced developer might need in some
cases.

### Tutorials

* [ErgoAI Tutorial](https://sites.google.com/coherentknowledge.com/ergoai-tutorial/):
  a set of lessons that introduces you to the fundamentals of authoring knowledge bases (a.k.a., rulebases) in ErgoAI. It includes  a number of worked examples with sample executable ErgoAI files. The tutorial provides an overview of the ErgoAI system from the very basics to more advanced topics.

* [Capturing Real World Knowledge in Ergo](https://sites.google.com/a/coherentknowledge.com/tutorial-capturing-real-world-knowledge):
this tutorial illustrates the process
of capturing real world knowledge in ErgoAI, with the goal of enabling
reasoning and question answering. The initial case study is drawn from the
lecture notes of a course on knowledge representation taught at Stanford
University in 2011.  The knowledge source is the California Driver's Handbook and the focus of the reasoning task is on knowledge that can be objectively and operationally used by the driver of a vehicle. Example files and step-by-step instructions for knowledge base creation are included.

### ErgoAI Manuals

* [ErgoAI Studio Manual](https://docs.google.com/document/d/1k_zNnvnEeWWuhvM4cn93i3nFi0VxKCdrNEypYtzhKEY/):
  Explains how to use the graphical UI and the Integrated Development Environment (IDE).  The IDE includes an interactive editor, explanation, and query windows, with navigation and debugging tools.

* [ErgoAI Reasoner User's Manual](https://drive.google.com/file/d/1UzI2bV7DwSOWvmZBKZY-bhyEvbZVmCt-/view?usp=share_link): Comprehensive reference manual including Ergo language syntax, reasoning engine, debugging tools and more.  For more experienced developers. General understanding of Prolog is a plus.

* [Guide to ErgoAI Packages](https://drive.google.com/file/d/1SiIqWk5p6g15r-4pdtjI3b_sqCDFK1x4/view?usp=sharing): Covers connectors from Ergo to other non-Ergo information sources and systems such as Java, SQL SPARQL, RDF/OWL, tabular data, XML, JSON, and more.

### FAQ and User's Forum

* [ErgoAI FAQ](https://docs.google.com/document/d/1J_ASpGjDwgqMDzNgB-hqQC3keA8sIMZIHHs8gmJXG04/): Frequently Asked Questions about ErgoAI.

* [Ergo and XSB Users Forum](https://groups.google.com/a/coherentknowledge.com/g/ergoai-xsb-forum):
A place for users to post questions and answers,
share interesting projects, and discuss ideas about knowledge based systems
in general. 

### Examples Bank

[ErgoAI Example Bank](https://sites.google.com/coherentknowledge.com/ergoai-tutorial/example-bank-of-advanced-uses)
provides users with runnable,
annotated examples that illustrate the various advanced features of Ergo
Suite. Each folder contains an "About" document explaining the example as well as the example files themselves with both data and rules.

The examples include:

* Java and Python integration
* Defeasible reasoning
* Connecting ErgoAI to SQL databases
* RDF and OWL import
* Querying SPARQL endpoints
* Importing tabular data
* Importing XML
* Working with JSON
* Doing input and output
* ErgoText and Federal Regulation W

This is a living document and more categories of examples will be
added. Suggestions from users on how to improve the examples or what
additional examples would be of interest as well as user-contributed
examples are welcome!  Please [email us](info@coherentknowledge.com) with
your thoughts and ideas. The examples could be both of the HOWTO type as
well as domain-specific (e.g., e-commerce, e-learning).

### XSB Manuals

These manuals are primarily for experienced developers who need low-level
features that are accessible via XSB.

* [The XSB System Volume 1: Programmer's Manual](https://xsb.sourceforge.net/manual1/manual1.pdf)

* [The XSB System Volume 2: Interfaces and Packages](https://xsb.sourceforge.net/manual2/manual2.pdf)


## Installation

The ErgoAI source code is split between two repositories:

* [Studio_fidji](../../../Studio_fidji) - a Java-based IDE code-named Fidji and
* [ErgoEngine](../../../ErgoEngine) - the ErgoAI inference engine, 
  language and data source
  interfaces, and everything else. The inference engine can be used without
  the IDE in the command window mode, and this is what is normally used
  when ErgoAI is embedded into a larger system.

#### Installing ErgoAI via an official rlease.

In addition, we provide stable releases for Linux, Mac, and Windows.
Installing a stable release is very easy:

* Make sure that the prerequisites for the installation are met. These prerequisites are described in Section 2.1 of [ErgoAI Reasoner User's Manual](https://drive.google.com/file/d/1UzI2bV7DwSOWvmZBKZY-bhyEvbZVmCt-/view?usp=share_link) and also in  [ErgoAI Tutorial](https://sites.google.com/coherentknowledge.com/ergoai-tutorial/ergoai-tutorial/home#h.p_ID_100).

* Download an appropriate release installer (a file named  `ergoAI_XXXXX.run` or `ergoAI_XXXXX.exe`, where XXXXX is the version number) and click your way through the installation.
These installers do not include the source code, so if one wants that then cloning ErgoAI repositories would still be necessary.

The full details are given in Section 2 of the [ErgoAI Reasoner User's Manual](https://drive.google.com/file/d/1UzI2bV7DwSOWvmZBKZY-bhyEvbZVmCt-/view?usp=share_link).

#### Installing ErgoAI from the sources.

Those who want to contribute to ErgoAI development would need to clone
[XSB](https://sourceforge.net/p/xsb/code/ci/git-origin/tree/) as well as the aforesaid ErgoAI repositories and compile the source code by themselves. This process is still straightforward for Linux, might be a bit more involved for Mac, and still more for Windows.

The main steps in this process are:

* Verification of prerequisites for the installation, as in case of the installation using an official release.

* Compiling XSB.

* Compiling the ErgoAI engine using a clone of the ErgoEngine repository

* Compiling the ErgoAI studio using a clone of the `Studio_fidji` repository.

The full details are given in Appendix A of [ErgoAI Reasoner User's Manual](https://drive.google.com/file/d/1UzI2bV7DwSOWvmZBKZY-bhyEvbZVmCt-/view?usp=share_link).

## Reporting Bugs

* Bugs in ErgoAI Reasoner: please report by creating a new issue in Github's Issue Tracker of the  [ErgoEngine](../../../ErgoEngine) repository.

* Bugs in the operations of the ErgoAI Studio: create a new issue in Github's Issue Tracker of the  [Studio_fidji](../../../Studio_fidji) repository.
