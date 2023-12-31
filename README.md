# Nottingham Group Project Meeting Minutes Template

Template for Group Project Meeting Minute in University of Nottingham.

## Requirements

Engine: pdfLaTeX

### Packages

- geometry
- setspace
- graphicx
- array
- multirow
- xcolor

## Usage

### Getting the Template

#### Using git

1. Install [git](https://git-scm.com/) to your computer.
2. Change to desired directory.

    ```sh
    cd /path/to/directory
    ```

3. Clone repository **Remember to change _directory\_name_ to the desired name of the folder**

    ```sh
    git clone https://github.com/ecyht2/Nottingham-Group-Project-Meeting-Minutes-Template.git directory_name
    ```

#### Using Zip

1. Download the ZIP file in the code dropdown.

    ![Image of ZIP file download](readme_img/download-zip.png)

2. Extract files to working directory.

#### Using GitHub

1. Sign in to GitHub
2. Click on the `Use this template` button.
3. Click `Create a new repository`.
4. Clone the repository. See [Using git](https://github.com/ecyht2/Nottingham-Group-Project-Meeting-Minutes-Template#using-git)

#### Using Overleaf

TBA

### Changing Titlepage Information

This template provides commands to change the information the title page. All the commands available are shown in the table below.

| Command                 | Description                             |
| ----------------------- | --------------------------------------- |
| \academicyear{year}     | Sets the academic year                  |
| \author{authors}        | Sets the student name/names             |
| \title{title}           | Sets the project title                  |
| \supervisor{supervisor} | Sets the project supervisor/supervisors |
| \date{date}             | Sets the date of the meeting            |
| \length{duration}       | Sets the length of the meeting          |

### Commands and Enviornments

This template provides enviornments and commands to insert the contents of the meeting minutes.

#### Commands

| Command          | Description                | Parameters |
| ---------------- | -------------------------- | ---------- |
| \printsignatures | Prints the signature lines | None       |

#### Enviornments

| Enviornment | Description                                    | Parameters                                   |
| ----------- | ---------------------------------------------- | -------------------------------------------- |
| progress    | "Progress made since the last meeting" content | The minimum height of the content (optional) |
| planned     | "Items discussed/planned for the week" content | The minimum height of the content (optional) |
| remarks     | The remarks content                            | The minimum height of the content (optional) |
| labeled     | A piece of content with a label.                   | The label of the content, The minimum height of the content |

## License

This repository including images except for Nottingham logo is license under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).
