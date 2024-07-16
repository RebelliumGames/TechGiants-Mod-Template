# Tech Giants Mod

To install this mod copy and paste below link into the mod section of Tech Giants Game. 
```
https://rebelliumgames.github.io/TechGiantsModTemplate/
``` 

## Steps to create your own mod

1. First create your own copy of the template by forking it, visit this [link to Fork](https://github.com/RebelliumGames/TechGiantsModTemplate/fork).
2. In `Repository name` field write your mod name.
3. Then click on **Create fork**.
4. Next enable github pages for your repository by going to **Settings tab** and scroll down to the **Pages** section.
5. Under **Branch** which is set to `None` select `main` then **Save**.
6. It might take a minute for you changes to take affect and be deployed to GitHub Pages.
7. Using your browser visit `https://username.github.io/repository/manifest.json`.
8. You can edit the files on GitHub or clone/download them locally edit them, then upload/push them back to GitHub.
9. Make sure to have a unique ID for your mod, you can get one [here](https://rebelliumgames.github.io/TechGiantsMod/) and put it in the `uuid` section of your `manifest.json`.
10. please make sure to create a new json object inside `versions` array in `manifest.json` and fill out the values correctly. the `sourceURL` will have to point to a file inside your GitHub repository. you can use absolute URLs like `https://rebelliumgames.github.io/TechGiantsMod/versions/v0.2.0/language.json` or use `./versions/v0.2.0/language.json` where the `./` is a substitute for your GitHub page URL. 

    ```json
    "versions": [
        {
            "version":"0.2.0",
            "changelog": "",
            "sourceURL": "./versions/v0.2.0/language.json",
            "supportedGameVersion": ">=0.2.0",
            "createdAt": "2024-07-17T00:00:00.000Z"
        }
    ]
    ```

If you incounter any problem please visit the [Dicord server](https://discord.gg/hexEVAxBJr) and ask the community for help.


https://github.com/user-attachments/assets/4b00473c-780d-40f9-8e9d-c0e4782a4144

# Changes from previous version

`language.json` now has more words/sentences, below is whats is added in v0.2.0-beta.4

When appending below language sentences be careful not to remove `{words in sentences}` and newlines `\n`

```
{
    "THIS_GAME_WILL_BE_SOON_DISCONTINUED_DUE_TO_LOW_SALE_FIGURES": "This game will be soon discontinued due to low sale figures.",
    "ADVERTISING_TV_Commercials": "TV Commercials",
    "ADVERTISING_Magazine_Ads": "Magazine Ads",
    "ADVERTISING_Newspapers_Ads": "Newspapers Ads",
    "ADVERTISING_In_Store_Demos": "In-Store Demos",
    "ADVERTISING_Billboards": "Billboards",
    "ADVERTISING_Bus_Ads": "Bus Ads",
    "COMPANY": "Company",
    "CONTINUE_GAME": "Continue Game",
    "DISABLED": "Disabled",
    "ADD_MOD_REPOSITORY": "Add Mod Repository",
    "BACK": "Back",
    "REMOVE": "Remove",
    "CLOSE": "Close",
    "CONFIRM": "Confirm",
    "ARE_YOU_CERTAIN_YOU_WANT_TO_DELETE": "Are you certain you want to delete",
    "RANDOMIZE_CHARACTER_APPEARANCE": "Randomize character appearance",
    "CORPORATE_TAX": "Corporate Tax",
    "CAPITAL": "Capital",
    "DATE": "Date",
    "UNITS": "Units",
    "MARKET_SHARE": "Market Share",
    "COMPANIES": "Companies",
    "COMPANY_DESCRIPTION": "Founded in {FOUNDING_DATE} by {CHARACTER_NAME}, {COMPANY_NAME} is a game studio headquartered in {LOCATION}.",
    "MANAGE_STAFF": "Manage Staff",
    "PUBLIC_COMPANY": "Public Company",
    "PRIVATE_COMPANY": "Private Company",
    "CURRENT_PROPERTIES": "Current Properties",
    "PROPERTY": "Property",
    "LEASING_PRICE": "Leasing Price",
    "RENTABLE_SQUARE_METER": "RSM",
    "OFFICE_SPACE": "Office Space",
    "PERSON": "Person",
    "BUYING_PRICE": "Buying Price",
    "SIZE": "Size",
    "AVAILABLE_PROPERTIES": "Available Properties",
    "LEASE_OFFICE": "Lease Office",
    "BUY_OFFICE": "Buy Office",
    "DISTRIBUTION_MEDIA": "Distribution Media",
    "SELF_PUBLISH": "Self Publish",
    "SIGN_A_CONTRACT": "Sign a Contract",
    "ROM_CARTRIDGE": "ROM Cartridge",
    "FLOPPY_DISK": "Floppy Disk",
    "CASSETTE_TAPE": "Cassette Tape",
    "ART": "Art",
    "AUDIO_ENGINEERING": "Audio Engineering",
    "DESIGN": "Design",
    "DIRECTING": "Directing",
    "PRODUCING": "Producing",
    "PROGRAMMING": "Programming",
    "WRITING": "Writing",
    "HIRE_EMPLOYEE": "Hire Employee",
    "ARTIST": "Artist",
    "AUDIO_ENGINEER": "Audio Engineer",
    "DESIGNER": "Designer",
    "DIRECTOR": "Director",
    "PRODUCER": "Producer",
    "PROGRAMMER": "Programmer",
    "WRITER": "Writer",
    "FOUNDER": "Founder",
    "GAME": "Game",
    "BUY_LICENSE_FOR": "Buy License for",
    "A_YEAR": "a year",
    "GRAPHICS_POWER": "Graphics Power",
    "PROCESSING_POWER": "Processing Power",
    "STORAGE_MEDIA": "Storage Media",
    "MEMORY": "Memory",
    "DOWNLOAD_DEBUG_INFORMATION": "Download Debug Information",
    "COLLECTING_INFORMATION": "Collecting Information...",
    "SYSTEM_INFORMATION": "System Information",
    "LOGS": "Logs",
    "SOUND": "Sound",
    "TEXT_SIZE": "Text Size",
    "TELEMETRY": "Telemetry",
    "TELEMETRY_MESSAGE": "To make Tech Giants as good as possible, we'd like to ask your permission to collect and process your analytics data, including error reports and general gameplay statistics. Your data are sent automatically over the internet and are always 100% anonymous.",
    "THIS_SAVE_ALREADY_EXISTS_DO_YOU_WANT_TO_OVERWRITE_IT": "This save already exists, do you want to overwrite it?",
    "OVERWRITE": "Overwrite",
    "SCENARIO_1_TITLE": "Video Game Pioneers",
    "SCENARIO_1_DESCRIPTION": "In the year 1978, you and your former colleagues from {COMPANY1} find yourselves yearning for more. Inspired by the groundbreaking success of {COMPANY2}, you decide to break free from the corporate mold. Armed with {FUNDING} in funding from {COMPANY3}, you embark on an audacious journey.\n Your mission? To forge a new path in the tech industry. You establish a fledgling game development company, with a vision as vast as the California sky. Your headquarters, a modest office space bathed in sunlight, sits just a stone’s throw away from the iconic {COMPANY1} campus in Sunny Vale.\n As the founder and CEO, you’ll navigate the treacherous waters of creativity, innovation, and competition. Will you pioneer groundbreaking games, revolutionize the industry, and leave an indelible mark on gaming history? The fate of your company rests in your hands."
}
```