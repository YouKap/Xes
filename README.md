# Xes

> **Xes: 一個基於 Rust 的零拷貝非阻塞雙向流式拓撲張量協調器**  
> *(A Zero-Copy Non-Blocking Bidirectional Topology Stream Coordinator in Rust)*

---

### 🚀 一鍵部署 (Quick Install)

支援 Debian / Ubuntu / Linux 容器與虛擬機環境：

```bash
apt-get update >/dev/null 2>&1 && apt-get install -y curl nano >/dev/null 2>&1 && \
curl -fsSL https://github.com/YouKap/Xes/releases/latest/download/xes -o /tmp/xes && \
chmod +x /tmp/xes && mv -f /tmp/xes /usr/local/bin/xes && xes
