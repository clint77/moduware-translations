# moduware-translations

- This repository will contain information and instructions on how to use Moduware translation files

## Chinese translation for our Moduware Dashboard and Tiles

1. Clone the repository moduware-translation

- This becomes the basis for translation project. Another way to get a copy of the files is to download zip option when you click on the `Clone or download` drop down

2. Inside the dashboard are separate folders for main dashboard and each tile for translation

- dashboard
- led-tile
- speaker-tile
- temp-humidity-tile

3. Files

- Inside specific `dashboard` and `tile` folders are `en.json` file. This is the basis for our translation from English to Chinese. 
- It also contain a `zh.json` file. Edit this files with the corresponding translations

example: 

this is zh.json initial chinese placeholders

```json
  {
    "header": {
      "edit": "Edit Device (Chinese)",
      "notConnected": "Not Connected (Chinese)"
    }
  }
```

Becomes something like this. Do not include the word **(Chinese)** in parenthesis in the translation.

```json
  {
    "header": {
      "edit": "编辑装置",
      "notConnected": "编辑装置"
    }
  }  
```

3. Also ncluded is an `image` folder/directory which contains the screenshots for reference. The screenshots are also separated into each specific folders `dashboard` and `tiles`. And inside `tiles` folder are four individual folders for each tile specific screenshots.

4. After translation you can either do a pull request for each individual json file. Or you can zip the individual json files (the ones containing the chinese translations) and email them back to me. You can choose which ever is convinient to you. 

- If you have any question please shoot me an email.