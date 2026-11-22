# ProjectTemplate


## License

This project is dual-licensed:
- `CC BY-NC-SA 4.0` for all assets
- `MIT` for everything else

## Programming automation & tools

1. Clone the repo, and run the setup scripts:
    1. Linux:
    ```
    ./setup.sh
    ```
    1. Windows:
    ```
    pip install -r requirements.txt
    pre-commit install
    pre-commit run --all-files
    ```
2. Optional recommended software:
    - Editor: [VSCode](https://code.visualstudio.com/) full IDE with advanced functionality compared to the Godot Editor, but needs to be configured properly with the [GDScript Formatter and Linter Extension](https://marketplace.visualstudio.com/items?itemName=EddieDover.gdscript-formatter-linter)


## Important programming notes

- We are using Formatter and Linter plugins that will automatically re-format your code or point out potential Errors when you save your Scripts. This may cause some confusion and also trigger the "Newer Files on Disk" Dialog in the Godot Editor, where you can choose "Reload from Disk"
- We will use Tabs for indentation ( it's being enforced by our Formatter )
- We will store all assets (art, audio) in `project/assets/`
- Assets that come with a custom license, for example google fonts, cannot be stored in the default assets folder as it already contains a license that covers all the sub folders as well