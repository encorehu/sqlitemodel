# sqlitemodel

给aardio封装了一个sqlite的增删改查的库

    item={
        id=5;
        name="fadf";
        code="fadf"
    }


    model.create(item)  //创建一条数据
    model.get(item);    //查询数据
    model.filter(item); //根据配置好的filter_fields过滤数据
    model.update(item); //根据id更新数据
    model.delete(item); //根据id删除数据
    model.search(item); //根据配置好的search_fields搜索数据

东西写了很久, 但是一直有各种错误

目标就是：
1. 增删改查少操心（console下可用）
2. 直接生成界面（增删改查的界面自动生成）
3. 和Excel互相批量导入导出

以上3个基本实现，还有待完善。
