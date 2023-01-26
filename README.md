# Logos

## Usage

- Should be lowercase:

  ```
  https://zzu.lu/logos/{type}/{name}.{jpg|png}
  ```

  - Example:

    ```
    https://zzu.lu/logos/s/github.jpg
    ```

- If you want to download:

  ```bash
  curl https://zzu.lu/logos/s/python.jpg --output output.jpg
  ```


## List

- Sorted by name, ascending

| Name | (S)quare | (F)it to content | (P)adding with content | SVG |
| ---- | ---- | ---- | ---- | ---- |
| codespaces | [png](s/codespaces.png) | | | |
| coupang | [jpg](s/coupang.jpg) | | | |
| flex | [png](s/flex.png) | | | |
| github | [jpg](s/github.jpg) | | | |
| gitlab | [png](s/gitlab.png) | | | |
| go-mascot | [png](s/go-mascot.png) | [png](f/go-mascot.png) | | |
| google-analytics | [png](s/google-analytics.png) | | | |
| jira-software | [jpg](s/jira-software.jpg) [png](s/jira-software.png) | [png](f/jira-software.png) | | |
| k-digital | [jpg](s/k-digital.jpg) | | | |
| notion | [jpg](s/notion.jpg) [png](s/notion.png) | | | |
| hphk | [jpg](s/hphk.jpg) | [png](f/hphk.png) | [jpg](p/hphk.jpg) [png](p/hphk.png) |  |
| hphk-h | [jpg](s/hphk-h.jpg) | | | |
| hypergrowth | [jpg](s/hypergrowth.jpg) | [png](f/hypergrowth.png) | |
| poetry | | | | [svg](svg/poetry.svg) |
| postgresql | | [png](f/postgresql.png) | | |
| python | [jpg](s/python.jpg) | [png](f/python.png) | | |
| slack | [jpg](s/slack.jpg) | | | |
| vite | | | | [svg](svg/vite.svg) |
| vscode | | [png](f/vscode.png) | | |
| webex | [png](s/webex.png) | | | |
| youtube | [jpg](s/youtube.jpg) | | | |


## Contribution

- Please make a pull request to `main` branch.
- Please make it over 200px in width or height so that it is not difficult to see.
- Please use `jpg` for images with background color(`#ffffff`), and `png` for images without background.
- Please use the following types:
  - `Square`, `s`: Images with same width and height
  - `Fit to Content`, `f`: Images with no padding on top, bottom, left, and right
  - `Padding with content`, `p`: Images with padding on top, bottom, left, and right
  - `SVG`, `svg`: SVG images
