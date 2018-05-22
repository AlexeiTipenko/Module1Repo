    1  ls
    2  history
    3  pwd
    4  cd first-repo
    5  ls
    6  nano readme.md
    7  git status
    8  git add -A
    9  git status
   10  git commit -m "My first commit"
   11  git config --global user.email "alexeitipenko@cmail.carleton.ca"
   12  git config --global user.name "Alexei Tipenko"
   13  git commit -m "My first commit"
   14  nano readme.md
   15  git commit -m "Added another line to readme.md"
   16  git commit
   17  git add -A
   18  git commit
   19  history
   20  history > module1_ex4.2.md
   21  git status
   22  git add -A
   23  git commit -m "Added module1_ex4.2.md file"
   24  pandoc -o module1_ex4.2.docx module1_ex4.2.md
   25  git status
   26  git add -A
   27  git commit -m "Added .docx version of module 1 exercise 4.2 markdown file"
   28  git log
   29  q
   30  git checkout -b NewBranch <f62f019ce98771a1ce4900fad1c24984ddfe357f>
   31  git checkout -b NewBranch f62f019ce98771a1ce4900fad1c24984ddfe357f
   32  git status
   33  ls
   34  nano ExampleFile1.md
   35  nano ExampleFile2.md
   36  nano ExampleFile3.md
   37  git status
   38  git add -A
   39  git status
   40  git commit -m "Added 3 new example markdown files for module 1 exercise 4.3 question 5"
   41  git status
   42  history
   43  history > module1_ex4.3.md
   44  ls
   45  git checkout master
   46  git branch
   47  git merge NewBranch
   48  git remote add origin https://github.com/AlexeiTipenko/Module1Repo.git
   49  git push -u origin master
   50  git push origin NewBranch
   51  ls
   52  nano ExampleTextFile1.txt
   53  ls
   54  git status
   55  git add -A
   56  git commit -m "Added new text file (and exercise 4.3 .md file)"
   57  git status
   58  git push
   59  history
   60  history > module1_ex4.4_ex4.5.md
