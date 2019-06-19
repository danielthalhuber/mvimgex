# mvimgex

`mvimgex` is a bash script for extracting photos and videos from Google Motion Photo (`MVIMG_*.jpg`) files.

## Installation

Clone the repository:

```sh
git clone git@github.com:danielthalhuber/mvimgex.git
```

Ensure that the file is executable:

```sh
chmod +x mvimgex
```

Save the executable file somewhere in your `PATH`:
```sh
cp mvimgex /usr/local/bin
```

## Usage

Extract from a single Motion Photo file:

```sh
mvimgex path/to/motion/photo/MVIMG_1234.jpg
```

Extract from all Motion Photo files in a directory:

```sh
mvimgex path/to/motion/photos
```

## License

This software is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)
