1.快捷输入插件使用 emmet
===============================
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
 b.使用说明
  
  子级 div>p
  同级 div+p
  乘法 div*4
  自定义属性 div[title='name']
  
