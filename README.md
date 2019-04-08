# LifeCycleQA
The data and the code for the paper titled "Declarative Question Answering over Knowledge Bases containing Natural Language Text with Answer Set Programming"
Download the code from: https://drive.google.com/file/d/1Lz_jm3d6mbkl1zza9N44JXbPw4s3aRUu/view?usp=drive_web

## Running the demo:

1. create a conda environment<br>
conda create -n lifecycle python=3.6

2. activate the environment<br>
conda activate lifecycle

3. Install clingo ( for Answer Set Programming)<br>
conda install -c potassco clingo

4. Install allennlp <br>
git clone -b qr_theories <url>https://github.com/OyvindTafjord/allennlp.git</url> <br>
INSTALL_TEST_REQUIREMENTS=true scripts/install_requirements.sh <br>
You can test your installation with ./scripts/verify.py .

5. export PYTHONPATH=<path_to_allennlp><br>
For e.g., export PYTHONPATH=/home/arindam/workspace/allennlp

6. Navigate to the directory inside the NatCyc code that contains the file "qa_demo.py"<br>

7. For the demo run : python qa_demo.py 
For sample questions see the /data/ folder inside the NatCyc directory. The demo version is cached, so you cannot write a new question.

