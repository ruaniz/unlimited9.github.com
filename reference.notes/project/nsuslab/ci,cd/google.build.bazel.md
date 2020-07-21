# Installing Bazel on Ubuntu

## Using the binary installer

#### Step 1: Install required packages
sudo apt install g++ unzip zip  
>sudo apt-get install openjdk-11-jdk  

#### Step 2: Run the installer
'download the Bazel binary installer named bazel-<version>-installer-linux-x86_64.sh from the Bazel releases page on GitHub.' : https://github.com/bazelbuild/bazel/releases  

chmod +x bazel-3.4.1-installer-linux-x86_64.sh
./bazel-3.4.1-installer-linux-x86_64.sh --prefix=/apps/bazel/3.4.1  

vi ~/.bashrc
```
...
export PATH="$PATH:/apps/bazel/3.4.1/bin"
```


## appendix

#### reference.site

* Installing Bazel on Ubuntu  
https://docs.bazel.build/versions/3.4.0/install-ubuntu.html  