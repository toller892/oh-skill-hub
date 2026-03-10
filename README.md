# oh-skill-hub

[English](#english) | [中文](#中文)

---

## English

### OpenClaw Skill Recommendation and Management System

An AI-powered intelligent skill discovery, evaluation, and installation assistant for OpenClaw.

#### Features

- 🔍 **Smart Skill Search**: Find the most suitable skills based on natural language descriptions
- ⭐ **Skill Rating System**: Comprehensive scoring based on usage frequency, user feedback, and compatibility
- 📊 **Usage Analytics**: Track skill usage and provide optimization suggestions
- 🔄 **Auto Update Check**: Monitor updates for installed skills
- 🛡️ **Security Audit**: Detect potential security risks in skills
- 💡 **Personalized Recommendations**: Suggest relevant skills based on user habits

#### Quick Start

1. **Clone this repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/oh-skill-hub.git
   cd oh-skill-hub
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure OpenClaw**
   Add this skill to your OpenClaw skills directory:
   ```bash
   ln -s $(pwd) ~/.openclaw/skills/oh-skill-hub
   ```

4. **Start using**
   ```
   Search for skills that can help me process images
   ```

#### Usage Examples

**Search for skills:**
```
Find skills for web scraping
```

**Install a skill:**
```
Install the image-processor skill
```

**List installed skills:**
```
Show all my installed skills
```

**Get recommendations:**
```
Recommend some skills based on my usage patterns
```

#### Configuration

Edit `config.json`:

```json
{
  "autoUpdate": true,
  "securityCheck": true,
  "recommendationEngine": "enabled",
  "dataCollection": "anonymous"
}
```

#### Security

- All skills undergo basic security scanning before installation
- Detects suspicious network requests, file operations, and system calls
- Users can review skill permission requirements
- Supports sandbox mode for running unverified skills

#### Requirements

- Node.js >= 18
- OpenClaw >= 1.0.0

#### License

MIT

---

## 中文

### OpenClaw 技能推荐和管理系统

基于 AI 的智能技能发现、评估和安装助手。

#### 功能特性

- 🔍 **智能技能搜索**：根据自然语言描述查找最合适的技能
- ⭐ **技能评分系统**：基于使用频率、用户反馈和兼容性的综合评分
- 📊 **使用分析**：追踪技能使用情况，提供优化建议
- 🔄 **自动更新检查**：监控已安装技能的更新
- 🛡️ **安全审计**：检测技能的潜在安全风险
- 💡 **个性化推荐**：根据用户使用习惯推荐相关技能

#### 快速开始

1. **克隆仓库**
   ```bash
   git clone https://github.com/YOUR_USERNAME/oh-skill-hub.git
   cd oh-skill-hub
   ```

2. **安装依赖**
   ```bash
   npm install
   ```

3. **配置 OpenClaw**
   将此技能添加到 OpenClaw 技能目录：
   ```bash
   ln -s $(pwd) ~/.openclaw/skills/oh-skill-hub
   ```

4. **开始使用**
   ```
   搜索能帮我处理图片的技能
   ```

#### 使用示例

**搜索技能：**
```
搜索能帮我爬取网页的技能
```

**安装技能：**
```
安装 image-processor 技能
```

**查看已安装技能：**
```
列出我安装的所有技能
```

**获取推荐：**
```
根据我的使用习惯推荐一些技能
```

#### 配置

编辑 `config.json`：

```json
{
  "autoUpdate": true,
  "securityCheck": true,
  "recommendationEngine": "enabled",
  "dataCollection": "anonymous"
}
```

#### 安全说明

- 所有技能在安装前会进行基础安全扫描
- 检测可疑的网络请求、文件操作和系统调用
- 用户可以查看技能的权限需求
- 支持沙箱模式运行未验证的技能

#### 依赖要求

- Node.js >= 18
- OpenClaw >= 1.0.0

#### 许可证

MIT
