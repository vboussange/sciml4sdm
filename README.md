# Scientific machine learning for species distribution modelling: a blueprint

---

This repository contains all the text, code and figures used for laying out a white paper about scientific machine learning approaches that present opportunities in the context of species distribution modelling. 


We refer to scientific machine learning as the ensemble of methods that permit to combine domain specific knowledge about a system (in our case, ecological processes) with machine learning techniques.

This project has been initiated during a workshop on DeepSDM held in May 2025 in Montpellier. We seek to reflect on ways to better integrate ecological knowledge and machine learning techniques in the context of species distribution modelling. We are looking for contributions from researchers interested in this topic to move forward and identify promising venues. 

## Contributing
- For adding references, please add your reference in a separate `.bib` file in the `tex/bibs` folder, and add a corresponding line in the master file

## How to use this repository :question:

- `tex`: This is the folder where all the latex text belongs and what we use to compile `main.pdf`.

- `code`: Folder with both Jupyter notebooks and Julia scripts.

- `.github`: This repository has a [workflow](https://github.com/ODINN-SciML/DiffEqSensitivity-Review/blob/main/.github/workflows/latex.yml) implemented that automatically compiles the latex files into the file `main.pdf` and then commits this file directy to the repository. If you are working from your fork, this action should also work, and you should be able to generate the pdf file automatically using GitHub actions. In order to trigger the GitHub action to compile and commit the Latex file, you just need to include the word `latex` in your commit message. 
<!-- This repository also includes an action to automatically merge all `*.bib` files into one single bibliography file `tex/bibliography.bib` that includes just the references that are cited in any of the `*.tex` files. 	 -->
<!-- In order to trigger this action, just include the word `bib-merge` in your commit message.  -->

- `Makefile`: make file that automatizes all the commands that can be executed within this repository. `make tex` compiles the `main.tex` latex file inside the folder `tex` with its respective bibliography, deletes auxiliaries files in the process and them move the generated pdf file to the home directory.

## Contact 

If you have any questions or want to reach out, feel free to open an issue.

## License 

The content of this project itself is licensed under the [Creative Commons Attribution 3.0 Unported license](https://creativecommons.org/licenses/by/3.0/), and the underlying source code used to format and display that content is licensed under the [MIT license](LICENSE).

Some of the code in this repo has been adapted from the [DiffEqSensitivity-Review project](https://github.com/ODINN-SciML/DiffEqSensitivity-Review), licensed under the MIT License.



