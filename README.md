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

### Other commands
```
git checkout branch
git log --oneline
```
## Download files from gdrive
```pip install gdown```

Gdrive link: https://drive.google.com/file/d/FILE_ID/view?usp=sharing 

Replace **FILE_ID** with the real ID 

```gdown https://drive.google.com/uc?id=FILE_ID```

or

```gdown https://drive.google.com/uc?id=FILE_ID -o output_file_name```
