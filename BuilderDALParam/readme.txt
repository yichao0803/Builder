﻿v0.4 2016-05-09
1.BLLComm 注释  if (DbType == "Oracle") strclass.AppendSpaceLine(2, " int iErrorCode = 1;");

v0.3 2015-12-29 
1.BLLComm 增加 DataRowToModel方法

v0.2 2015-10-21 zhangyichao
1、删除BLLComm 数据验证
2、更新BuilderDALSQL的代码 匹配 DALParam

v0.1 2015-09-15  zhangyichao
1.增加IDAL/DALParam  Oracle 分页和计数方法 GetRecordCount；GetListByPage
2.增加IDAL/DALParam  MySQL	分页和计数方法 GetRecordCount；GetListByPage
3.修复IDAL/DALParam/BLLComm   MySQL	Add方法返回类型为int等于自增ID 
4.注释BLLComm  Update 按参数修改  2015-09-15 张义超 不可用
5.修复IDAL/DALParam/BLLComm/Model   Mysql 实体类文件和Model为大写 其中Model层类名 强制大写
6.增加IDAL/DALParam   转换List方法 DataTableToList；GetModelList

