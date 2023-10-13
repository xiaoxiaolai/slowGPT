## 💡 tips

### 准备工作
1. [由于模型下载，自备梯子](https://www.iplcq.xyz/#/register?code=5EIUTBNU)
2. 修改/config/calsh/config.yaml的https://you_subscribe_url地址
3. docker run --rm -p 1080:1080 -v ./config/calsh:/root/.config/clash --network host ghcr.io/dreamacro/clash-premium -d

### 知识库启动
1. 确认docker-compose.yaml代理端口是否符合实际
2. docker compose up -d && docker compose logs -f