+++
# Slider widget. 主页→显示 播放幻灯片 【打开】
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false 打开
weight = 1  # Order that this section will appear. 出现的顺序位置

# Slide interval. 动画滑动
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional). 设置显示高度
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "300px"

# Slides. 幻灯片单张设置
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "OpenKinetics"
  content = "I am center aligned :smile:"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional). 设置显示的颜色和图像
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/bubbles-wide.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional). 设置按钮
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Download"
  cta_url = "https://sourcethemes.com/academic/"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap" # 设置按钮上显示的图标

[[item]]
  title = "仪器"
  content = "显示仪器照 :smile:"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/bubbles-wide.jpg"   # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "案例分析"
  content = "显示应用案例 :smile:"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "headers/bubbles-wide.jpg"   # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
