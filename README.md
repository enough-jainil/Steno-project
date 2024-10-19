# Steno :loop:

[![GitHub Super-Linter](https://github.com/enough-jainil/Steno-project/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/marketplace/actions/super-linter)

## Ultimate Steganography Software :superhero:

The all-in-one steganography application. :grin:<br>
**Formats Supported:**

- Images
- Audio
- Text
- ~~Video~~ _To be supported in future versions_

> This is an important application, especially in today's world.<br>
> We need to hide messages rather than only encrypting them.

## Features

- Hide your private messages in images, audio, and text files.
- Forgot password feature in case you forget. <br>
  (Click on the _3 dots_ in the main window to know more)
- Access info about any button just by hovering over it.

![homescreen](https://github.com/enough-jainil/Steno-project/blob/master/images/img.png?raw=true)

Using the _3 dots_ present in the top-right of the above window, users can create an account in case they forget the password for their respective hidden messages in files.

## Other Notes

All modules are standard modules of **batteries included** Python. Then use the `main.py`.
**Having `Cascadia Code` font makes the GUI look best.**
The GUI is quite explanatory, so I hope you don't have any problems using this.
In audio steganography, only `.wav` files are supported presently. In images, all formats are supported.

## Roadmap

- Enabling encryption of data
- Adding video support

## Installation Instructions

```
# Your global Python installation needs to have pipenv
pip install pipenv

# Clone the repo
git clone https://github.com/enough-jainil/Steno-project

# Change directories into the project
cd Steno-project

# [developer only] If you are a developer, you need to install dependencies for dev
pipenv install --dev

# If you're not a developer, just install required dependencies like this
pipenv install

# Activate the Pipenv shell (aka tell your terminal/whatever to use dependencies from the env in this project)
pipenv shell

# Start the program
python -m main.py
```

## Steganography is not Cryptography! :confused:

If you are getting confused between _Steganography_ & _Cryptography_, then see this:

#### Cryptography

**If** `you = wms` **then** `Qcaapgrw gq gknmprylr` **= ?**<br>
_Can you guess the answer?_<br>
Here we have `key = -2`, i.e., if we go 2 alphabets behind `y`, you get `w`, and similarly, if you go 2 alphabets behind `o`, we get `m`, and similarly, 2 alphabets behind `u` gives us `s`. Therefore `you = wms`. <br>
So now you may have got the answer, which is `Security is important`.

> Note: The cryptography algorithms are much advanced now.

#### Steganography

So now that you know what cryptography is, let's know what _Steganography_ is.<br>
**If** `____=____` **then** `______=______` **?**<br>
_Confused?_<br>
Here you won't be able to even sense the presence of data. Leave alone knowing what
is the data. That's why it is called hiding data in plain sight. There are some applications that
may detect the presence of hidden data. CIA obviously has it. <br>
Generally, at a professional level, the data hidden is encrypted first. So _steganography_ and _cryptography_ are not
mutually exclusive to each other.

> Knowledge fact: Jeff Bezos's mobile was hacked by hiding malicious code in a media
> file which, on getting downloaded, sent the host device's control to the hacker.

## License

[MIT](https://choosealicense.com/licenses/mit/)
