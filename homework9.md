# 领域建模-模型验证与面向资源的API设计

## 使用 UMLet 建模

- 1. 使用类图，分别对 Asg_RH 文档中 Make Reservation 用例以及 Payment 用例开展领域建模。然后，根据上述模型，给出建议的数据表以及主要字段，特别是主键和外键
  * 注意事项：
      + 对象必须是名词、特别是技术名词、报表、描述类的处理;
      + 关联必须有多重性、部分有名称与导航方向;
      + 属性要注意计算字段.
      
      
  * 数据建模，为了简化描述仅需要给出表清单，例如：
      + Hotel（ID/Key，Name，LoctionID/Fkey，Address…..） 
      
  
**Make Reservation领域模型:**

  
