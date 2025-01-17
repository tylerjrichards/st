# 🎈 Kick-off your Streamlit projects with `st` CLI

Just hit `st` in your new project directory and it will:
- Create a basic Streamlit project structure in your directory:
```
.
├── .gitignore         # basic .gitignore to ignore Streamlit secrets!
├── .streamlit
│   └── secrets.toml   # empty Streamlit Secrets
├── README.md          # basic README
├── requirements.txt   # empty
└── streamlit_app.py   # basic Streamlit template app
```
- Open the project & script in VS Code
- Run the Streamlit app
- Open the app in your browser

So you're ready to start crafting the app!

✨ It's as simple as:

```bash
$ st
```

![downloaded-GIF (1)](https://user-images.githubusercontent.com/7164864/145828632-052ef856-6fb4-4823-9405-9c822fead2fd.gif)


## 🚀 Usage

### Prerequisites

This is a working setup using OSX & VS Code.

### Install

**Using pip:**

Run:
```
$ pip install st-kickoff
```


### Documentation

```
$ st --help

Usage: st [OPTIONS]

Options:
  -p, --path TEXT                 Path where you want to create your Streamlit
                                  project. (Default: ".")

  --open_project_in_vs_code TEXT  Open VS code with the newly created file. (Default: True)
  --run_app TEXT                  Run Streamlit script (Default: True)
  --open_app_in_browser TEXT      Open Streamlit app in browser (Default: True)
  --help                          Show this message and exit.
```

### Get started!

Make a new directory, `cd` in and run:

```
$ st 
```

### Troubleshooting

- Make sure your CLI can access VS Code. See [this link](https://stackoverflow.com/a/40129135/6159698).

- If you get `xcrun: error: invalid active developer path`... error:  
Visit https://apple.stackexchange.com/a/254381 or run:
```
xcode-select --install
```
