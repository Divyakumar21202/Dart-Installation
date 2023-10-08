# Dart-Installation

# Dart Steps-by-Steps Installation :

This document provides step-by-step instructions for installing Dart on different operating systems and running Dart in a web-based environment.

## Table of Contents

- [Windows Installation](#windows-installation)
- [Mac Installation](#mac-installation)
- [Linux Installation](#linux-installation)
- [Running Dart on the Web](#running-dart-on-the-web)

## Windows Installation

Follow these steps to install Dart on a Windows operating system:

1. Download the Dart SDK from [here](link-to-download).
2. Copy the `dart-sdk` folder to your C drive (C:\dart-sdk).
3. Add `C:\dart-sdk\bin` to your system's environment variables.
4. Open the command prompt and type `dart --version` to verify the installation.

## Mac Installation

To install Dart on a Mac, use Homebrew:

1. Install Homebrew if not already installed by running the following command:
   ```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. Tap into the Dart repository:
   ```
   brew tap dart-lang/dart
   ```

3. Install Dart:
   ```
   brew install dart
   ```

## Linux Installation

Install Dart on Linux by following these steps:

1. Open your terminal and run the following commands:

   ```
   sudo apt-get update
   sudo apt-get install apt-transport-https
   wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo gpg --dearmor -o /usr/share/keyrings/dart.gpg
   echo 'deb [signed-by=/usr/share/keyrings/dart.gpg arch=amd64] https://storage.googleapis.com/download.dartlang.org/linux/debian stable main' | sudo tee /etc/apt/sources.list.d/dart_stable.list
   ```

2. Install Dart:

   ```
   sudo apt-get update
   sudo apt-get install dart
   ```

## Running Dart on the Web

You can run Dart programs in your browser using DartPad. Visit [DartPad](https://dartpad.dev/) to write and run your Dart code in a web-based environment.

#Explore My GitHub

Thank you for visiting my GitHub profile! If you're interested in exploring more of my projects and contributions, feel free to visit my GitHub repository:

GitHub [Profile](https://github.com/Divyakumar21202.git)

I have a diverse range of projects, and I'm always working on something new and exciting. Follow me on GitHub to stay updated with my latest work and contributions.

Feel free to connect with me if you have any questions, suggestions, or just want to chat. Happy coding!
