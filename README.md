﻿# PRD2018-G07  
  

1.要求：  
    （1）建整合分支，小组长分配任务，整合人员在integration分支发布相关任务模板；  
    （2）小组每人自建分支，首先从integration分支上拉取任务相关信息，完成分配的任务后各自交到自己分支上；  
    （3）最后由整合人员负责整合并提交到integration分支。   
	注：小组成员（非组长）只保留自己的分支。如果需要查看其它成员分支，只能在本地新建分支拉取查看，不能推送。    
	
2.sourthtree签名信息更改，路径：设置-高级-用户信息，格式改为学号+姓名  
     
3.提交场景

＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋■场景一■＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋
场景1：提交个人作业  
权限：项目组所有成员
示例：新增个人作业《人月神话》读后感[新增的内容：1、位置+新增了什么 | 2、]（待修改的内容：XXXXX）
过程：在工作前拉取远端的最新integration分支，并以此为基础编辑，提交到自己对应的远程分支。审查无误后提醒integration分支进行合并。 
－－－－－－－－－－－－－－－－－－－－－－－－－○END○－－－－－－－－－－－－－－－－－－－－－－－－－－
＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋■场景二■＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋

场景2：协同编写某文档的0.X.0版本
 
权限：项目组所有成员
 
示例：修订《项目总体计划v0.1.0》[更改的内容：1、位置+更改了什么 | 2、]（待修改的内容：XXXXX）
 
过程：在工作前拉取远端的最新integration分支，并以此为基础编辑，提交到自己对应的远程分支。审查无误后提醒integration分支进行合并。
 
－－－－－－－－－－－－－－－－－－－－－－－－－○END○－－－－－－－－－－－－－－－－－－－－－－－－－－
 

 
＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋■场景三■＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋
 
场景3：提交由一个人负责的文件
 
权限：项目组所有成员示例：新增《项目计划甘特图》[新增的内容：1、位置+新增了什么 | 2、]（待修改的内容：XXXXX）
 
过程：在工作前拉取远端的最新integration分支，并以此为基础编辑，提交到自己对应的远程分支。审查无误后提醒integration分支进行合并。
 
－－－－－－－－－－－－－－－－－－－－－－－－－○END○－－－－－－－－－－－－－－－－－－－－－－－－－－
 

 
＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋■场景四■＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋
 
场景4：更新现有文件
 
权限：项目组所有成
 
示例：修订《项目总体计划v0.1.0》[更改的内容：1、位置+更改了什么 | 2、]（待修改的内容：XXXXX）
 
过程：在工作前拉取远端的最新integration分支，并以此为基础编辑，提交到自己对应的远程分支。审查无误后提醒integration分支进行合并。
 
－－－－－－－－－－－－－－－－－－－－－－－－－○END○－－－－－－－－－－－－－－－－－－－－－－－－－－
 

 
＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋■场景五■＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋
 
场景5：提交整合的[v0.X.0]文档（仅在合并协同编写的文档时使用，其他时候使用默认注释）
 
权限：git配置管理员
 
示例：整合《可行性分析v0.1.0》（2/3）
 
过程：整合各个成员的工作成果到本分支，提交到远程integration分支，通知master分支进行合并。审查无误后提醒integration分支进行合并。
 
－－－－－－－－－－－－－－－－－－－－－－－－－○END○－－－－－－－－－－－－－－－－－－－－－－－－－－
 
 

 
＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋■场景六■＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋
 
场景6：对文件命名进行整改
 
权限：项目组所有成员
 
示例：改名（《A文件名》->《B文件名》）
 
过程：提交后推送到当前分支的远程分支
 
－－－－－－－－－－－－－－－－－－－－－－－－－○END○－－－－－－－－－－－－－－－－－－－－－－－－－－
 

 
＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋■场景七■＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋＋
 
场景7：提交会议纪要/录音
 
权限：会议记录员、会议记录员
 
示例：提交《20181031第X次会议纪要/录音》
 
 
过程：直接提交到master分支并推送到远程master分支
 
－－－－－－－－－－－－－－－－－－－－－－－－－○END○－－－－－－－－－－－－－－－－－－－－－－－－－－
 
 eg：31601378赵伟宏 、31601345陈帆
