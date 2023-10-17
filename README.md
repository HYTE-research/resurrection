# resurrection

This code repository is related to an article published in New Media and Society. 

Further theorization on *resurrecting* tweets is available here: 

Harju, A. A., & Huhtamäki, J. (2021). ‘#hellobrother needs to trend’: Methodological reflections on the digital and emotional afterlife of mediated violence. *International Review of Sociology*, 31(2), 1–32. [https://doi.org/10.1080/03906701.2021.1947951](https://doi.org/10.1080/03906701.2021.1947951)

Resurrecting tweets is a step forward from *rehydrating* tweets, that is, using a list of tweet identifiers to recollect the full tweet data. 

Rehydration is the only option for sharing Twitter data that complies with Terms of Service. However, under the Elon Musk administration, the practices for accessing and sharing have been in a constact change. 

## Getting ready

This process is compatible with MacOS, Linux and UNIX. Minor changes are needed in Windows environment.

Run the following commands in a terminal.

Create a virtual environment for the project:

  python -m venv .venv

Activate the environment:

  source .venv/bin/activate

Install the needed packages:

  pip install -r requirements.txt

## Usage

Open the Jupyter notebook. You can for example run a local Jupyter server on the command line or install and use Anaconda or Microsoft Visual Code.

Move to work with the notebook: [notebook_hellobrother.ipynb](notebook_hellobrother.ipynb).