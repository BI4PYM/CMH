# CMH
Communication Mode Hierarchy

通信方式层级结构

'CMH' 是用于描述各种通信方式之间关系的模型，类似于OSI模型，分为 '介质层' '信道层' '调制层' '接口层' '信息层' '封装层' '界面层' 共七层。

每层元素可向下包含，高层元素利用低层元素。不同元素包含的下层元素可能不同。

层间/层中关系并不是绝对严格，可根据需要灵活调整。

'CMH' is a model used to describe the relationship between various communication modes, similar to the OSI model. It is divided into seven layers: 'media layer' , 'channel layer' , 'modulation layer' , 'interface layer' , 'information layer' , 'encapsulation layer' and 'interface layer' . 

Each layer of elements can be contained downwards, while high-level elements utilize low-level elements. Different elements may contain different lower level elements. 

The inter layer/inter layer relationships are not absolutely strict and can be flexibly adjusted as needed.
## 本地化规范
本地化文件夹应在 './localization' 目录下，文件夹命名规范采用 'RFC 4646' http://www.ietf.org/rfc/rfc4646.txt

本地化文件夹根目录包含 'README.md' 文件，内容包含以对应语言表述的 './localization/zh_Hans/README.md' 文件内容。

本地化文件夹根目录包含用于容纳各层级元素示例的七个文件夹，文件夹名如 '1_介质层' 。

各层级文件夹下包含对应层级元素的文本文件，文件名如 'RTTY.md' ，使用对应语言介绍对应元素的协议标准、相关链接和相关信息等。

各本地化文件夹可参考 './localization/zh_Hans/' 文件夹。

##Localization specifications
Localized folder should be located in '/ Under the 'localization' directory, the folder naming convention adopts 'RFC 4646' http://www.ietf.org/rfc/rfc4646.txt

The root directory of the localized folder contains the 'README.md' file, which contains the content expressed in the corresponding language './localization/zh_Hans/README.md' file content.

The root directory of the localized folder contains seven folders for holding examples of elements at each level, with folder names such as '1_MediumLayer' .

Text files containing corresponding level elements in each level folder, with a file name such as 'RTTY.md ' , using the corresponding language to introduce the protocol standards, related links, and information of the corresponding elements.

Each localized folder can refer to './localization/zh_Hans/' folder.