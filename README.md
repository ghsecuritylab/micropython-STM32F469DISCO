micropython for STM32F469DISCO board!

���뵽stm32Ŀ¼��Ȼ��make�Ϳ���������д�ļ�
cd ports/stm32
make

���ļ���д��STM32F469�������м���
1.�Ѿ�������SDRAM��micropython����ʹ�õ�RAM��16MByte��
2.����tfcard������֧�֣����������tf�����ɸ��ٷ�һ�����ڲ�flash�����U�̡�

��������������ʾ��
MicroPython v1.9.4-631-g338635c-dirty on 2018-11-09; F469I-DISCO with STM32F469
Type "help()" for more information.
>>> import micropython
>>> micropython.mem_info()
stack: 492 out of 80896
GC: total: 16392960, used: 1248, free: 16391712
 No. of 1-blocks: 13, 2-blocks: 8, max blk sz: 40, max free sz: 1024470
>>>