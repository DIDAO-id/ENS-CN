# 术语

* _Controller_: 可以编辑名称记录的帐户。注册人或控制者可以更改控制者。
* _Label_: 名称的单个组成部分，例如“alice”。
* _Labelhash_: 单个标签的 keccak256 哈希。
* _Name_: ENS 标识符，例如“alice.eth”。名称可以由多个部分组成，称为标签，用点分隔。
* _Namehash_: 用于处理 ENS 名称并返回唯一标识该名称的加密哈希的算法。Namehash 将名称作为输入并生成一个 Node。
* _Node_: 唯一标识名称的加密哈希。
* _Owner_: 名称的所有者是 ENS 注册表的所有者字段中引用的实体。所有者可以转让所有权、设置解析器或 TTL，以及创建或重新分配子域。
* _Registrar_: 注册商是负责分配子域的合约。注册器可以在任何级别的 ENS 中进行配置，并由注册表的所有者字段指向。
* _Registration_: 注册是注册商对用户名称所有权的记录。这与注册表中的所有者字段不同;注册保留在注册商合约中，并额外存储有关到期日期、已支付费用等的信息。
* _Registrant_: 注册的所有者。如果需要，注册人可以转让注册、设置控制者，并在注册表中收回名称的所有权。
* _Registry_: ENS 的核心合约，注册管理机构维护从域名（任何级别 - x、y.x、z.y.x 等）到所有者、解析器和生存时间的映射。
* _Resolver_: 解析器是从名称映射到资源（例如，加密货币地址、内容哈希等）的合约。解析程序由注册表的解析程序字段指向。