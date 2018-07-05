# web
------可行性分析-------
===============================
 （1）系统安全性
 ------------------------------
      该系统是针对学生信息的管理，使用人数较多，所以系统应该有很好的权限管理，不同权限进入不同的操作界面。为了防止数据的并发，数据的编辑必须合法的用户来操作，并对所有的信息进行保密。
 （2）系统内容的全面性分析
 ------------------------------
       本系统有三大部分，即学院信息、学生信息、管理员信息三部分，因此需要本系统很好的统一管理这些数据信息
 （3）可扩展性
 ------------------------------
        站点的数据承载量、功能模块单个或者整体调整都可以满足变化的需要，这种适应性称为可扩展性。
 （4）系统的灵活性
 ------------------------------
        要求有良好的人机界面，操作简单。
        
 ------功能需求分析--------
 ==============================
 （1）用户登录
 ------------------------------
        学生信息管理系统采用用户名密码的验证方式，进入学生信息管理系统前，用户必须输入用户名和密码，只有通过验证才能登陆进入信息系统
 （2）学生信息
  -----------------------------
        学生信息管理系统中应该包括四个方面，对学生信息的查询，对信息的删除，对信息的添加，对信息的修改。
  （3）学院信息
  -----------------------------
         学院信息应该包括以下几个方面，学院名称，学院编码，学院专业，专业代码
   （4）管理员信息
   ----------------------------
         管理员对用户信息的查询、修改、添加、删除以及处理等操作
         
  -----性能需求分析--------
  ================================
   （1）系统易操作性
  -----------------------------
        设计的系统应该尽量简单，使用户操作简单就能进入信息管理系统。
   （2）系统具有可维护性
   -----------------------------
      由于系统涉及的信息较多，数据库中的信息会随着时间进行修改，系统可利用的空间和性能就会随之下降，为了使系统能更好的保存学生的信息，系统应该具有可维护性，可以对某些模块能够进行维护。
   （3）系统具有开放性
  -----------------------------
     该系统可以在开放的硬件体系结构中运行，并且能够与其他系统顺利连接。
 
