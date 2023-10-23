# Structura
## App errors
| Error code | Error example | Meaning | Solution |
|------------|---------------|---------|----------|
|Non-Compound root tags is not supported | ![image](https://github.com/hegehog8761/structura-tests/assets/119626198/f7e07936-ccb4-4e26-95e0-0f8794108c76) | A part of the file is not formatted as it would normally be so the file could not be converted | Make sure that you aren't exporting to a folder that is used by Microsoft OneDrive, you can ensure this by saving the file to `This PC->C: Drive->Users->Your username->Downloads`
|ModuleNotFoundError: No module named ... | ![image](https://github.com/hegehog8761/structura-tests/assets/119626198/67322d78-1c43-405f-be6e-b716105b2162) | Some of the files required could not be found on your computer | Make sure that you are downloading **all of** the files from the github page and run `pip install -r requirements.txt` if you are running it using python (probably not if you are not sure) in the folder you have all of the other files in |

 

## Bot errors
| Error code | Error example | Meaning | Solution|
|------------|---------------|---------|---------|
|The application did not respond | ![image](https://github.com/hegehog8761/structura-tests/assets/119626198/a42ea24a-ab35-4cdf-b1fb-9bc39112613b) | The bot did not manage to start up in the time allocated by Discord | Attempt to run the command again to get the bot started |
| Processing, if this hangs it is because the file is too big. retrying will not fix it | ![image](https://github.com/hegehog8761/structura-tests/assets/119626198/8b3a5f7f-eb0d-4bb9-bf30-6a1d4ff72167) | Your file took too long to proccess as it was too large and so was cancelled | Either try to split your build into separate parts or use the app to convert it |
| This interaction failed | ![image](https://github.com/hegehog8761/structura-tests/images/interaction_failed.png) | Discord was unable to handle your command | Use [the website](https://discord.gg/) version of discord rather than a modified client |
| An error occurred (ValidationException) when calling the UpdateItem operation: ExpressionAttributeValues contains invalid key: Syntax error; key: ":name:name" | ![image](https://github.com/hegehog8761/structura-tests/assets/119626198/49bf1ac7-1abd-46bc-9dfe-1e42ce1b0d6a) | A none vanilla block was attempted to be converted and crashed | Remove all behaviour packs from your world and re-export the file |

