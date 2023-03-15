# CodeShot Landing Page

Currently, evenything is being done via GitHub Pages, deploying from the main branch.

## DNS Configuration

Add the following records:

| Name              | Type          | TTL   | Priority | Content             |
| -------------     | ------------- | ----- | -------- | ---------------     |
| codeshot.net      | A             | 86400 | 0        | 185.199.108.153     |
| codeshot.net      | A             | 86400 | 0        | 185.199.109.153     |
| codeshot.net      | A             | 86400 | 0        | 185.199.110.153     |
| codeshot.net      | A             | 86400 | 0        | 185.199.111.153     |
| www.codeshot.net  | CNAME         | 86400 | 0        | code-shot.github.io |

Where the A record IP addresses are given [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain)

## GitHub Configuration

Under the repository [Settings -> Code and Automation -> Pages](https://github.com/code-shot/codeshot-landing/settings/pages) set the Custom Domain to `codeshot.net`
