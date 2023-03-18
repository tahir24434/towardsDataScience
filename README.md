# *** Setup on SageMaker ***
bash

##### Download github/fastai/fastsetup 
`git clone https://github.com/fastai/fastsetup.git`

##### Create fastaiCourse environment
`conda create -n fastai` 
`conda activate fastai`

##### Download and install mamba 
`./setup_conda.sh`

##### Download and install fastai
`mamba install -c fastchan fastai`

##### Adding environment to Jupyter notebook
`conda install -c anaconda ipykernel`

`python -m ipykernel install --user --name=fastaiCourse`

##### To Setup fastaibook
`mamba install -c fastchan fastbook`

`conda install ipywidgets`

