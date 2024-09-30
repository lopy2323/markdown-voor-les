# Les 4: Publiceren van code naar Github
## Maak een repository en link deze
>repo betekent repository
Eerst maak je een .git folder met 
```
git init
```
daarna moet je een repo maken op Github
dan link je die repo met:
```
git remote add origin https://github.com/USERNAME/REPO_NAME.git
```
nu moet je een branch aanmaken:
```
git branch -M main
```
### Hier na kunnen we files uploaden door middel van CMD
je add je file naar de commit group met:
```
git add FILENAME.FILE_EXTENTION
```
hierna kan je de uitvoeren commit met:
```
git commit -m "MESSAGE"
```
nu kunnen we een branch aan maken met:
```
en upload je het met 
```
git push -u origin main
```
### Wat ik vaker ga gebruiken van Markdown:
Notes Maken 