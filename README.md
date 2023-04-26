# EasyPact

#include "easyProtocol.h"
使用示例:
{
        static frame_t senbuf;
        easy_set_header(&senbuf, yourheader)
        easy_set_address(&senbuf, youraddress));
        easy_set_id(&senbuf, yourid);

        easy_wipe_data(&senbuf);
        easy_add_data(&senbuf, data1, 4);
        easy_add_data(&senbuf, data2, 2);
        easy_add_data(&senbuf, data3, 1);
        easy_add_check(&senbuf);
}