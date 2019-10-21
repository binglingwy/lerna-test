## 发布步骤

1、commit
2、lerna version
3、lerna publish from-git

## 注意事项
1、git commit换成npm run c



## 踩坑记录

1、版本不能是0.0.X，要不然始终会统一全部升级
2、publish要忽略package.json文件，要不然也会全部统一升级


