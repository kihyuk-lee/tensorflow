# tensorflow install guide (Online)

### 0. DEV Conf.
>###### os : win7 - 64bit

### 1. Install Anaconda (Tensorflow compatible Python 3.5) → Anaconda : ver3-4.2.0
>###### Downlaod URL : https://repo.continuum.io/archive/.winzip/
>###### py3.5 : Anaconda3-4.2.0-Windows-x86_64.exe

### 2. pip upgrade (command line) 
>###### python -m pip install --upgrade pip

### 3. install tensorflow
>###### pip install tensorflow 

### 4. test 
>###### python
<pre><code>
import tensorflow as tf
import sys
sys.version
</code></pre>

### 5. run Jupyter Notebook
>###### run : jupyter notebook 
>###### check token : jupyter notebook list



# tensorflow install guide (Offline)

### 0. DEV Conf.
>###### os : win7 - 64bit

### 1. Install Anaconda (Tensorflow compatible Python 3.5) → Anaconda : ver3-4.2.0
>###### Downlaod URL : https://repo.continuum.io/archive/.winzip/
>###### py3.5 : Anaconda3-4.2.0-Windows-x86_64.exe

### 2. python package download (by online)
>###### pip install -d . tensorflow

### 3.Downloaded file move to offline PC

### 4. install tensorflow (offline)
>###### pip install --no-index --find-links=. tensorflow


# tensorflow with Hive (JDBC Connection)
### 0. offline pc

### 1. Download JayDeBeApi
>###### pip install -d . jaydebeapi

### 2-1. Download VC++ 14.0 Compiler (Online Install)
>###### Donwload URL : http://landinghub.visualstudio.com/visual-cpp-build-tools
>###### Click "Download Visul C++ Build Tools 2015"

### 2-2. Download VC++ 14.0 Compiler (Offline Install)
>###### Offline Donwload Guide : https://social.msdn.microsoft.com/Forums/ko-KR/8417efbd-7776-4ceb-903e-e427d7923d5e/visual-studio-community-015-?forum=vsko
>###### command window : visualcppbuildtools_full.exe /layout (from Online PC)
>###### move pakcage file to offline  

### 3. Install 1 &2
>###### pip install --no-index --find-links=. jaydebeapi
>###### visualcppbuildtools_full.exe (with Admin Auth)

### 4. test
>###### python
<pre><code>
import jaydebeapi
</code></pre>

# tesorflow with Google Datalab
### 1. Google Cloud Platform : https://datalab.cloud.google.com/
>###### Create Account 

### 2. Create New Project

### 3. Create VM
> ###### MANUAL : https://cloud.google.com/datalab/docs/quickstarts

> ###### gcloud shell
<pre><code>
$ gcloud projects list
$ gcloud config set core/project <b>project_id</b>
$ gcloud config set compute/znoe <b>zone</b> #https://cloud.google.com/compute/docs/regions-zones/regions-zones#choosing_a_region_and_zone
$ datalb create <b>instance-name</b> #ex) inst01
</code></pre>

### 4. run Code
> ###### web preview
> ###### create new notebook

