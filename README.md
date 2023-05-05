# GPT4All_GPTJ_backend Backend for GPT-J

![GitHub license](https://img.shields.io/github/license/ParisNeo/GPT4All_GPTJ_backend)
![GitHub issues](https://img.shields.io/github/issues/ParisNeo/GPT4All_GPTJ_backend)
![GitHub stars](https://img.shields.io/github/stars/ParisNeo/GPT4All_GPTJ_backend)
![GitHub forks](https://img.shields.io/github/forks/ParisNeo/GPT4All_GPTJ_backend)
[![Discord](https://img.shields.io/discord/1092918764925882418?color=7289da&label=Discord&logo=discord&logoColor=ffffff)](https://discord.gg/4rR282WJb6)
[![Follow me on Twitter](https://img.shields.io/twitter/follow/SpaceNerduino?style=social)](https://twitter.com/SpaceNerduino)
[![Follow Me on YouTube](https://img.shields.io/badge/Follow%20Me%20on-YouTube-red?style=flat&logo=youtube)](https://www.youtube.com/user/Parisneo)

The GPT4ALL-Backend is a Python-based backend that provides support for the GPT-J model. This backend can be used with the GPT4ALL-UI project to generate text based on user input.

## Installation
Before installing the GPT4ALL-Backend, make sure that you have Python 3.10 or higher installed on your machine and added to your path.

### Windows
- Open the command prompt and navigate to the gpt4all folder.
- Activate the virtual environment by running the following command: env\Scripts\activate
- Install the required packages by running the following command: pip install -r requirements.txt
- Copy the gptj folder to the backends folder of the GPT4ALL-ui project.

### Linux and macOS
- Open the terminal and navigate to the `gpt4all` folder.
- Activate the virtual environment by running the following command: source `env/bin/activate`
- Install the required packages by running the following command: `pip install -r requirements.txt`
- Copy the `gptj` folder to the backends folder of the GPT4ALL-ui project.
- Now create `gptj` folder inside models and put one or many gpt-j models there.

## Usage

To use the GPT-J backend, start the GPT4ALL-ui server by running the following command:
```bash
python app.py
```
or 

for windows:
```bash
webui.bat
```
for linux, macos:
```bash
webui.bat
```

Once the server is runing, navidate to the address displayed by the server (localhost:9600). In settings menu, select gpt_j as backend then select one of the models.

Now you can use the model with the backend.