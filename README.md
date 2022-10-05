# Thesis on real time DDOS detection

## Tech Stack

**Tools :** Anaconda, DataSpell, Gogle Colab

**Library :** numba, fastai, tensorflow, scikit-learn

**Python :** Version 3.10

## To Run Locally

- Clone the project

```bash
  git clone https://github.com/MasumBhai/Thesis-on-DDOS.git
```

## Requirements

- anaconda must be installed

```bash
  conda update conda --all
```

- To use same virtualenv as authors (platform: win64)

```bash
  Download 'conda-spec-file-masum.txt' file from this repo's 'Project Configuration' folder
```

- Create a new virtualenv identical to authors

```bash
conda create --name masum_ml_env --file conda-spec-file-masum.txt
```

- check if conda virtualenv set up or not

```bash
conda env list
```

- activate the newly created environment

```bash
conda activate masum_ml_env
```

- Or, you can install author used packages into your own existing environment

```bash
 conda install --name <your_existing_env> --file conda-spec-file-masum.txt
```

- Conda packages are installed, now need to install pip packages (fastai, tensorflow, pytorch)

```bash
pip install --upgrade pip
pip install tensorflow
pip install torch torchvision torchaudio
pip install fastai 
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

