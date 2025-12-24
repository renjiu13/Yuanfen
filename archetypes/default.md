+++
# ==============================================================================
# 文章模版 (archetypes/default.md)
# 作用：执行 `hugo new posts/xxx.md` 命令时，会自动使用此模版生成新文件的 Front Matter。
# ==============================================================================
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++
