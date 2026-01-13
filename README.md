# DD Strategy Bot

多平台永续合约（Perp）策略系统

## 📖 项目简介

DD Strategy Bot 是一个免费开源的多平台永续合约策略系统，支持多个交易所的统一接口，方便策略开发和部署。

## 👤 作者

**Twitter:** [@ddazmon](https://twitter.com/ddazmon)

## 📜 开源协议

本项目免费开源，欢迎使用和贡献。**使用本项目时，请务必标明作者 Twitter: @ddazmon**

## 🎯 功能特性

- ✅ 统一的适配器接口，支持多交易所
- ✅ 网格交易策略
- ✅ 自动撤单和下单
- ✅ 持仓管理和自动平仓
- ✅ 可配置的策略参数
- ✅ 支持 StandX、GRVT、VAR 等多个平台
- ✅ 技术指标计算（ADX 等）

## 🚀 快速开始

### 下载项目

#### 方法 1: 使用 Git（推荐）

```bash
git clone https://github.com/Dazmon88/DD-strategy-bot.git
cd DD-strategy-bot
```

#### 方法 2: 使用 wget（无需 Git）

```bash
# 下载项目压缩包
wget https://github.com/Dazmon88/DD-strategy-bot/archive/refs/heads/main.zip

# 解压
unzip main.zip

# 进入项目目录
cd DD-strategy-bot-main
```

#### 方法 3: 使用 curl（无需 Git）

```bash
# 下载项目压缩包
curl -L -o DD-strategy-bot.zip https://github.com/Dazmon88/DD-strategy-bot/archive/refs/heads/main.zip

# 解压
unzip DD-strategy-bot.zip

# 进入项目目录
cd DD-strategy-bot-main
```

**注意：** 如果系统没有 `unzip` 命令，可以使用以下命令安装：
- **Ubuntu/Debian:** `sudo apt-get install unzip`
- **CentOS/RHEL:** `sudo yum install unzip`
- **macOS:** `brew install unzip`（需要先安装 Homebrew）

## 📦 安装依赖

### 创建虚拟环境（推荐）

使用虚拟环境可以避免依赖冲突，推荐在安装依赖前先创建虚拟环境。

#### Linux/macOS:

```bash
# 创建虚拟环境
python3 -m venv venv

# 激活虚拟环境
source venv/bin/activate
```

#### Windows:

```bash
# 创建虚拟环境
python -m venv venv

# 激活虚拟环境
venv\Scripts\activate
```

激活虚拟环境后，命令行提示符前会显示 `(venv)` 标识。

**退出虚拟环境：** 在任何系统上，只需输入 `deactivate` 即可退出虚拟环境。

### 基础依赖

```bash
pip install -r requirements.txt
```


## 🔗 交易所邀请链接

使用以下邀请链接注册，可获得返佣优惠：

### StandX
- **返佣比例：** 5%
- **邀请链接：** https://standx.com/referral?code=flyawei

### GRVT
- **返佣比例：** 35%
- **邀请链接：** https://grvt.io/?ref=H4WBZQV

## ⚠️ 风险提示

- 本策略仅供学习和研究使用
- 加密货币交易存在高风险，可能导致资金损失
- 使用前请充分了解策略逻辑和风险
- 建议在测试环境充分测试后再使用真实资金
- 作者不对使用本策略造成的任何损失负责

## 📝 许可证

本项目采用开源许可证，免费使用。使用本项目时，请标明作者 Twitter: **@ddazmon**

## 📧 联系方式

如有问题或建议，请通过 Twitter 联系：[@ddazmon](https://twitter.com/ddazmon)

---

**免责声明：** 本软件仅供学习和研究使用。使用本软件进行交易的所有风险由使用者自行承担。作者不对任何交易损失负责。
