# Hot-Dump-Statstics-Database

#⼆进制⽂件基本操作：

DataFileHandler::open() 若⽂件存在，则打开⽂件；若⽂件不存在，则创建⽂件

DataFileHandler::append() 每次插⼊的新数据，Append 在⽂件末尾，避免对⽂件随机读写，提⾼性能

DataFileHandler::read_line() 从指定⾏数开始读取⼀⾏数据，返回⼆进制信息 int*

#表的元数据管理：

TableMeta::TableMeta() 根据表的元数据创建对象，元数据包括：表名、列名、主键、表⽂件存储路径等

TableMeta::save()/load() 将元数据存储在⽂件中 / 从⽂件中加载元数据

#待完善...
