# 42cursus
my 42cursus 16/09/2023

Libft

Pdf
https://cdn.intra.42.fr/pdf/pdf/105099/en.subject.pdf
https://github.com/pasqualerossi/42-Cursus-Tester

https://github.com/pasqualerossi/Libft#h-header

All
https://github.com/hanshazairi/42-libft
https://www.asidesigned.com/project-libft.html

+
https://github.com/TakuyaSama/42_Cursus_Libft
https://gitlab.com/42-Istanbul/libft
https://github.com/rchallie/libft/blob/master/Makefile


Tester
https://github.com/Abaker-Hype/42-Cursus-Tester/tree/main

Tester Libft, Get_Next_Line or Printf

1. Copy and paste the following in shell -
git clone https://github.com/Abaker-Hype/42-Cursus-Tester.git


Note: make sure to git clone this tester outside of your Libft/Get_Next_Line/Printf Folder, not in it.

2. cd into the 42-Cursus-Tester and type in the following in shell -
vim script.sh


3. In the vim script.h file, under the #Libs locations (3rd Row Down from the top of the script.h file), change the path description to your own Libft, Get_Next_Line or Printf folder.

4. Then exit vim (wq) and type in the shell the following command -
make <the project name that your working on>

to run the 42-Cursus-Tester, eg. 
make printf

5. Check your results and good luck!
If you get a KO or S in this tester, then write the following to find out where exactly in the function/program that is occuring:
make <project name> <function_name> detail
