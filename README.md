<h1 align="center">Numworks-App-Development-Template</h1>
<p align="center">
    <img alt="Version" src="https://img.shields.io/badge/Version-1.1.1-blue?style=for-the-badge&color=blue">
    <img alt="Stars" src="https://img.shields.io/github/stars/SaltyMold/Numworks-App-Development-Template?style=for-the-badge&color=magenta">
    <img alt="Forks" src="https://img.shields.io/github/forks/SaltyMold/Numworks-App-Development-Template?color=cyan&style=for-the-badge&color=purple">
    <img alt="License" src="https://img.shields.io/github/license/SaltyMold/Numworks-App-Development-Template?style=for-the-badge&color=blue">
    <br>
    <a href="https://github.com/SaltyMold"><img title="Developer" src="https://img.shields.io/badge/Developer-SaltyMold-red?style=flat-square"></a>
    <img alt="Maintained" src="https://img.shields.io/badge/Maintained-No-blue?style=flat-square">
    <img alt="Written In" src="https://img.shields.io/badge/Written%20In-C-yellow?style=flat-square">
</p>

_This repo is a template to help you to create a C app for the Numworks calculator._

| Simulator | IRL |
|----------|--------|
| <img width="458" height="918" alt="SIM" src="https://github.com/user-attachments/assets/7b715f9c-9c52-4d39-b747-07784fdae3af" /> | ![IRL](https://github.com/user-attachments/assets/fd59b9a8-2437-49e2-aa7f-380ad2e20eac) |

## ⚙️ Setup Instructions

You need to install the required dependencies to build. You can find the instructions in my **[C-App-Guide-for-Numworks](https://github.com/SaltyMold/C-App-Guide-for-Numworks)** github repo.

You also need to install **x86_64-w64-mingw32-gcc** to compile your app for the simulator on your computer.

**Clone the repository**:

   ```sh
   git clone https://github.com/SaltyMold/Numworks-App-Development-Template.git
   cd Numworks-App-Development-Template
   ```

## ✨ Usage

To build the app for the calculator, run:
```sh
make build
```

To build the app for the simulator, run:
```sh
make test
```
To install the app on your calculator, connect it via USB and run:
```sh
make run
```
To debug the binary build, run:
```sh
make check
```
To clean the build files, run:
```sh
make clean
```

## 🛠️ Build your own app

Inside the project, you'll find **`eadk.h`**, which provides essential functions for interacting with the calculator. There is also a **`storage.h`** for managing data storage.
Additionally, make sure to include an **`icon.png`** with dimensions **55×56 pixels** to serve as your app’s icon.