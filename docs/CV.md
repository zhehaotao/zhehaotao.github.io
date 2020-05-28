 <center>
     <h1>陶浙颢</h1>
     <div>
         <span>
             <img src="../assets/envelope-solid.svg" width="18px">
             zhtao@ucdavis.edu
         </span>
         ·
         <span>
             <img src="../assets/github-brands.svg" width="18px">
             <a href="https://github.com/zhehaotao">zhehaotao</a>
         </span>
     </div>
 </center>


 ## <img src="../assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 性别：男；出生年月：1998.01

## <img src="../assets/graduation-cap-solid.svg" width="30px"> 教育经历

浙江大学  本科                                                                                                                                 2016.09-2020.07

* 专业方向：飞行器信息与电子；GPA：3.56/4

加州大学戴维斯分校  交流生                                                                                                          2019.03-2019.08

* 修读课程：数据结构基础，计算机网络，算法设计；GPA：3.67/4

## <img src="../assets/tools-solid.svg" width="30px"> 技能清单

- 熟悉HTML和CSS，能根据设计原稿完成网页的构建。
- 熟悉JavaScript以及ES6标准的新特性，能写出清晰的代码。  
- 了解React，Bootstrap等前端框架，有使用React及相关技术栈Redux的开发经验。
- 了解Node.js，有使用Express框架写出符合Restful规范的后端API的经验。
- 熟悉Python，有使用相关开源软件的科研经历。
- 拥有扎实的计算机网络基础，有软件定义网络SDN的研究经历。
- 拥有良好的英语阅读能力（托福100），熟悉使用Google、Stack Overflow和官方文档解决问题。 
- 拥有优秀的自学能力，能迅速掌握新技术，爱好自学新技术。  

## <img src="../assets/project-diagram-solid.svg" width="30px"> 项目经历

* [E-commerce Shop](https://e-commerce-world.herokuapp.com/)                                                        https://github.com/zhehaotao/E-commerce-Shop-App

  *React, Redux, Firebase, Stripe*

  E-commerce Shop是一个集选购商品和在线支付为一体的电商网站。项目基于React框架进行开发，使用了Redux技术栈进行状态管理。优化难点在于避免冗余计算并减少组件渲染压力，我通过引入Redux中间件reselect来选取状态，使得无关状态变化时无需重新渲染组件。同时，我通过styled-component库引入模块化CSS，避免了因为CSS全局命名空间而可能存在样式冲突的问题。
  
* [Share Trip](https://sharetripworld.herokuapp.com/)                                                                                             https://github.com/zhehaotao/Share-Trip

  *Bootstrap 4, ejs, Node.js, Express, MongoDB*

  Share Trip是一个用于分享旅行的社交网站，认证登录后的用户能够在网站上晒出自己的旅行照片，也能够在他人的分享下面评论和点赞。项目采用了Bootstrap 4来设计前端UI界面，选用Node.js的Express框架为后端，MongoDB为数据库存储用户及旅行信息。项目把判断用户登录状态和旅行归属等逻辑放在中间件，有效地减少了代码冗余。通过这个全栈项目，我对前后端的交互有了更深的理解。
  
* 基于SDN的跨网段通信研究

  *Python, Mininet, Ryu, OpenFlow*

  基于软件定义网络的跨网段控制器解决了在同一个SDN网络下不同网段主机之间的通信问题。项目的难点在于SDN网络二三层之间的界限非常模糊，我在阅读OpenFlow协议的基础上设计了一种用SDN控制器来模拟网关行为并伪造ARP请求的方法，并基于Ryu控制器进行二次开发实现了跨网段通信。该研究成果为SDN实现网络层及以上的控制提供了进一步研究的基础。

* 基于IEEE 802.11的无线局域网仿真分析

  该项目通过建立拓扑模型，分析计算了无线局域网中的主机在CSMA/CA协议下的吞吐率和延迟数据，结果与理论符合得较好。我在项目中领导了组员多次进行讨论，并确定了相应的技术方法和实现过程。