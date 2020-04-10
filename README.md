# Sudoku
**Sudoku** is a console-level graphics interactive game based on world-wide popular [Japanese puzzle][1].<br />
This is a **team** project done as part of [Practical Programming][2] elective course in second semester of my bachelor studies.

## Installation
Main project depencendy is [Curses][3] library used for console graphics. Project installation slightly differs depending on which operating system you are using cause of its nature and nature of used library.

### Windows OS

// TO-DO

### Linux-based OS
First, you must install mentioned dependency which is `ncurses` packege on Linux distributions.<br />
Command for installing `ncurses` package sligthly varies depending on specific distribution:

#### Debian / Ubuntu OS
```bash
sudo apt-get install libncurses5-dev libncursesw5-dev
```

#### CentOS / RHEL / Scientific Linux 6.x/7.x+ and Fedora Linux 21 or older
```bash
sudo yum install ncurses-devel
```

#### Fedora Linux 22.x+
```bash
sudo dnf install ncurses-devel
```
<br />

After successful pacakge instalation, only thing left to do is to compile project using `Make`:
```bash
$ make
```

>*`Make` package must be installed before project compilation, but is usually pre-installed with distribution.*

## Documentation
All relevant documentation can be found in decicated [Documentation][4] folder.

## Contributors
* Aleksa Brkić ([brksoman][5])
* Miljan Zarubica ([zarubica][6])
* Petar Đekanović ([petalex][7])

[1]: https://en.wikipedia.org/wiki/Sudoku
[2]: https://rti.etf.bg.ac.rs/rti/ir1pp2/index_si.html
[3]: https://en.wikipedia.org/wiki/Curses_(programming_library)#pcurses_and_PDCurses
[4]: https://github.com/petalex/sudoku/tree/master/docs
[5]: https://github.com/brksoman
[6]: https://github.com/zarubica
[7]: https://github.com/petalex
