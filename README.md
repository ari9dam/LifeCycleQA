# LifeCycleQA
The data and the code for the paper titled "Declarative Question Answering over Knowledge Bases containing Natural Language Text with Answer Set Programming"
Download the code from: https://drive.google.com/open?id=1U9MCalIe5i9ApLBGIHT-TbRRZRbzY2sm

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

4. navigate to the directory that contains the file "qa_demo.py"<br>

5. for the demo run : python qa_demo.py 

