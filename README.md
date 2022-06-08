# text2spell

Translates input text to radiotelephony spelling alphabet.

It can be run by providing input text as argument vector in quotations to avoid the prompt.

## Requirements
Requires Ruby language installed.

To check if Ruby is already installed run: `ruby --version`

**Debian**  
`sudo apt install ruby`

**Arch**  
`sudo pacman -S ruby`

**Fedora**  
`sudo dnf install ruby`

## Usage

```bash
$ ./text2spell "Matsumoto Yukihiro"
Matsumoto => MIKE ALFA TANGO SIERRA UNIFORM MIKE OSCAR TANGO OSCAR
Yukihiro  => YANKEE UNIFORM KILO INDIA HOTEL INDIA ROMEO OSCAR
```

```bash
$ ./text2spell
Enter text: photosynthesis
photosynthesis => PAPA HOTEL OSCAR TANGO OSCAR SIERRA YANKEE NOVEMBER TANGO HOTEL ECHO SIERRA INDIA SIERRA
```