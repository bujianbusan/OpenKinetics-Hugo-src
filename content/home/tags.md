+++
# Tag Cloud widget. 主页→标签云
widget = "tag_cloud"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false 打开
weight = 120  # Order that this section will appear. 这部分出现的位置

title = "Popular Topics"
subtitle = "热门话题"

[content]
  # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy = "tags"
  
  # Choose how many tags you would like to display (0 = all tags)
  count = 20

[design]
  # Minimum and maximum font sizes (1.0 = 100%). 设置标签的最小和最大显示
  font_size_min = 0.7
  font_size_max = 3.0
+++
