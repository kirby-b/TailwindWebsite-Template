# How to use

This is the first template I have ever made, so I am not 100% sure.
From my understanding though, the only steps you should need to do for using this template is:

1. On the top of this repo click "use this template" and then "create a new repository"
2. Download node modules to your local files of it so tailwind actually can build your css. Do not under any circumstance upload the node modules to your repo. You can do this with ``` npm update ``` which always works for me ( you will need to have node installed on your computer first, you can do this here: [node download page](https://nodejs.org/en/download/prebuilt-installer/current) )
3. Run ```npx tailwindcss -i ./src/unbuilt.css -o ./src/built.css --watch``` when you add new styles. You only need to do this with new style, not new text content ( replacing the lorem ipsum with real words )
