## �����ļ����ļ�ϵͳ�Ĳ���

#### ����ָ����С���ļ�

```
with open(filename, 'w') as f:
    f.seek(2 ** 10)  # 1GB
    f.write(chr(0))
```
