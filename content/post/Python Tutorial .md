---
title: "Python Tutorial"
date: 2021-12-09T16:11:49+07:00
draft: true
---


## Python Tutorial : How to Process JSON Data in Python (from File and Web API)

### JSON

JSON (JavaScript Object Notation) is a lightweight data exchange format, easy to read and write by humans, and easy to translate and generate (generate) by computers.JSON is a text format that does not depend on any programming language because it uses a language style commonly used by C family programmers including C, C++, C#, Java, JavaScript, Perl, Python etc. Because of these properties, it makes JSON ideal as a data-exchange language.

now we will learn how to process JSON data in Python with the json library and also later we will try to retrieve JSON data from the API Server. Lets begin.

### 1.How to Parse JSON in Python

first we will parse the data in the json file, why should we do that?

Because the data can not be read directly in Python. It must be parsed first so that we can use it in Python.The way is that we can use the json module that has been provided by python. Let’s get started.

First create a new JSON file with the name mydata.json — can be created with pycharm and other text editors — then fill in the JSON file like this:

> All blame is a waste of time. No matter how much fault you find with another, and regardless of how much you blame him,  it will not change you” - Wayne Dyer


```py
import setuptools

with open("README.md", "r", encoding="utf-8") as fh:
    long_description = fh.read()

setuptools.setup(
    name="latestearthquakenewsindonesia",
    version="0.7",
    author="Firman Arya P",
    author_email="firmanap22@gmail.com",
    description="his package will get the latest earthquake news from Indonesia BMKG Meteorological, "
                "Climatological And Geophysical Agency",
    long_description=long_description,
    long_description_content_type="text/markdown",
    url="https://github.com/jakarta-remote-work/Latest-Earthquake-News",
    project_urls={

    },
    classifiers=[
        "Programming Language :: Python :: 3",
        "License :: OSI Approved :: GNU General Public License v3 (GPLv3)",
        "Operating System :: OS Independent",
        "Development Status :: 5 - Production/Stable"
    ],
    # package_dir={"": "src"},
    # packages=setuptools.find_packages(where=""),
    packages=setuptools.find_packages(),
    python_requires=">=3.6",
)
```

