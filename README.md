# skuDemo

> 项目描述
> 商品详情，规格选择路径处理
# skuDemo

> 项目描述
>
> 1. 背景及业务介绍：商品详情，规格选择路径处理
> 2. 业务覆盖范围&应用范围：适用于所有规格选择

## 项目npm命令

- `npm run dev` 项目开发启动Demo命令
- `npm run build` 项目工具打包命令


## 目录结构

```
.
├── lib                                   # 公用包文件
│   ├── sku.js                            # 包引用入口
├── public                                # 示例文件入口
│   ├── favicon.ico                       # htmlIcon
│   ├── index.html                        # html入口
├── src                                   # 项目Demo
│   ├── components                        # 公共文件目录
│   │   ├── index.js                      # sku计算代码
│   ├── App.js                            # demo核心代码
│   ├── App.css                           # demo样式文件
│   ├── index.js                          # demo入口
│   ├── index.css                         # 统一样式入口
│   ├── logo.svg                          # icon
├── postcss.config.js                    
├── package.json                      
└── README.md      
```