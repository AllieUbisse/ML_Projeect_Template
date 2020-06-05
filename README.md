# Machine Learning Project Template
---
![](https://www.researchgate.net/publication/329266618/figure/fig1/AS:698144849399809@1543462111704/ML-lifecycle-adapted-from-Miao-et-al-6.png)<br>
image source: *www.researchgate.net/figure/ML-lifecycle-adapted-from-Miao-et-al-6_fig1_329266618* <br>
## Description
This repo serves as a machine learning template repository.<br>
Anyone is allowed to fork and manipulate according to their project structure.<br>
If you are New to Machine Learning or Github, then this is the best getting started repository for your project.<br>
**NB:** This repository will get better with time and I shall try to use **versions**. So feel free to open an Issue and request some enhencement, your suggestion is appreciated!<br>
<br><br>
Let me Walk you through, shall we?
<hr>

## What To Do 1st?
1. **Fork** the repository to your desired Account (**personal or Organization**).
2. **Clone** your forked Repo to your Local machine or  Server if you are a cloud person like me.
3. Rewrite your **ReadME.md** file, explaining your project. Since your ReadMe file will grow with your project, then here is a tool for you [stackedit online Markdown Editor](https://stackedit.io/) Sign-in with your github Account and it will save your changes.
4. This template is created with the github workflow in mind!
 - If this is your 1st time using github or you're not that comfortable with the github branch system, then Just use the **Master Branch**.
 - Else-If Github Geek like me:
    - Every machine learning stage is a Branch.
    - Branches you may like to create:
     - EDA branch (**analysis**)
     - Feature Engineering (**Engineering**) not all your features will work!
     - Preprocessing branch (**preprocessing**) 
     - Model training branch (**modeling**)
     - **Merge to master**---> every stage when completed or when you need to move to the next stage.
 
> Allie this is too much work!<br>
  I know and it will reduce code conflict or lost of files, Also it is the best way to learn.<br>
  Remember it is okay to make mistakes on your personal or small team Capstone projects, but the cooparate world will expect you to     understand things like **{branches, Pull request, issues, versioning, merging branches with  master branch}**
  Do not do it on your 1st project, just keep in mind that it is one of the best approach!
---

## Repo File Structure
Keep it Simple and clean, that will improve your project readability.<br>
**Let us Sort our Files**
1. **Data** --> Store your raw and preprocessed data here. if your csv or data file is less than 100MB (**Github's Current file size Limit**) else try **git-LFS**
2. **NoteBooks** --> Store All your Notebooks here. **Naming** is important for later use!, I will provide a detailed NoteBook, feel free to delete or make changes.
3. **Scripts** --> During Model Experiments, I find it best to complile my training script and run multimple model and go chill outside or take a walk. Let the Computer do its Job(**automated runs**). I will leave an example scripts to hypertune parameters and Cross validation.
4. **Output** --> All my scripts generates outputs, so I store results {model results, model-plots, model.pkl for later use}. I will  train few models using sample_train.py and save its **feature Impotance plot**, **model_crossval_score.csv** and the **model.pkl** along with the **train.csv and test.csv** . Just so you can be able to reproduce your runs if required.
5. **Images** --> I personaly line to Draw workflows or diagrams when explaining and this might be the best place to save your images and display then when doing your presentation to better explaning your findings and understanding.

---
**.gitignore**
Is one important file, make use of it to tell **git** what files to ignore during ```git add .```  and ```git commit```.<br>
Add files that might contain your personl info e.g IP address, API Keys, or just any files that you would not like the public to see.

*All the Best with your New Project!*
---
**MAY THE DATA BE WITH YOU, AMEN!**
