### XML验证
1. DTD:Document Type Definition 文档类型定义
2. XSD:XML Schemas Definition XML模版定义

#### 验证模式的读取
1. getValidationModeForResource方法获取对应资源的验证模式
2. 自动检查要争模式：XmlValidationModeDetector中的ValidationModeDetector方法

#### 获取Document
1. DocumentLoader是读取Doc的接口，真正读取的是DefaultDocumentLoader
2. DefaultBeanDefinitionDocumentReader中的doRegisterBeanDefinition是真正解析方法