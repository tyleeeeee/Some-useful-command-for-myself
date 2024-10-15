# Some useful command for myself

## Conda environment

### Create a new environment

`conda create --name newenv python=3.9`

### Check enviroment list

`conda env list `

### Delete the enviroment

`conda env remove --name newenv`

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

`pip install gdown`

Gdrive link: https://drive.google.com/file/d/FILE_ID/view?usp=sharing

Replace **FILE_ID** with the real ID

`gdown https://drive.google.com/uc?id=FILE_ID`

or

`gdown https://drive.google.com/uc?id=FILE_ID -o output_file_name`

## Install Conda using terminal

Go to https://repo.anaconda.com/archive/, my version is Anaconda3-2024.06-1-Linux-x86_64.sh

```
wget https://repo.anaconda.com/archive/Anaconda3-2024.06-1-Linux-x86_64.sh

bash Anaconda3-2024.06-1-Linux-x86_64.sh
```

如果已經安裝 conda 但沒有顯示的話，可以執行
`source ~/.bashrc`

## Check architecture

E.g. x86_64

`uname -u`
