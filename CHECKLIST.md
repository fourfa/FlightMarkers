### Pre-Build
* Update AssemblyInfo for <project name> project
* Update `Resources\GameData\Squidsoft Collective\<project name>\<project name>.version`
* Update `Resources\GameData\Squidsoft Collective\<project name>\Changelog.txt`
* Update if required `Resources\GameData\Squidsoft Collective\<project name>\Readme.txt`

### Build
* Build solution in release mode
* Create zip file from `Resources\GameData\` (Squidsoft Collective folder)
* Name the zip file `<project name>-ksp<version>-v<major>.<minor>.<patch>.<build>(pre).zip` (eg <project name>-ksp1.3-v0.1.0.0pre.zip)

### Post-Build
* Verify Github master matches local master
* Create release tag and push to Github
* Update Github release info and add binary
* Update [CurseForge](https://kerbal.curseforge.com/) release
* Update [AVC information](http://ksp-avc.cybutek.net/?page=My_Versions)
* Post update in the [forum thread](http://forum.kerbalspaceprogram.com/)