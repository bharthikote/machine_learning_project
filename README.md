# machine_learning_project
This is first ML project








Creating Conda environment
```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```

```
pip install -r requirements.txt
```
To add files to git
```
git add .
```
OR 
```
git add <file_name>
```

Note: To ignore file or folderfrom git we can write name of file/folder in .gitignore file
To check git status
```
git status
```

To check all version maintained by git 
```
git log
```

To create version or commit all changes  y git
```
git commit -m 'message'
```

To send version/changes
```
git push origin main
```
To setup CI/CD pipeline in Heroku we need three information
1. HERROKU_EMAIL = bharathsharath0221@gmail.com
2. API_KEY = rnd_anlMvWxzTFjJbHa38YtX88yQtWnk9e05278af40a
3. APP_NAME = ml-regression-app

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lower case

To list docker images
```
docker images
```
