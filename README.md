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

# Credits

| Name                 | Author(s) |
|----------------------|-----------|
| ``FilesToInstaller`` | Kirito    |