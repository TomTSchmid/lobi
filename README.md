# lobi
Setlists and leadsheats.

{
    "workbench.colorTheme": "Default High Contrast",
    "workbench.tree.indent": 24,
    "workbench.colorCustomizations": {
        "window.activeBorder": "#ff00ff",
        "window.inactiveBorder": "#00ff00",

        "editor.foreground": "#cccccc",
        "editor.selectionBackground": "#3333ff9c",
        "editor.selectionForeground": "#f81be900",
        "editor.findMatchBorder": "#ff0000",
        "editor.findMatchHighlightBorder": "#ff0000",
        "editor.findMatchBackground": "#ff009d9f",
        "editor.findMatchHighlightBackground": "#ff7300c0",
        
        // "editorGroup.border": "#ff0000",
        "editorWidget.border": "#ff0000",
        "editorSuggestWidget.selectedBackground": "#2600ff81",
        // "editor.lineHighlightBorder": "#ff0000",
        // "editorInfo.border": "#ff0000",
        // "editorGroupHeader.tabsBorder": "#ff0000",
        // "editorGroup.border": "#ff0000",
        // "focusBorder": "#ff0000",
        // "focusBorder": "#ff0000",
        "contrastBorder": "#2f00ff",

        
        "editorRuler.foreground": "#335566",
        "editorIndentGuide.background1": "#555555",
        "editorIndentGuide.activeBackground1": "#ff00ff",
        "editorGutter.background": "#19195f",
        
        "tab.activeBackground": "#ff9900bb",
        "tab.activeForeground": "#000000",
        "tab.unfocusedActiveBackground": "#fbff00a2",
        "tab.unfocusedActiveForeground": "#000000",
        
        "diffEditor.insertedTextBackground": "#004400",
        "diffEditor.insertedTextBorder": "#007700",
        "diffEditor.removedTextBackground": "#440000",
        "diffEditor.removedTextBorder": "#770000",
        
        "merge.currentHeaderBackground": "#00b193",
        "merge.incomingHeaderBackground": "#0095da"
    },
    "editor.bracketPairColorization.enabled": true,
    "editor.mouseWheelZoom": true,
    "editor.scrollbar.horizontal": "visible",
    "editor.scrollbar.vertical": "visible",
    "editor.rulers": [
        8,
        32,
        72,
        120,
        200,
        201,
        250,
        300,
        301,
        302,
        350,
        400,
        401,
        402,
        403,
        450,
        500,
        501,
        502,
        503,
        504
    ],
    "latex-workshop.latex.tools": [
        {
            "name": "latexmk",
            "command": "latexmk",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "-pdf",
                "-outdir=%OUTDIR%",
                "%DOC%"
            ],
            "env": {}
        },
        {
            "name": "xelatex",
            "command": "xelatex",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOC%"
            ],
            "env": {}
        },
        {
            "name": "pdflatex",
            "command": "pdflatex",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOC%"
            ],
            "env": {}
        },
        {
            "name": "bibtex",
            "command": "bibtex",
            "args": [
                "%DOCFILE%"
            ],
            "env": {}
        }
    ],
    "latex-workshop.latex.recipes": [
        {
            "name": "pdfLaTeX",
            "tools": [
                "pdflatex"
            ]
        },
        {
            "name": "latexmk 🔃",
            "tools": [
                "latexmk"
            ]
        },
        {
            "name": "xelatex",
            "tools": [
                "xelatex"
            ]
        },
        {
            "name": "pdflatex ➞ bibtex ➞ pdflatex`×2",
            "tools": [
                "pdflatex",
                "bibtex",
                "pdflatex",
                "pdflatex"
            ]
        },
        {
            "name": "xelatex ➞ bibtex ➞ xelatex`×2",
            "tools": [
                "xelatex",
                "bibtex",
                "xelatex",
                "xelatex"
            ]
        }
    ],
    "idf.gitPathWin": "C:\\Users\\tomha\\.espressif\\tools\\idf-git\\2.30.1\\cmd\\git.exe",
    "idf.espIdfPathWin": "C:\\Users\\tomha\\esp\\esp-idf",
    "idf.pythonBinPathWin": "C:\\Users\\tomha\\.espressif\\python_env\\idf5.0_py3.8_env\\Scripts\\python.exe",
    "idf.toolsPathWin": "C:\\Users\\tomha\\.espressif",
    "idf.customExtraPaths": "C:\\Users\\tomha\\.espressif\\tools\\xtensa-esp-elf-gdb\\11.2_20220823\\xtensa-esp-elf-gdb\\bin;C:\\Users\\tomha\\.espressif\\tools\\riscv32-esp-elf-gdb\\11.2_20220823\\riscv32-esp-elf-gdb\\bin;C:\\Users\\tomha\\.espressif\\tools\\xtensa-esp32-elf\\esp-2022r1-11.2.0\\xtensa-esp32-elf\\bin;C:\\Users\\tomha\\.espressif\\tools\\xtensa-esp32s2-elf\\esp-2022r1-11.2.0\\xtensa-esp32s2-elf\\bin;C:\\Users\\tomha\\.espressif\\tools\\xtensa-esp32s3-elf\\esp-2022r1-11.2.0\\xtensa-esp32s3-elf\\bin;C:\\Users\\tomha\\.espressif\\tools\\riscv32-esp-elf\\esp-2022r1-11.2.0\\riscv32-esp-elf\\bin;C:\\Users\\tomha\\.espressif\\tools\\esp32ulp-elf\\2.35_20220830\\esp32ulp-elf\\bin;C:\\Users\\tomha\\.espressif\\tools\\cmake\\3.24.0\\bin;C:\\Users\\tomha\\.espressif\\tools\\openocd-esp32\\v0.11.0-esp32-20221026\\openocd-esp32\\bin;C:\\Users\\tomha\\.espressif\\tools\\ninja\\1.10.2;C:\\Users\\tomha\\.espressif\\tools\\idf-exe\\1.0.3;C:\\Users\\tomha\\.espressif\\tools\\ccache\\4.6.2\\ccache-4.6.2-windows-x86_64;C:\\Users\\tomha\\.espressif\\tools\\dfu-util\\0.9\\dfu-util-0.9-win64;C:\\Users\\tomha\\.espressif\\tools\\esp-rom-elfs\\20220823",
    "idf.customExtraVars": {
        "OPENOCD_SCRIPTS": "C:\\Users\\tomha\\.espressif\\tools\\openocd-esp32\\v0.11.0-esp32-20221026/openocd-esp32/share/openocd/scripts",
        "IDF_CCACHE_ENABLE": "1",
        "ESP_ROM_ELF_DIR": "C:\\Users\\tomha\\.espressif\\tools\\esp-rom-elfs\\20220823/"
    },
    "cmake.configureOnOpen": true,
    "git.openRepositoryInParentFolders": "always",
    "latex-workshop.formatting.latex": "latexindent"
}


# This is Git's per-user configuration file.
[user]
	name = Tom Schmid
	email = Tom_Schmid@gmx.net
[alias]
	co = checkout
	br = branch
	ci = commit -m
	ac = commit -a -m
	ca = commit --amend
	pushf = push --force-with-lease
	st = status
	sm = submodule
	smu = submodule update
	smi = submodule update --init
	cleanSetlist = rm -r --cached setlists
	l1  = log -n 1
	l2  = log -n 2
	l3  = log -n 3
	l5  = log -n 5
	l8  = log -n 8


