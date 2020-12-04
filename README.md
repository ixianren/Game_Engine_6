# Game_Engine_6
工程文件在master branch中，场景是sketch

1. 将颜色空间由Gamma改为线性，使渲染效果更接近真实环境

2. 使用全局光照使得间接光也被渲染，并通过增加indirect resolution，提高全局光照的分辨率

3. 调整光源的颜色，使选择低饱和度的暖色光，使光的颜色与周围环境相协调（这里采用了橙色光，制造“慵懒的下午"的感觉

4. 调整光源的强度，使光柔和、真实

5. 调整阴影类型为soft shadow，调整baked shadow angle、strength、bias、normal bias等，让阴影更自然柔和

6.设置环境光为color，调整ambient color，提升整体画面氛围

7.增加雾效，设置模式为exp2

8.通过URP管线试用了几种后处理效果

