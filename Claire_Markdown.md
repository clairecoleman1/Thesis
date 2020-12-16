My work:

I had downloaded and installed Git previously:

I ran 'git version' on terminal and the output was 'git version 2.28.0'

I made a folder called thesis and added my files to the folder.

I ran 'cd thesis' and 'ls' and my output was:

thesis_16328283:README.txt		thesis_16328283_fastqc_out
thesis_16328283:test_data		thesis_16328283_fastqc_script.py
thesis_16328283:trim_out		thesis_16328283_trimm_script.py

And I will add this markdown document to it when it completed.

Next I ran 'git init' and got the following output:

'Reinitialized existing Git repository in /Users/clairecoleman/thesis/.git/'

I then did 'git add' followed by the name of each file in the thesis folder

and ran git status

which gave this output:

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   thesis_16328283:README.txt
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-01.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-02.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-03.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-04.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-05.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-06.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-07.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-08.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-09.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-10.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-11.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-12.fastq
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-01.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-02.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-03.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-04.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-05.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-06.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-07.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-08.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-09.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-10.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-11.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-12.fastq.trimmed
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-01_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-01_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-02_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-02_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-03_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-03_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-04_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-04_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-05_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-05_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-06_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-06_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-07_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-07_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-08_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-08_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-09_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-09_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-10_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-10_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-11_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-11_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-12_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-12_fastqc.zip
	new file:   thesis_16328283_fastqc_script.py
	new file:   thesis_16328283_trimm_script.py

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store

----------------------------------------------------------------------
    
    
I actually realised after this that I named the files incorrectly..so deleted, them renamed them, and ran this again: interestingly, this was the output I got - git really does track *every* change! Interesting insight..
    
    
git add ... and git status again
    
Output:
    
    
    On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   16328283:README.txt
	new file:   16328283:test_data/exampleHIV.interleaved.part-01.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-02.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-03.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-04.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-05.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-06.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-07.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-08.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-09.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-10.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-11.fastq
	new file:   16328283:test_data/exampleHIV.interleaved.part-12.fastq
	new file:   16328283:trim_out/exampleHIV.interleaved.part-01.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-02.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-03.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-04.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-05.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-06.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-07.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-08.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-09.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-10.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-11.fastq.trimmed
	new file:   16328283:trim_out/exampleHIV.interleaved.part-12.fastq.trimmed
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-01_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-01_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-02_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-02_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-03_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-03_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-04_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-04_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-05_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-05_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-06_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-06_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-07_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-07_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-08_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-08_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-09_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-09_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-10_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-10_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-11_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-11_fastqc.zip
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-12_fastqc.html
	new file:   16328283_fastqc_out/exampleHIV.interleaved.part-12_fastqc.zip
	new file:   16328283_fastqc_script.py
	new file:   16328283_trimm_script.py
	new file:   thesis_16328283:README.txt
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-01.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-02.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-03.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-04.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-05.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-06.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-07.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-08.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-09.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-10.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-11.fastq
	new file:   thesis_16328283:test_data/exampleHIV.interleaved.part-12.fastq
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-01.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-02.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-03.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-04.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-05.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-06.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-07.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-08.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-09.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-10.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-11.fastq.trimmed
	new file:   thesis_16328283:trim_out/exampleHIV.interleaved.part-12.fastq.trimmed
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-01_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-01_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-02_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-02_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-03_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-03_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-04_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-04_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-05_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-05_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-06_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-06_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-07_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-07_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-08_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-08_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-09_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-09_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-10_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-10_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-11_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-11_fastqc.zip
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-12_fastqc.html
	new file:   thesis_16328283_fastqc_out/exampleHIV.interleaved.part-12_fastqc.zip
	new file:   thesis_16328283_fastqc_script.py
	new file:   thesis_16328283_trimm_script.py

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	deleted:    thesis_16328283:README.txt
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-01.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-02.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-03.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-04.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-05.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-06.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-07.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-08.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-09.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-10.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-11.fastq
	deleted:    thesis_16328283:test_data/exampleHIV.interleaved.part-12.fastq
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-01.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-02.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-03.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-04.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-05.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-06.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-07.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-08.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-09.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-10.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-11.fastq.trimmed
	deleted:    thesis_16328283:trim_out/exampleHIV.interleaved.part-12.fastq.trimmed
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-01_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-01_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-02_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-02_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-03_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-03_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-04_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-04_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-05_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-05_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-06_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-06_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-07_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-07_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-08_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-08_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-09_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-09_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-10_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-10_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-11_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-11_fastqc.zip
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-12_fastqc.html
	deleted:    thesis_16328283_fastqc_out/exampleHIV.interleaved.part-12_fastqc.zip
	deleted:    thesis_16328283_fastqc_script.py
	deleted:    thesis_16328283_trimm_script.py

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store

