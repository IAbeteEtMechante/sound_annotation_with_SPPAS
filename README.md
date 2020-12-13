# sound_annotation_with_SPPAS
This is a quick description on how to work with SPPAS



## How to Install SPPAS

Install SPPAS:
1. download the zip
2. unzip
3. install the necessary dependencies:
3.a install wxpython. Somehow it was quite difficult to install on my machine. 
I had to follow advice on this link:
https://askubuntu.com/questions/1073145/how-to-install-wxpython-4-ubuntu-18-04

Here are the steps again, for you to follow:

```sh
sudo apt install make gcc libgtk-3-dev libwebkitgtk-dev libwebkitgtk-3.0-dev libgstreamer-gl1.0-0 freeglut3 freeglut3-dev python-gst-1.0 python3-gst-1.0 libglib2.0-dev ubuntu-restricted-extras libgstreamer-plugins-base1.0-dev
```
then:

```sh
sudo pip3 install wxpython
```
Then wait for a while and it will install it.

3b install brew
3c install julius:
```sh
brew install julius
```

That's all you need, you can now launch the GUI for SPPAS with:


```sh
python3 -m sppas
```

But actually you dont need the GUI and you can use it on CLI. Interesting things to read first are:

www2.lpl-aix.fr/~bigi/Doc/2015-SPPAS-Tutorial-HongKong/SPPAS-tutorial_04_methodo.html

http://www.sppas.org/documentation_03_annotations.html



