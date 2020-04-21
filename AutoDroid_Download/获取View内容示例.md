AUTODROID_DOWNLOAD=var view = findView('10') //先找一个view
view=JSON.parse(view) //转换view字符串为viewJSON对象
log(‘view的text: ’+view.text) //把view的文本打印到日志
log(‘view的size: ’+view.size) //把view的大小打印到日志
