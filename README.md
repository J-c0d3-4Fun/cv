#### Resume/ Curriculum vitae (CV)
This repository was created to host, build, and deploy my resume/cv 

### Command to create PDF
docker run --rm -i -v "$PWD":/data latex pdflatex cv.tex
