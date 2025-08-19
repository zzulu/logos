# logos

![demo](demo.gif)

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
| celery | [png](s/celery.png) | | | |
| codeit | [jpg](s/codeit.jpg) | | | |
| codeit-inverse | [jpg](s/codeit-inverse.jpg) | | | |
| codespaces | [png](s/codespaces.png) | | | |
| coupang | [jpg](s/coupang.jpg) | | | |
| docker | [png](s/docker.png) | | | |
| flex | [png](s/flex.png) | | | |
| github | [jpg](s/github.jpg) | | | |
| gitlab | [png](s/gitlab.png) | | | |
| go-mascot | [png](s/go-mascot.png) | [png](f/go-mascot.png) | | |
| google-analytics | [png](s/google-analytics.png) | | | |
| jira-software | [jpg](s/jira-software.jpg) [png](s/jira-software.png) | [png](f/jira-software.png) | | |
| k-digital | [jpg](s/k-digital.jpg) | | | |
| notion | [jpg](s/notion.jpg) [png](s/notion.png) | | | |
| pinia | | | | [svg](svg/pinia.svg) |
| poetry | | | | [svg](svg/poetry.svg) |
| postgresql | | [png](f/postgresql.png) | | |
| python | [jpg](s/python.jpg) | [png](f/python.png) | | |
| redis | [webp](s/redis.webp) | | | |
| slack | [jpg](s/slack.jpg) | | | |
| traefik | [png](s/traefik.png) | | | |
| vite | | | | [svg](svg/vite.svg) |
| vscode | | [png](f/vscode.png) | | |
| vue | | [png](f/vue.png) | | |
| webex | [png](s/webex.png) | | | |
| youtube | [jpg](s/youtube.jpg) | | | |
| (empty) | [png](s/empty.png) | | | |


## Contribution

- Please make a pull request to `main` branch.
- Please make it over 200px in width or height so that it is not difficult to see.
- Please use `jpg` for images with background color(`#ffffff`), and `png` for images without background.
- Please use the following types:
  - `Square`, `s`: Images with same width and height
  - `Fit to Content`, `f`: Images with no padding on top, bottom, left, and right
  - `Padding with content`, `p`: Images with padding on top, bottom, left, and right
  - `SVG`, `svg`: SVG images
