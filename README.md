# gophersfrm.netlify.com

## Developing

1. Install [GoHugo](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)
2. initalize submodules

    ```shell
    git submodule update --init --recursive
    ```

3. Start GoHugo

    ```shell
    hugo server -D
    ```
## Add Content

Use the Hugo command `hugo new content $PATH` to create new content. 
For example to create a new post for a meetup use the following command: `$ hugo new content meetups/filename.md`.   

## Version

| Version | Description           |
|---------|-----------------------|
| 0.3.0   | Add meetups overview  |
| 0.2.0   | Add hosts             |
| 0.1.0   | First running version |
