Sakarya Üniversitesi SAUX (Open edX)
========
Sakarya Üniversitesi Open edX platformu için şablon çalışmasıdır.

Sizde Open edX için özel bir tema tasarlayabilirsiniz. Bunun için edX alt yapısına hakim olmanız gerekmektedir. Sakarya Üniversitesi için hazırlanmış olduğum şablonu dilerseniz sizde kullanabilirsiniz. Kurulum ile ilgili ayrıntılara aşağıdan ulaşabilirsiniz.

![Alt text](/default_theme_screenshot.jpg?raw=true "Open edX Default Theme Screenshot")

Şablon Hakkında
===============
To customize your theme:
- Fork this repository.
- Clone it into the theme directory next to your edx-platform directory and rename the theme directory to your new theme's name.
- Upload your own image assets.
- Edit the .scss file in static/sass/ and rename the file with your theme's name.
- Edit the lms.envs.json file in edx-platform and set 'USE_CUSTOM_THEME' to true, and 'THEME_NAME' to your theme's name.
