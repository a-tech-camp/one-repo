## One Repo

This is an universal repository for codebases.

## Prerequisites
### Visual Studio Code (VSCode)
VSCode is our recommended editor. Check out the recommended extensions recommended in [vscode/extensions.json](./vscode/extensions.json)

## Development
### Images
To build an image type:
```
docker build .
```

To run the image, take the image-id that was outputted above and type: 
```
docker run <image-id>
```

In one line this can be:
```
docker build . -t one-repo/latest; docker run one-repo/latest
```
