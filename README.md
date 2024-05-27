# Some useful command for myself

## Conda environment

### Create a new environment 
```conda create --name newenv python=3.9```
### Check enviroment list
```conda env list ```
### Delete the enviroment
```conda env remove --name newenv```


## Git

### Push file to branch
```
git add .
git commit -m "Add files"
git push origin branchname
```
Then create a pull request in github

### Other command
```
git checkout branch
git log --oneline
```
## Download files from gdrive
```
pip install gdown
```
### Example 

Gdrive link: https://drive.google.com/file/d/18n_3V1rywgeADZ3oONO0DsuuS9eMW6sN/view?usp=sharing 

Gdrive ID: 18n_3V1rywgeADZ3oONO0DsuuS9eMW6sN
```
gdown https://drive.google.com/uc?id=18n_3V1rywgeADZ3oONO0DsuuS9eMW6sN
```
