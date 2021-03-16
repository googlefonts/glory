Glory is a modern sans serif font. The rounded corners give it a soft, contemporary feel. While the characters are slightly condensed, this semi mono-weight sans features subtly curved vertical strokes.  

It was created with graphic design in mind. It is suitable for logos, headlines and body text with the available six weights. Combine Glory with other script styles to give your work warmth and contrast. For a truly professional look, team up Glory with its script companion, Hurricane.

Glory comes with Latin Character sets including Western, Central, and Vietnamese language support.

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
