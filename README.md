# select
使用vue仿写select组件

主要知识点是：vue父子组件间传值，样式绑定

数据格式是为了项目需要仿写的json格式数据，
      eg：{
            key: 'JS',
            value: '济南'
          }, {
            key: 'QD',
            value: '青岛'
          }
          
其中父组件负责获取和显示外部数据并传递给子组件，子组件负责处理数据并且向父组件传递数据，因此子组件可以重复应用于此格式数据的不同数据。

样式上没有很多美化，可以继续完善扩展。
