## maven不同环境打包
     mvn package                 会打包activeByDefault=true的环境
     mvn package -Pdev           开发环境打包
     mvn package -Ptest          测试环境打包
     mvn package -Pproduction    开发环境打包
    