# Thesis on real time DDOS detection

## Tech Stack

**Tools :** Anaconda, DataSpell, Gogle Colab

**Library :** numba, fastai, tensorflow, scikit-learn

**Python :** Version 3.7

## To Run Locally

- Clone the project

```bash
  git clone https://github.com/MasumBhai/Thesis-on-DDOS.git
```

### Create a new virtualenv identical to authors (platform: win64)

- anaconda must be installed

```bash
  conda update conda --all
```

#### Approach 01 (from .yml file)
- Download `masum_ml_env.yml` file from `Project Configuration` folder
```bash
conda env create -f masum_ml_env.yml
```
#### Approach 02 (from .txt file)
- Download 'conda-spec-file-masum.txt' file from this repo's 'Project Configuration' folder

```bash
conda create --name masum_ml_env --file conda-spec-file-masum.txt
```
#### Approach 03 (install all packages inside existing env)

```bash
 conda install --name <your_existing_env> --file conda-spec-file-masum.txt
```

#### Activate the environment
- check if conda virtualenv set up or not

```bash
conda env list
```

- activate the newly created environment

```bash
conda activate masum_ml_env
```

#### Conda packages are installed, now need to install pip packages


```bash
pip cache purge
conda install numba
conda install jupyter
conda install opencv
conda install tqdm matplotlib plotly
conda install -c conda-forge scikit-learn-intelex
conda install dask
conda install xgboost
conda install nb_conda
pip install --upgrade pip
pip install torch torchvision torchaudio
pip install fastai
conda install -c anaconda beautifulsoup4
conda install seaborn
pip uninstall pyzmq
pip install pyzmq
pip uninstall pandas
pip install pandas
pip install ipykernel
conda install cudnn
pip install --upgrade --no-deps --force-reinstall tensorflow
pip install keras
conda install theano pygpu
conda install -c conda-forge shogun
```

## Related Works

Here are some related projects (list will be made soon)

[Explore Our Literature Review](https://drive.google.com/drive/folders/1ot7xlnyCaPxMbYm9Ohn9ob61JzsKRA-B?usp=sharing)

## Optimizations

- Data-Preprocessing (working on it)

## Documentation

[Documentation](https://masumbhai.me)

- Saving my machine learning environment

```bash
 conda list --explicit > conda-spec-file.txt
```

## Acknowledgements

- Thesis
  supervisor [@Brigadier general Abdur Razzak](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
- Professor [@Dr. Mahbubur Rahman](https://mist.ac.bd/department/cse/facultyMembers/dr_md_mahbubur_rahman-2)
- Thesis co-supervisor [@Raiyan Rahman](https://github.com/matiassingers/awesome-readme)

## Authors

- [@Abdullah Al Masum](https://masumbhai.me)
- [@Abdul Al Emon](https://github.com/emon49)
- [@Shad Reza](https://github.com/shadreza)

## Feedback

If you have any feedback, please reach out to me at abdullahmasum6035@gmail.com
