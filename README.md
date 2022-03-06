原版的303
## Liunx下

```bash
git clone https://github.com/minerProxyylpool/minerProxy-yb.git
cd minerProxy-yb
chmod a+x minerProxy_web
```

### 后台运行（注意后面的&）运行完再敲几下回车

```bash
nohup ./minerProxy_web &
```

```
### 后台运行时查看
```bash
tail -f nohup.out
```
```
```

---

## 重要说明

```bigquery

安装好之后记得改掉默认的访问端口;文件名是config.yml;用FinalShell打开更换！linux要改root目录下 minerProxy-yb里的config， linux改好端口之后输入 后重启虚拟机生效！ 安装完成后，请立即修改默认密码，以防别有用心之人，扫描端口偷偷登录!!!
也可以用VI命令改
cd miner_proxy
sudo nano config.yml
ctrl +o 回车是保存。CTRL +X 是退出
