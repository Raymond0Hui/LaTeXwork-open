Triple_SOS�����䷽����װ˵��
��˵���ĵ����¿��԰���������python����ʹ����Triple_SOS

���ߣ�����
˵���ĵ������ڳ���
ʱ�䣺20220326
ϵ������Ⱥ��875413273
ϵͳ��Windows 7 64λ


��װpython-3.7.5-amd64.exe

�򿪰�װĿ¼(C:\Users\Administrator\AppData\Local\Programs\Python\Python37)......(a)
��(C:\Users\Administrator\AppData\Local\Programs\Python\Python37\Scripts)......(b)

Triples Code 20220218��������ߵ�Դ���룬���临�Ƶ�(a)
��patch1��������ļ��滻��(a)(ֻ�����������������pyside2����ΪPySide6���ò���)

(b)�¸�Ŀ¼Ϊcmd���������룺

pip -V

pip.exe config set global.index-url https://mirrors.aliyun.com/pypi/simple/

pip.exe install --upgrade pip

pip -V

pip.exe install sympy
pip.exe install numpy
pip.exe install scipy
pip.exe install pyside2
pip.exe install matplotlib

(a)������python.exe graphics_main.py

���û��LaTeX����patch2���sos_manager.py�滻��(a)(������line 431)

�Ժ�Ϳ���ֱ��˫����python.exe graphics_main.py��(�ɴ�����ݷ�ʽ)