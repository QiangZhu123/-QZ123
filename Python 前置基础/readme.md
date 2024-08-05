
#  请实现一个wordcount函数，统计英文字符串中每个单词出现的次数。返回一个字典，key为单词，value为对应单词出现的次数。
    from collections import Counter
    import re

    def wordcount(word):
        test = re.findall(r'\b\w+\b', word)
        a = Counter(test)
        return a

#  请使用本地vscode连接远程开发机，将上面你写的wordcount函数在开发机上进行debug，体验debug的全流程，并完成一份debug笔记(需要截图)。

![image](https://github.com/user-attachments/assets/3325a32f-d162-42d3-95cc-88804533f6b8)


![image](https://github.com/user-attachments/assets/e9e11bd1-7816-4cc2-9338-543394494150)


![image](https://github.com/user-attachments/assets/35ae2d8c-1ac3-4a90-861b-2626f5055074)


![image](https://github.com/user-attachments/assets/52832a4e-4c09-4822-8438-dff47bf7b416)

![image](https://github.com/user-attachments/assets/723d0b35-47de-44f7-bec6-8418c775ac66)




