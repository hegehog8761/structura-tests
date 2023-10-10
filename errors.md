# Structura
Error codes

| Error code | Error example | Meaning | Solution |
|------------|---------------|---------|----------|
|Non-Compound root tags is not supported |Exception in Tkinter callback Traceback (most recent call last):
File "tkinter__init.py", line 1921, in call
File "structura.py", line 200, in runFromGui
File "structura_core.py", line 79, in generate_with_nametags
File "structure_reader.py", line 25, in init__
File "nbtlib\nbt.py", line 131, in load
File "nbtlib\nbt.py", line 259, in from_fileobj
File "nbtlib\nbt.py", line 225, in parse
TypeError: Non-Compound root tags is not supported: <class 'nbtlib.tag.End'> |