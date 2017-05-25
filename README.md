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
>###### Donwload URL : https://www.microsoft.com/ko-kr/download/details.aspx?id=48159

### 3. Install 1 &2
>###### pip install --no-index --find-links=. jaydebeapi
>###### BuildTools_Full.exe (with Admin Auth)

### 4. test
>###### python
<pre><code>
import jaydebeapi
</code></pre>

