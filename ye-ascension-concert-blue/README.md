# YE Ascension — Concert Blue

Codex 桌面宠物：旋转地球、演唱会人物、黑白奔跑和青蓝飞升光束。

## 安装（Windows）

在 PowerShell 中运行：

```powershell
$dir = Join-Path $env:USERPROFILE '.codex\pets\ye-ascension-concert-blue'
New-Item -ItemType Directory -Force -Path $dir | Out-Null
$base = 'https://raw.githubusercontent.com/SKYCHENV/YE-BEAR-2007/main/ye-ascension-concert-blue'
Invoke-WebRequest "$base/pet.json" -OutFile (Join-Path $dir 'pet.json')
Invoke-WebRequest "$base/spritesheet.webp" -OutFile (Join-Path $dir 'spritesheet.webp')
```

然后在 Codex 宠物列表中选择 **YE Ascension — Concert Blue**；如未出现，重启 Codex。

本项目为粉丝创作，与 Ye 或其团队无官方关联。素材与人物形象的权利可能属于各自权利人；公开访问不代表已授予第三方素材的再利用许可。
