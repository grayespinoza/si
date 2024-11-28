<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Grey"
mintoclevel = 2

prepath = "si"

ignore = ["node_modules/"]

generate_rss = true
website_title = "SI | Grey"
website_descr = "materials for supplemental instruction in mathematics"
website_url   = "https://heygrey.dev/si/"
+++

<!--
Add here global TeX commands to use throughout your pages.
-->
\newcommand{\align}[1]{\begin{aligned}#1\end{aligned}}

\newcommand{\bb}[1]{\mathbb{#1}}
\newcommand{\bf}[1]{\mathbf{#1}}
\newcommand{\cal}[1]{\mathcal{#1}}
\newcommand{\rm}[1]{\mathrm{#1}}
\newcommand{\txt}[1]{\text{#1}}

\newcommand{\F}{\bb{F}}
\newcommand{\C}{\bb{C}}
\newcommand{\R}{\bb{R}}
\newcommand{\Q}{\bb{Q}}
\newcommand{\Z}{\bb{Z}}
\newcommand{\N}{\bb{N}}

\newcommand{\e}{\rm{e}}
\newcommand{\i}{\rm{i}}

\newcommand{\d}{\rm{d}}

\newcommand{\deq}{:=}
\newcommand{\map}[3]{{#1}\colon{#2}\to{#3}}
\newcommand{\seq}[3]{{#1}^{#2}_1,\dots,{#1}^{#2}_{#3}}
\newcommand{\ser}[3]{{#1}^{#2}_1+\dots+{#1}^{#2}_{#3}}
