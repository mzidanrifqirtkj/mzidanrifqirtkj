<h1 align="center">Hi, I'm Muhammad Zidan Rifqi Ramadhan</h1>
<h3 align="center">A passionate backEnd developer from Indonesia</h3>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=mzidanrifqirtkj&show_icons=true&locale=en&layout=compact" alt="mzidanrifqirtkj" /></p>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ mzidanrifqirtkj }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9


