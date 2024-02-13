# FormatFusion-CLI: Effortless File Format Conversion

FormatFusion-CLI is a user-friendly command-line program designed to streamline your file format conversion needs. With support for popular formats like JSON, CSV, XML, and YAML, it eliminates the hassle of manual conversions and batch processes, saving you time and effort.

**Key Features:**

- Simple and intuitive command-line interface.
  Supports conversion between JSON, CSV, XML, and YAML formats.
- Efficient batch processing for multiple files.
- Preserves data integrity during conversion.
- Lightweight and portable, works across various operating systems.

**Target Audience:**

FormatFusion-CLI caters to a wide range of users, including:

- Developers: Easily integrate format conversion into your workflows.
- Data analysts: Clean and prepare data in different formats for analysis.
- System administrators: Manage and convert configuration files efficiently.
- Content creators: Convert content between various formats for different platforms.

## Getting Started:

### Installation:

Download the software source from this github repository [FormatFusion-cli]().
Alternatively, follow the compilation instructions provided in the INSTALL.md file.

Then, you can create a virtual environment using this following command:

```bash
py -m venv env
```

after that, activate the virtual environment using this command:

```bash
.\env\Scripts\activate
```

and run this command to install the requirements:

```bash
pip install -r requirements.txt
```

### Basic Usage:

The general usage format is:

1. **Help**

   ```bash
   python cli.py -h
   ```

   The command above will return a help information about FormatFusion cli as you can see bellow

   ```bash

   .--.._       _..--.
   /   _.-'''-.  `-._   \
   |          |       |
   |  F O R M A T  |  F U S I O N  |
   |          |       |
   \   `-._.-'   `-._/ /
   `.-----.---...---.-----'
   By: Wahyu Krisna Aji
   version 0.2.x

   usage: cli.py [-h] input_file output_file

   Convert files to another file format.

   positional arguments:
   input_file   path input file.
   output_file  path output file.

   options:
   -h, --help   show this help message and exit
   ```

2. **Main Function (File Converter)**

   To use the file convertion function you can write down this following command:

   ```bash
   python cli.py input_file output_file
   ```

   example: you have a file name **test.json**. then, you want to conver your test.json file into **test.yaml**, so in order to achieve that, you need to write down the following command:

   ```bash
   python cli.py test.json test.yaml
   ```

   Here is the breakdown of the command:

   - **input_file**: this is the path of your input file.
   - **output_file**: this is the path of your output file (expected result).

### Contributing:

We welcome contributions from the community! If you'd like to improve FormatFusion-CLI, please refer to the CONTRIBUTING.md file for guidelines.

### License:

FormatFusion-CLI is distributed under the [MIT LICENSE](LICENSE) license. See the LICENSE file for details.

### Requirements

For more detail about the requirements, you can check it in the requirements.txt or you can visit it using the [following link](https://github.com/aliftech/FormatFusion)
