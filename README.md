# AIGobang

基于 **C++ 实现的 HTTP/HTTPS 服务器框架**，并在该框架上开发了一个 **五子棋 AI 对战 Web 应用**。  
项目主要用于实践 **C++ 网络编程、高性能服务器设计以及 Web 应用开发**。

---

## 项目特点

### C++ HTTP Server

实现了一个简易的 **C++ HTTP/HTTPS 服务器框架**，主要功能包括：

- 基于 **Reactor 模型** 的高并发服务器架构
- 支持 **HTTP / HTTPS（OpenSSL）**
- 动态 **路由管理**
- **Session 会话管理**
- **中间件机制**
- 连接池与缓存优化

服务器能够支持多线程并发请求处理，提高系统吞吐量。

---

### AI 五子棋 Web 应用

基于 HTTP Server 框架开发的在线五子棋应用，主要功能：

- 用户 **登录 / 注册**
- 游戏 **菜单系统**
- **AI 人机对战**
- 在线用户状态管理

前端通过 HTTP 请求与服务器交互，服务器负责游戏逻辑处理并返回结果。

---

## 项目结构
AIGobang
│

├── HttpServer # C++ HTTP服务器框架

├── WebApps # 五子棋 Web 应用

├── images # 项目截图

├── CMakeLists.txt

└── README.md


---

## 技术栈

- C++
- C++11
- Socket 网络编程
- Reactor Model
- HTTP / HTTPS
- OpenSSL
- CMake

---

## 构建运行

```bash
mkdir build
cd build
cmake ..
make
