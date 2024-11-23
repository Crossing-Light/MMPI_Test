原项目已经相当完善，测验流程安排合理，结果呈现完整，剖图美观。

希望改进的是（开始画饼）：

- 女性Mf分数计算错误。最快的改法就是计算照常，但是之后用100去减；
- 直接拿临床量表最高的两个分数作为两点编码不妥，量表分数必须超标才能进入编码；
- 把矛盾题对数作为Q分数不妥（这里是迫选，所以Q分数必为0，直接把Q删掉即可，移花接木合理性不大），应称为重测指数TR，但不如直接叫矛盾题对数来得简明。

不知道什么时候有闲心来搞这东西。

# MMPI_Test
明尼苏达多相人格测试（MMPI）Python3命令行版<br>

明尼苏达多项人格测验（Minnesota Multiphasic Per-sonality Inventory，简称MMPI）是由明尼苏达大学教授哈瑟韦（S．R．Hathaway）和麦金力（J．C．Mckinley）于40年代制定的，是迄今应用极广、颇富权威的一种纸-笔式人格测验。该问卷的制定方法是分别对正常人和精神病人进行预测，以确定在哪些条目上不同人有显著不同的反应模式，因此该模型可以用于测试正常人的人格类型，也可以用于区分正常人和精神疾病患者。经过数十年的改良与修订，纪术茂先生带领其团队于1980年正式推出了基于中国常模的MMPI，虽然距今年代久远可能不能完全适用于现代中国人的人格分析，但根据实际应用情况仍具有较高的准确性和临床价值。<br>

## 本程序的主要功能包括
1. 完整的测试内容
2. 记录原始问卷
3. 生成统计分报表
4. 生成人格剖面图  

## 本程序所需的库包括： 
1. time（用于测试计时与程序内定时）
2. matplotlib（用于绘制人格剖面图）
3. openpyxl（用于形成评分表格）

### 注意：本程序需在专业人士指导下使用并解读，其结果才具有临床价值。  

## 相关资料与引用文献：

>[1] Schiele, B. C.; Baker, A. B.; Hathaway, S. R. (1943). "The Minnesota multiphasic personality inventory"[J]. Journal-Lancet (63): 292–297. ISSN 0096-0233.<br>
>[2] Hathaway, S. R., & McKinley, J. C. (1940). A multiphasic personality schedule(Minnesota): I. Construction of the schedule[J]. Journal of Psychology, 10, 249-254.<br>
>[3] Hathaway, S. R., & McKinley, J. C. (1942). A multiphasic personality schedule (Minnesota): II. A differential study of hypochondriasis[J]. Journal of Psychology, 10,255-268.<br>
>[4] McKinley, J. C, & Hathaway, S. R. (1940). A multiphasic personality schedule (Minnesota): III. The measurement of symptomatic depression[J]. Journal of Psychology, 14, 73-84.<br>
>[5] McKinley, J. C, & Hathaway, S. R. (1942). A multiphasic personality schedule (Minnesota): IV. Psychasthenia[J]. Journal of Applied Psychology, 26, 614-624.<br>
>[6] McKinley, J. C, & Hathaway, S. R. (1944). A multiphasic personality schedule (Minnesota): V. Hysteria, Hypomania, and Psychopathic Deviate[J]. Journal of Applied Psychology, 28, 153-174.<br>
>[7] 纪术茂, 戴郑生. 明尼苏达多项人格调查表——最新研究与多类量表解释[M].北京: 科学出版社, 2004.  
