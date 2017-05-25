1.快捷输入插件使用 emmet
===============================
  引用博客地址：http://blog.csdn.net/rovast/article/details/45647887
  <br/>
 a.修改快捷键为tab<br/>
 `
   [
      {
        "keys": [
        "tab"
        ], 
        "args": {
        "action": "expand_abbreviation"
        }, 
        "command": "run_emmet_action", 
        "context": [
        {
        "key": "emmet_action_enabled.expand_abbreviation"
        }
      ]
      }
]
`
<br/>
 b.使用说明
  
  子级 div>p <br/>
  同级 div+p <br/>
  乘法 div*4 <br/>
  自定义属性 div[title='name']<br/>
  
