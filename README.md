# test
Hi ye ek random  repository banaya  aur Readme.md file banaya
is #test  hash se bold type mein aaya
repository folder hota
commit save hota
aur commit ke time message likhte kuch

<br>
ab isme kuch changes kiye taaki history mein dikh ske   aur ye niche wale command git bash p chalaye ya terminal p v chala skte
git --version                isse version ka pta chalta
pwd                          se current working directory ka 
<br>
git config --global user.name "Shubh-Prateek"
git config --global user.email "shubhprateekalt@gmail.com"

ye isse git configuration hota taaki konse account mein changes krrhe wo pata chale
ye global hi krrhe local v krskte agar bahut se github account ho to   aur yaha pe github wala user name likha

<br>
d drive jaha ye folder hai  wha jaake status dekha git status aur fir clone kiya pura copy
git clone https://github.com/Shubh-Prateek/test.git

<br>
abhi humara readme.md stage hai to koi v change krrhe to vs code M krke dikah rha
<br>
to basically git init se bolta ki git dekh rha is folder ke staged changes ko
aur git add filename   ya git add . bolta sbhi staged ko dekho
abhi itna save krke add. aur commit krdete

<br>
jabhi nayi file banao to usko staged krdo aut commit  

<br> to hamne abhi ek index.html file banayi aur wo untracked aarhi uar ye wali modified

<br>
abhi agar h1 create kiya index.html m to git ko pata nhi chalega wo untracked hi bolega kyuki isko commit nhi kiya

<br>
git commands wale mein se command dekhlo kuch

<br>
abhi humlog direct ek folder se git init krenege taaki ek naya git repo khul sake mtlb git uspe dhyaan de changes ka
gitdemo folder ke andar ek nayi folder bana rhe  cd .. se parent folder p aaye mtlb gitdemo p
wha p mkdir se naaya folder banaya LocalRepo krke

<br>
to ab folder ke andar gye aur git init kiya   isse ek .git waali file bani jo ki ls -a list all file se pta chala
usme ek naya html file banaya git add . kiya aur fir commit kiya par push krne se pehle ye krna pdega
<br>
hame is folder ko github p v daalna to github p naya repository banaya jaise localrepo
readme ko nhi initialse krenge nhi to  iss folder mein v banana pdega
<br>
git remote add origin link  mtlb hum ek remote repo add krna chahte jiska naam origin  hai aur link jo jahagithubrepo
<br>git remote -v se verify krte 
<br>git branch   check krke baatate konsi branch hai
<br>git branch -M main    to rename the branch   kyuki pehle master hua krta tha par github ne policies mein change k
<br>git push origin main

<br>
to ye hua 
Dell@DESKTOP-F8ELQB2 MINGW64 /d/gitdemo/LocalRepo (master)
$ git remote add origin https://github.com/Shubh-Prateek/localrepo.git

Dell@DESKTOP-F8ELQB2 MINGW64 /d/gitdemo/LocalRepo (master)
$ git remote -v
origin  https://github.com/Shubh-Prateek/localrepo.git (fetch)
origin  https://github.com/Shubh-Prateek/localrepo.git (push)
verify hogya ki shi jagah remote set

<br>
Dell@DESKTOP-F8ELQB2 MINGW64 /d/gitdemo/LocalRepo (master)
$ git branch
* master          bol rha  master branch

Dell@DESKTOP-F8ELQB2 MINGW64 /d/gitdemo/LocalRepo (master)
$ git branch -M main           rename kiya kyuki git ka ab main use krte master ke jagah

Dell@DESKTOP-F8ELQB2 MINGW64 /d/gitdemo/LocalRepo (main)
$ git push origin main   fir main branch mein push
Enumerating objects: 3, done.  
ab repo mein ye dikhayega
<br>
 git push -u origin main    agr baar baar same hi branch mein update kr rhe to usko upstream krke usko set krdiya 
 taaki agla push usi mein jaaye
 