----------------------------------------------------------------
    
    
Next I ran:
    
    git commit -m "Add initial version of thesis code." 

You just have to add a comment of some sort..
    
and then I ran:
    
    git log
    
And my output was:
    
commit 7ee1622673b493befc97c6edd391a5e2747ff9e1 (HEAD -> master)
Author: Claire Coleman <clairecoleman123@hotmail.com>
Date:   Wed Dec 16 14:50:36 2020 +0000

    Add initial version of thesis code.

----------------------------------------------------------------
    
    
After this I ran:
    
    git diff
    
And my output was:
    
    
    diff --git a/thesis_16328283:README.txt b/thesis_16328283:README.txt
deleted file mode 100644
index f3eae9e..0000000
--- a/thesis_16328283:README.txt
+++ /dev/null
@@ -1 +0,0 @@
-I downloaded fastqc and trimmomatic and used python scripts to read in data from test data set and used these packages to create output files called fast qc out and trim out.
diff --git a/thesis_16328283:test_data/exampleHIV.interleaved.part-01.fastq b/thesis_16328283:test_data/exampleHIV.interleaved.part-01.fastq
deleted file mode 100644
index 2b3f402..0000000
--- a/thesis_16328283:test_data/exampleHIV.interleaved.part-01.fastq
+++ /dev/null
@@ -1,1876 +0,0 @@
-@chr1-106238/1
-CCCTAAGACCCTTTTAGTCAGTGTGGAAAATCTCTAGCACTCTCTCCAGGGGCTTCTTCCATTTTTTGTACACATCTCCAAGGCTTTGAAAGAGTGCGCA
-+
-@=@F(FFFHHGFFIJJJJJCIGJIGFIJIG(JHFIH:E2I)GJFJI0IGJJJ?IDGJIED=DCGHJ8H>=C?DADBFD<BCH9DDC+C>CDBD5DCE&@:
-@chr1-106238/2

--------------------------------------------------------------------------
    
    I then logged into my github account in browser which I had previously created..
    
    I made a new repository and called it 'thesis'
    
    After this I followed the steps on the webpage:
    
    I ran these commands in terminal:
    
    
   git remote add origin https://github.com/clairecoleman1/Thesis.git
   git branch -M main
   git push -u origin main 
    
    
After this I got this output:
    
    Enumerating objects: 56, done.
Counting objects: 100% (56/56), done.
Delta compression using up to 4 threads
Compressing objects: 100% (56/56), done.
Writing objects: 100% (56/56), 9.53 MiB | 3.07 MiB/s, done.
Total 56 (delta 11), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (11/11), done.
To https://github.com/clairecoleman1/Thesis.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
    
    
-------------------------------------------------------------------
    
    Then I opened another browser window and used this link:
    
    
    
    https://github.com/clairecoleman1/Thesis
    
    
    
    And it brought me to my repository which I had created.
    
    
    (Please note that there are two of each file type due to confusion over what the files     should be called..)..BUT it's all there! 
    
    
   
    