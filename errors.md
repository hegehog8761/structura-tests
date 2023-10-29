# Structura
[Skip to bot errors](#bot-errors) <br>
To search visit [this website](https://htmlpreview.github.io/?https://github.com/hegehog8761/structura-tests/blob/main/search.html)
## App errors
| Error code | Error example | Meaning | Solution |
|------------|---------------|---------|----------|
| <a name="non-compound_roots"></a> Non-Compound root tags is not supported | ![image](https://raw.githubusercontent.com/hegehog8761/structura-tests/main/images/non-compound_roots.png) | A part of the file is not formatted as it would normally be so the file could not be converted | Make sure that you aren't exporting to a folder that is used by Microsoft OneDrive, you can ensure this by saving the file to `This PC->C: Drive->Users->Your username->Downloads` |
| <a name="module_not_found"></a> ModuleNotFoundError: No module named ... | ![image](https://raw.githubusercontent.com/hegehog8761/structura-tests/main/images/module_not_found.png) | Some of the files required could not be found on your computer | Make sure that you are downloading **all of** the files from the github page and run `pip install -r requirements.txt` if you are running it using python (probably not if you are not sure) in the folder you have all of the other files in |

 

## Bot errors
| Error code | Error example | Meaning | Solution|
|------------|---------------|---------|---------|
| <a name="did_not_respond"></a> The application did not respond | ![image](https://raw.githubusercontent.com/hegehog8761/structura-tests/main/images/did_not_respond.png) | The bot did not manage to start up in the time allocated by Discord | Attempt to run the command again to get the bot started |
| <a name="hang"></a> Processing, if this hangs it is because the file is too big. retrying will not fix it | ![image](https://raw.githubusercontent.com/hegehog8761/structura-tests/main/images/processing.png) | Your file took too long to proccess as it was too large and so was cancelled | Either try to split your build into separate parts or use the app to convert it |
| <a name="failed"></a> This interaction failed | ![image](https://raw.githubusercontent.com/hegehog8761/structura-tests/main/images/interaction_failed.png) | Discord was unable to handle your command | Use [the website](https://discord.gg/) version of discord rather than a modified client |
| <a name="invalid_key"></a> An error occurred (ValidationException) when calling the UpdateItem operation: ExpressionAttributeValues contains invalid key: Syntax error; key: ":name:name" | ![image](https://raw.githubusercontent.com/hegehog8761/structura-tests/main/images/invalid_key.png) | A none vanilla block was attempted to be converted and crashed | Remove all behaviour packs from your world and re-export the file |
| <a name="no_valid_files"></a> No Valid Files Were attached| ![image](https://raw.githubusercontent.com/hegehog8761/structura-tests/main/images/no_valid_files.png) | The file you provided was not valid, either 0KB (corupted by Microsoft OneDrive) in size or wrong file type | If the size is 0KB save the file to `This PC->C: Drive->Users->Your username->Downloads` <br><br> If the file size is not 0, make sure that the file is named `something.mcstructure` if it does not end in `.mcstructure` then it is the wrong file, make sure that it is a Minecraft Bedrock mcstructure file | 
| <a name="ui_error"></a> /convert file1: | 
