## 以太坊是什么？

以太坊是一个开源的区块链平台，在这个平台上任何人都可以构建和使用基于区块链技术的去中心化应用，如比特币。没有哪一个人可以控制或拥有以太坊，因为它是一个由许多人共同构建的开源项目。不同于比特币的是，以太坊更加灵活。在以太坊平台上创建应用非常容易，而随着Homestead的发布，使用这些应用也变得更加安全。

## 下一代区块链

区块链技术是比特币的基础。它第一被描述是在中本聪于2008年发布的白皮书《一种点对点的电子货币系统》一书中。尽管在原文中对于区块链的应用进

布式计算架构，其中，每个网络节点都执行并记录相同的事务（这些事务是由组分成块的）。一次只能添加一个区块，每个区块都包含了数字证明，用于验证该区块与其前一区块是否按顺序排列的。这样，区块链中的分布式数据库在全网中保持一致。个人用户与分类账的交互通过强密码保证安全。Nodes that maintain and verify the network are incentivized by mathematically enforced economic incentives coded into the protocol

在比特币中分布式数据库被构想成“账户余额表”（分类账）。比特币的交易是通过比特币token之间的转移来达到个人之间的无信任金融交易。随着越来越多的开发者和专家关注比特币，。。。。。。。

2014年，以太坊创始人开始构建下一代区块链技术：一种完全的无须信任的智能合约。

## 以太坊虚拟机

以太坊是一种可编程的区块链。与只给用户事先定义好的操作指令不同的是，以太坊允许用户创建自己的操作。如此一来，它提供了一个可以运行多种类型的去中心化的区块链应用的平台。

狭义上理解，以太坊是定义了去中心化应用平台的一套协议。它的核心是“以太坊虚拟机（EVM）”。在计算机学上，以太坊是“图灵完全”@的。开发者可以使用如JavaScript和Python之类的语言开发应用，运行在EVM上。

如其他区块链技术一样，以太坊同样包含了点对点的网络协议。以太坊的区块链数据库由许许多多连接到网络的节点维护和更新。每个节点都运行在EVM上并执行相同指令。因此，以太坊也被描述为“世界计算机”。

整个以太坊网络中的这种大规模的并发计算并不能使计算效率更高。事实上，这种过程反而使计算更慢同时也更贵。去中心化让以太坊拥有极强的容错能力，保证了零宕机，数据存储在区块链上永远不会改变并且能够抗审查。

以太坊平台本身无特性、无价值。同开发语言一样，它的价值由企业家和开发者决定。

以太坊适合于点对点间自动直接交互，适合于网路中跨组间协作。

比特币能使个人间不通过中间金融机构而直接交易。以太坊的影响可能会更近一步。理论上，通过代码可以在以太坊自动运行任何复杂的金融交易。除了金融方面的应用，任何涉及到信任、安全和持久化等特性的地方都可以使用以太坊，如，资产登记、投票等。

## 以太坊如何工作？

以太坊引入了许多比特币的特性和技术。同时也做了许多改变和革新。

同比特币的区块链技术是一串纯粹的交易不同，以太坊的最小单元是账户。以太坊的区块链技术追踪每一个账户的状态。所有状态的转换都是账户间价值和信息的转移。账户有两种类型：

* EOA\(Externally Owned Accounts\),由私钥控制；
* 合约账户\(Contract Accounts\),由合约代码控制，并且只能被EOA激活

对大多数用户来说，它们之间最基本的不同是：EOA由用户控制，因为用户掌握着私钥，而私钥是用来控制EOA的。而合约账户由内部代码管理。如果合约账户被用户控制，那一定是它们被编码由给定地址的EOA控制，而控制权又由EOA转移到用户手中。流行术语“智能合约”指的是：账户中的一段代码，这段代码在当一笔交易发送到账户时执行。用户可以通过在区块链上部署代码来创建新的合约。

合约账户只有在EOA发出指示后才进行操作。这是因为以太坊要求节点的计算结果能够一致，所以，这就需要在严格确保下执行。

和比特币一样，以太坊也需要用户在网络上交易时支付一笔小的费用。这是为了防止恶意的计算任务，如DDoS攻击或。交易的请求者需要为他们所激活的每一步付费，包含计算任务和存储。这些费用由以太坊本地价值标记（value-token）按数量支付。

这些费用由验证的网络节点收集。以太坊节点上的“旷工”们接受、传播、验证和执行这些交易。旷工们将这些交易组织起来，这些交易包含了许多账户“状态”的更新，然后这些更新被提交进所谓的“块”\(blocks\)，旷工们互相竞争，确保自己的块是下一个添加到区块链的。这种行为就是所谓的挖矿，旷工们每挖到一个块，都会得到相应奖励。

同比特币一样，旷工的任务在于解决复杂的运算问题。这就是我们所熟知的“工作证明”。任何计算任务都需要大量的资源来解决算法上的问题。提供这些资源的多寡，就是您工作多寡的证明。为了防止那些使用专门的设备集中挖矿的行为\(比特币上常常发生\)，以太坊选择了耗内存的计算任务。如果解决任务需要内存以及CPU，那么理想的设备恰恰是一般的计算机。这使以太坊的工作证明更具有耐性（更多分散的挖矿行为比使用专门的设备集中挖矿更加安全）。

