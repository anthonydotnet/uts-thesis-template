This template is the result of months of effort. 

I built upon the work of Dr. Chandranath Adak's original template to make it easier to adopt. It is, hence, substantially refactored. To view the original template, go to: https://www.overleaf.com/latex/templates/university-of-technology-sydney-uts-thesis-template/kndxjkgqmnjj

I supply this template without any warranty. I hope that this template will help save HDR students time (and stress). I hope to be frequently updating/improving this template, so please provide feedback so that future students can benefit from it.

I wish you all the best in your research.

Anthony Dang (Anthony.Dang@uts.edu.au | https://www.linkedin.com/in/anthonydotnet/)



=======
 USAGE
=======
1. Add configuration as required (see below)
- NOTE: Many of the original packages are commented out. I left them there in case someone needs them. I might remove these commented-out packages in the future.
2. Add your important quotes and definitions (see below)
3. Add content (see below)
4. When you are ready, remove the examples from main.tex


== Configuration ==
- config/hyphenation.tex (optional)
- config/abbreviations.tex (recommended)
- config/glossary.tex (recommended)
- assets/Signature.png  (required - replace with yours!)
- config/thesis-details.tex (required)
- config/preamble/macros-custom.tex (optional - put your custom macros here!)



== Quotes & Definitions ==
Store quotes and definitions in separate files.
- partial-content/definitions/your-definition-file.tex
- partial-content/quotes/your-quotefile.tex



== Content Pages ==
Your content goes here:
- pages/_preliminary/abstract.tex
- pages/_preliminary/acknowledgement.tex
- pages/_preliminary/dedication.tex
- pages/_preliminary/publications.tex
- pages/_preliminary/abstract.tex
- pages/appendices/
- pages/chapters/
    - Figures should go under /assets/ folders of each chapter.

Note: To add/remove chapters/appendices, see main.tex
REMEMBER: Remove the examples from main.tex


==================
 RECOMMENDATIONS
==================
Use the following folder structure for each chapter and appendix to help stay organised:
- assets
  - For images, PDFs, etc.
- partials
  - Use this for tables, figures, and other small .tex files to help stay organised. 
- sections
  - Use this for large sections of the chapter.




==================
 PULL REQUESTS
==================
Github: https://github.com/anthonydotnet/uts-thesis-template


