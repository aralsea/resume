# resume
To generate a PDF file of the resume from the repository, 
1. open your terminal and navigate to an appropriate working directory.
2. just run the following command.
``` shell
git clone https://github.com/aralsea/resume.git \
&& cd resume \
&& latexmk 2023_04/resume_2023_04.tex -output-directory=2023_04 \
&& open 2023_04/resume_2023_04.pdf
```

