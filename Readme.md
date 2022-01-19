## Sample Latex Project


This is a sample latex project for your report or your paper , it use the icml2015 style guide for reference and everything .


## Why did I create this?

I have been tired of using overleaf, and it not free. I setup VS code to use latex in VsCode . 

You can use [this tutorial to](https://linuxpip.org/vscode-latex/) learn how to use latex in VScode. If you are a coder like me you will enjoy it. 

## How to run

### Install Latex

If you are a hacker and have macbook pro, I am sure you have homebrew installed , if not what are you waiting for ? Just head up here and [install it ](https://brew.sh/).

Once brew is install install the latex tools and packages. 

- `brew install --cask mactex`


This should take some time but it will installed , restart your terminal and check if latex and other packages are installed and accessible via cmd by running 

- `which latex`


### Build and run 


If everything is okay and you can build your project form the command line running the following command in order : 

- `pdflatex report`
- `biblatex report`
- `pdflatex report`
- `pdflatex report`


If everything goes well you should see the pdf.
