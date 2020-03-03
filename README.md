# HWX Title
hw description

For more details, please click [this link]() to view the slides.

### Start
Please create your own private Github repo to host your files. The repo name should be `hwX-blahblah`. And you repo link will be `https://github.com/<YOUR_GITHUB_ID>/hwX-blahblah`. After that, your **MUST** register `<YOUR_GITHUB_ID>` with [this form](), and add [TA's github account](#) to the repo collaborator, or we cannot receive your submission.

### Dataset


> ⚠️  ***Warning*** ⚠️  
> You should keep a copy of the dataset only in your local machine. **DO NOT** upload the dataset to this remote repository. If you extract the dataset manually, be sure to put them in a folder called `data/` under the root directory of your local repository so that it will be included in the default `.gitignore` file.

### Submission Format


### Evaluation on dev set
To evaluate your model on dev set, you can run the provided evaluation script provided in the starter code by using the following command.

# Submission Rules
### Kaggle Deadline

### All files submission Deadline


### Submission Format
Aside from your own Python scripts and model files, you should make sure that your submission includes *at least* the following files in the root directory of this repository:
 1.   `report.pdf`  
The report of your homework assignment. Refer to the "*Report Questions*" section in the slides for what you should include in the report.
 2.   `reproduce.sh`  
The shell script file for running your ASR model. The produced answer should be the same as the best submitted file on kaggle. If the score is not matched, you would lost the 5 points on kaggle.

We will run your code in the following manner:

    bash ./reproduce.sh $1 $2
where `$1` is the audio dataset directory (e.g. `data/DLHLP`), and `$2` is name of the output prediction csv file (e.g. `ans.csv` ).

### Packages
In [`pip-freeze.txt`](https://github.com/DLHLP2020/hw1-speech-recognition/blob/master/pip-freeze.txt) is a list of packages you are allowed to import in this assignment.

If you only use the machine in 計中, all packages are installed, you don't need to do any thing.

Note that using packages with different versions will very likely lead to compatibility issues when we reproduce your results. If you use your own computer, make sure that you install the correct version as listed in [`pip-freeze.txt`](https://github.com/DLHLP2020/hw1-speech-recognition/blob/master/pip-freeze.txt). E-mail or ask the TAs first if you want to import other packages.

### Remarks
- If your model is larger than GitHub’s maximum capacity (100MB), you can upload your model to another cloud service (e.g. Dropbox). However, your shell script files should be able to download the model automatically. For a tutorial on how to do this using Dropbox, please click [this link](https://docs.google.com/presentation/d/1SsIeIij9ZOEN_TGdbAS1oWcI6bT1uSTI6b5__u2wdDc/edit?usp=sharing).

# Q&A
If you have any problems related to HW1, you may
- Use TA hours (please check [course website](http://speech.ee.ntu.edu.tw/~tlkagk/courses_DLHLP20.html) for time/location)
- Contact TAs by e-mail ([dlhlp.ta@gmail.com](mailto:dlhlp.ta@gmail.com))
- Post your question in the comment section of [this post](https://www.facebook.com/groups/789568188219010)
