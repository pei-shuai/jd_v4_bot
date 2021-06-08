#依次运行以下三条命令，安装jd_v4_bot带面板和更新jbot


1、如果无法拉到V4镜像，请使用阿里源进行拉取。

    wget -q https://raw.githubusercontent.com/pei-shuai/jd_v4_bot/main/jd-docker.sh -O jd-docker.sh && chmod +x jd-docker.sh && ./jd-docker.sh

   
2、进入容器，默认容器名jd_v4_bot，如果做了修改按照实际写。

    docker exec -it jd_v4_bot bash 
    
 
3、新装面板执行以下命令后，请访问5678端口进行配置，如果你做了映射，请使用实际映射的端口进行访问，默认用户名admin，密码adminadmin。
 
    wget -q https://raw.githubusercontent.com/pei-shuai/jd_v4_bot/main/v4mb.sh -O v4mb.sh && chmod +x v4mb.sh && ./v4mb.sh
    

3.1、更新或者重装装面板执行以下命令后，请使用旧密码进行访问面板。

    wget -q https://raw.githubusercontent.com/pei-shuai/jd_v4_bot/main/v4mb_up.sh -O v4mb_up.sh && chmod +x v4mb_up.sh && ./v4mb_up.sh
