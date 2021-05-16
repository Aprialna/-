# -基于动态表示的注意力机制序列推荐方法研究方法主要包含三个方法的代码
（1）基于自适应注意力感知门控循环单元的序列推荐方法，借助目标物品的信息构建了一种计算用户交互与目标物品相关性的自适应注意力机制，并将自适应注意力机制应用于门控循环单元的输入层和隐藏层
构建用户的动态表示，以建模用户偏好的多样性。
（2）基于协同自注意力网络的会话推荐方法首先根据会话中的每个物品生成邻居会话，并加权融合邻居会话中包含的协同信息来构建物品的动态表示，再输入到自注意力网络中学习交互间复杂的依赖关系，
在应用协同信息的同时构建物品的动态表示，使同一个物品对不同用户而言表示不同。
（3）基于自适应协同自注意力网络的会话推荐方法考虑了长会话中用户多意图情况，将物品的动态表示和会话的动态表示相结合，建模用户偏好的动态性和多样性。
