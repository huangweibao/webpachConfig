# webpackConfig
webpack-config.js配置文件
module.exports = {
    //配置入口文件的读入
    entry:"入口文件的路径",
    output:{//配置输入参数，输出最终被webpack处理并合并后的代码
      path:'输出路径',
      filename:'输出文件名'
    },
      module:{
          loader:{
              [
                text:/\.js$/,  //正则表达式 校验读入的文件格式
                loader:'jsx-loader
              ]
          }
      }
}
