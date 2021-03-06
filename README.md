# Bootcamp-FA21

## Setup

Everyone should make an account on Github (https://github.com/). Then, follow the instructions for your OS.

### Linux, Mac
1. Most likely you already have git installed. If you don't, see https://git-scm.com/book/en/v2/Getting-Started-Installing-Git or ask Jatin.
2. Open terminal.
3. Run: `git config --global user.name "<Your name>"`
4. Run: `git config --global user.email <Your email>`
5. Run `cd Desktop`
5. Run: `git clone https://github.com/AIDA-UIUC/Bootcamp-FA21.git`
6. Download conda from https://www.anaconda.com/products/individual-d
7. Run: `conda install -c pytorch pytorch`. Then run `pip install -r requirements.txt`.
8. Run: `jupyter notebook`
9. Execute the code in `setup_test.ipynb` and make sure it worked
10. Create a new git repository on Github. You can do this from the website.
11. Run: `git remote set-url origin <new git URL>`
12. Run: `git add -u`
13. Run: `git push`

### Windows
1. Download git for windows from https://git-scm.com/downloads
2. Open the git bash program
3. Run: `git config --global user.name "<Your name>"`
4. Run: `git config --global user.email <Your email>`
5. Run: `cd Desktop && touch hi.txt`
6. See if `hi.txt` exists in your Desktop. If you've never used terminal before, this shows that terminal is another interface to your computer. Until now you've probably used what is called a GUI (graphical user interface) like Chrome and Finder to do things. Terminal is a more expansive, text-based way to do things with your computer.
7. Run: `git clone https://github.com/AIDA-UIUC/Bootcamp-FA21.git`
8. Download conda from https://www.anaconda.com/products/individual-d
9. Open the anaconda prompt program
10. Run: `cd Desktop/Bootcamp-FA21`
11. Run: `conda install -c pytorch pytorch`. Then run `pip install -r requirements.txt`.
12. Run: `jupyter notebook`
13. Execute the code in `setup_test.ipynb` and make sure it worked
14. Create a new git repository on Github. You can do this from the website.
15. Run: `git remote set-url origin <new git URL>`
16. Run: `git add -u`
17. Run: `git push`
