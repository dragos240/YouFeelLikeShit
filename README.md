# You Feel Like Shit - An interactive self-care flowchart

Taken from [the original Twine site](https://philome.la/jace_harr/you-feel-like-shit-an-interactive-self-care-guide/play/index.html).

## Compiling
Use `go get` to compile the twee file:
```
go get github.com/tmedwards/tweego
```

Get the [Twine storyformats](https://github.com/tmedwards/tweego/releases/tag/v2.1.1) for your OS. Extract the `storyformats` directory to the repository root. The end directory structure should look like this:
```
.
├── README.md
├── YouFeelLikeShit.twee
└── storyformats
```

Compile the twee file:
```
tweego -o YouFeelLikeShit.html YouFeelLikeShit.twee
```

## Usage
Open the `YouFeelLikeShit.html` file with a web browser to use it.
