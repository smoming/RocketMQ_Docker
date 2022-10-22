# RocketMQ_Docker

# 環境準備 - Create Folder
C:\\App\\docker\\rocketmq\\docker\\rocketmq\\data\\namesrv\\logs
C:\\App\\docker\\rocketmq\\docker\\rocketmq\\data\\namesrv\\store
C:\\App\\docker\\rocketmq\\docker\\rocketmq\\data\\broker\\logs
C:\\App\\docker\\rocketmq\\docker\\rocketmq\\data\\broker\\store
C:\\App\\docker\\rocketmq\\docker\\rocketmq\\etc\\broker

# broker.conf 放置指定位置
C:\\App\\docker\\rocketmq\\docker\\rocketmq\\etc\\broker\\broker.conf

# 執行 docker-compose yml 檔案
docker-compose -f docker-compose.yml up -d

# 至RocketMQ-Dashboard測試
http://localhost:8081