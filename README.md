Pashto-NLP
==============

This project is initiated by Nangarhar University, Faculty of Computer Science. The main objective of the project is to contribute improving the Pashto natural language processing. In this project language resources (lexicon, annotated corpora) will be developed. Similarly, algorithms used in language processing will be also provided for the Pashto language.

Instructions for Contributors
-----------------------------

### 1. Clone the project with Git

Clone the main repository and rename it's remote handle as «rmtstream»:

``` bash
git clone https://github.com/csfacultynu/Pashto-NLP.git
cd IMPRO-3.SS15
git remote rename origin rmtstream
```

Fork the repository on GitHub and add the fork as remote in your local clone:

```bash
export GH_USER=shakir774 # configure your GitHub username here
git remote add $GH_USER https://github.com/$GH_USER/Pashto-NLP.git
```

Add the forks of your collaborators as:

```bash
git remote add someone https://gethub.com/someone/Pashto-NLP.git
git remote add someoneother https://gethub.com/someoneother/Pashto-NLP.git
git fetch --all # fetches the remote indexes
```

### 2. Import the project into your IDE

We recommend using [Pycharm](https://www.jetbrains.com/pycharm/), although the project should (at least in theory) also work with [IntelliJ IDEA](https://www.jetbrains.com/idea/) using [python plugin] (https://plugins.jetbrains.com/idea/plugin/631-python).

### 3. Code Contribution

Please work on each task or subtask in a separate branch (called *tast branch* or *feature branch*).

When you develop your code, please follow the workflow below:

  1.  Collaborate within the group. Create small commits and exchange by push/pull-ing from the forks.
  1.  Make sure you frequently pull and rebase `«upstream»/master` onto the `dev_{system}` branch.
  1.  Once the algorithm is unit-tested and works, [squash all small commits](http://gitready.com/advanced/2009/02/10/squashing-commits-with-rebase.html) into logical commits with clear content description (e.g. one for the algorithm and one for the uni-test).
  1.  [Create a pull request](https://help.github.com/articles/creating-a-pull-request) from your feature branch to the `«upstream»/master`.
  1.  After reviewing the code, we will merge your code into `«upstream»/master`.
  
