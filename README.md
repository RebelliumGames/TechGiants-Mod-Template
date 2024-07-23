# Tech Giants Mod

To install this mod copy and paste below link into the mod section of Tech Giants Game. 
```
https://rebelliumgames.github.io/TechGiants-Mod-Template/repository.json
``` 

## Steps to create your own mod

1. First create your own copy of the template, [Create a new repository from Template](https://github.com/new?template_name=TechGiants-Mod-Template&template_owner=RebelliumGames).
2. In `Repository name` field write your mod name.
3. Then click on **Create repository**.
4. To classify your mod repository and make it easily discoverable, add `tech-giants` and `mod` [topics](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics#adding-topics-to-your-repository)
5. Next enable github pages for your repository by going to **Settings tab** and scroll down to the **Pages** section.
6. Under **Branch** which is set to `None` select `main` then **Save**.
7. It might take a minute for you changes to take affect and be deployed to GitHub Pages.
8. Using your browser visit `https://username.github.io/repository/repository.json`.

9. You can edit the files on GitHub or clone/download them locally edit them, then upload/push them back to GitHub.
10. Make sure to have a unique ID for your mod, you can get one [here](https://rebelliumgames.github.io/TechGiants-Mod/) and put it in the `uuid` section of your `manifest.json`.

11. please make sure to create a new json object inside `assets` array in `manifest.json` and fill out the values correctly. the `path` will have to point to a file inside your GitHub repository. you can use absolute URLs like `https://rebelliumgames.github.io/TechGiantsMod/versions/v0.2.0/assets/language.json` or use `assets/language.json`. 

    ```json
    "assets": [
        { "type": "json", "path": "assets/language.json" }
    ],
    ```

```mermaid
flowchart LR
    A{fa:fa-file-code repository.json} -->|fa:fa-link Link to Manifest| B{fa:fa-file-code manifest.json 
    v0.0.1}
    A{fa:fa-file-code repository.json} -->|fa:fa-link Link to Manifest| C{fa:fa-file-code manifest.json 
    v0.2.0}

    B -->|fa:fa-link Link to Asset| D[fa:fa-file language.json]
    C -->|fa:fa-link Link to Asset| E[fa:fa-file language.json]
```

If you incounter any problem please visit the [Dicord server](https://discord.gg/hexEVAxBJr) and ask the community for help.


https://github.com/user-attachments/assets/4b00473c-780d-40f9-8e9d-c0e4782a4144
