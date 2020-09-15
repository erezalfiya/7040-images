Ereze's file transfer

git clone https://github.com/erezalfiya/7040-images.git

add a file
git add readme.txt

Commit the changes to the git repositor

Git commit readme.txt

push files to Erez's Server

git push -f


To refresh my copy from what is on the Github server:

git pull -f



from the command line:


root:sdk-base# cd /home/fsmith
root:fsmith# ls
c  depot  Desktop  Documents  Downloads  get_dpdk_files  get_kernel_and_lib_modules  marvell  Music  n  Pictures  Public  Templates  Videos
root:fsmith# git clone https://github.com/erezalfiya/7040-images.git
Cloning into '7040-images'...
warning: You appear to have cloned an empty repository.
root:fsmith# cd 7040-images/
root:7040-images# vim readme.txt
root:7040-images# git commit readme.txt
error: pathspec 'readme.txt' did not match any file(s) known to git.
root:7040-images# ls
readme.txt
root:7040-images# git add readme.txt
root:7040-images# vim readme.txt
root:7040-images# git commit readme.txt
[master (root-commit) 8043b2f]  new file:   readme.txt add a readme file to the Repostiory
 1 file changed, 15 insertions(+)
 create mode 100644 readme.txt
root:7040-images# git push -f
Username for 'https://github.com': erezalfiya
Password for 'https://erezalfiya@github.com':
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 385 bytes | 385.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/erezalfiya/7040-images.git
 * [new branch]      master -> master
root:7040-images#
 

