# spring-framework构建

## 使用码云

    强制同步github会把本文件删除

    开源项目太大，本地下载和clone都会失败

    github网速太慢，把github项目导入到码云
    
    使用码云 push 网速很快

## 使用idea clone spring-framework

    设置build tools
    使用maven旧版maven配置为本地，使用gradle就把gradle配置为本地

    本地安装好gradle
    https://blog.csdn.net/zzq900503/article/details/54695831
    
    在IDEA里gradle配置和使用.本地没有安装gradle,idea会自动下载
    https://blog.csdn.net/achenyuan/article/details/80682288
    idea 把gradle配置为本地，修改文件目录

    idea默认下载gradle到C盘 \.gradle文件夹
    gradle下载文件配置到maven仓库
    
    idea clone 项目后直接打开项目，直接build
    bulid先暂停，gradle配置国内镜像后再build
    
    第一次build特别慢，后来build就快了
