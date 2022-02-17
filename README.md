# openSUSE Lesson Plan
[![Generate pdf](https://github.com/KaratekHD/lessons/actions/workflows/pdf.yml/badge.svg)](https://github.com/KaratekHD/lessons/actions/workflows/pdf.yml)

This project is a collaborative effort for designing and preparing lesson plans for teachers, home educators, students and self-learners. The lesson plans focus on segments of open-source software development, culture and contribution. The material is helpful for curriculums involving the teaching of IT courses in primary, secondary and higher education.

## Feedback on use of content
The developers of this content are interested in knowing how it is being used. Please send us feedback in comments or contribute with a pull request, or open up an issue. We plan to run a contest after all the content is completed.

## How to use this repository
The current build of the  PDF is avaliable in GitHub Actions. Visit https://github.com/KaratekHD/lessons/actions/workflows/pdf.yml, click the latest entry with a green  checkmark next to it and click on `lesson-plan.pdf` down at the bottom. This will give you a zip file containing the PDF. This is not an ideal solution, if you have any suggestions on how to improve this Action feel free to open a PR.
## Setting up your build environment
1. Clone this repository.
2. Install Pytohn and Pip: `sudo zypper install python38-base python38-pip`
3. Install Pipenv: `pip install pipenv`
4. Install the requirements using Pipenv - This will set up a virtual environment for you so that you can't mess with your system Python libraries: `pipenv install`
5. You can now build the PDF document locally by running `ENABLE_PDF_EXPORT=1 pipenv run mkdocs build`

## Editing the sources
Place new documents in the `/docs` directory using markdown files. 
You can see your changes by running `ENABLE_PDF_EXPORT=1 pipenv run`.
Once you're ready to propose your changes, make a PR to this repo. [Material for mkdocs](https://squidfunk.github.io/mkdocs-material/), [mkdocs](https://www.mkdocs.org/user-guide/writing-your-docs/) and [mkdocs with PDF](https://pypi.org/project/mkdocs-with-pdf/) documentation could also be useful.

## License

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
