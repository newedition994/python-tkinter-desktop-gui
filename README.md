# Part Manager

> Python/Tkinter desktop GUI app to manage customer computer parts

## Usage

install dependencies
`pipenv install`

run script
`python part_manager.py`

Mac
pyinstaller --onefile --add-binary='/System/Library/Frameworks/Tk.framework/Tk':'tk' --add-binary='/System/Library/Frameworks/Tcl.framework/Tcl':'tcl' part_manager.py
