A collection of additional python tools for use in makefiles.

# Usage

## FilesToInstaller

```
usage: FilesToInstaller.py [-h] --input INPUT [INPUT ...] --output OUTPUT --relative-path RELATIVE_PATH [--operation [OPERATION]]

Script to create an event file that #includes several given event files.

optional arguments:
  -h, --help            show this help message and exit
  --input INPUT [INPUT ...]
                        Filenames to be combined into the output file.
  --output OUTPUT       Filename of output file.
  --relative-path RELATIVE_PATH
                        Relative file path of the inputs and output files.
  --operation [OPERATION]
                        Operation used on the input files in the output file.

```

## FontImport
```
usage: FontImport.py [-h] --input INPUT [INPUT ...] --input-image INPUT_IMAGE [INPUT_IMAGE ...] --output OUTPUT
                     --relative-path RELATIVE_PATH [--name NAME] [--width WIDTH]

Script to create an event file to install font image files.

options:
  -h, --help            show this help message and exit
  --input INPUT [INPUT ...]
                        Filenames of font image binaries.
  --input-image INPUT_IMAGE [INPUT_IMAGE ...]
                        Filenames of font image files.
  --output OUTPUT       Filename of output file.
  --relative-path RELATIVE_PATH
                        Relative file path of the inputs and output files.
  --name NAME           Name of installer.
  --width WIDTH         Extra width to add to characters.
```

# Credits

| Name                 | Author(s) |
|----------------------|-----------|
| ``FilesToInstaller`` | Kirito    |
| ``FontImport``       | Kirito    |