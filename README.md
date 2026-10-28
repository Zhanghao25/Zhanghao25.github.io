# Zhanghao Chen - Academic Homepage

Personal academic website of Zhanghao Chen, Ph.D. student at HKUST(GZ).

Built with plain HTML + CSS. No frameworks, no build step.

The page loads a fingerprinted copy of `assets/css/style.css` to prevent cached styles from being mixed with newer HTML. When changing CSS, create `assets/css/style.<sha256-prefix>.css` with the same content and update the stylesheet link in `index.html`. Keep `style.css` available for older page requests.
