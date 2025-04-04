# 金融计算器工具箱

## 项目介绍
金融计算器工具箱是一款功能全面且操作便捷的网页应用程序，旨在为金融专业人士和个人投资者提供一系列实用的金融计算工具。通过该工具箱，用户可以轻松完成各种复杂的金融计算任务，为投资决策和风险评估提供有力支持。

## 功能特性
1. **VaR（风险价值）计算器**：可计算投资组合在一定置信水平下可能遭受的最大损失，帮助投资者有效管理风险。
2. **期权定价器（BSM）**：基于经典的 BSM 模型，综合考虑标的资产价格、行权价格、到期时间、波动率和无风险利率等因素，为欧式期权准确定价。
3. **债券价格与收益率计算器**：根据债券的面值、票面利率、到期收益率和到期年限等信息，快速计算债券的价格和收益率，助力债券投资分析。
4. **久期/凸度计算器**：用于衡量债券价格对利率变动的敏感性以及久期对利率变动的敏感性，为债券投资提供深入的风险分析。
5. **折现现金流估值（DCF）计算器**：通过将未来各期现金流按照给定的折现率折现到当前，评估资产的内在价值，辅助投资决策。

## 使用方法
### VaR 计算器
- 输入投资金额、波动率和置信水平。
- 点击“计算”按钮，即可得到 VaR 值。

### 期权定价器
- 输入标的资产价格、行权价格、到期时间、波动率和无风险利率。
- 点击“计算”按钮，获取看涨期权和看跌期权的价格。

### 债券价格与收益率计算器
- 输入债券面值、票面利率、到期收益率和到期年限。
- 点击“计算”按钮，计算债券价格。

### 久期/凸度计算器
- 输入债券面值、票面利率、到期收益率和到期年限。
- 点击“计算”按钮，得出久期和凸度。

### 折现现金流估值（DCF）计算器
- 输入各期现金流（用英文逗号分隔）和折现率。
- 点击“计算”按钮，计算资产的 DCF 估值。

## 技术栈
- **HTML**：用于构建网页结构。
- **CSS（Tailwind CSS）**：借助 Tailwind CSS 框架实现美观且响应式的页面布局。
- **JavaScript**：实现各种金融计算功能和用户交互逻辑。
- **Font Awesome**：提供丰富的图标库，增强页面视觉效果。

## 贡献与反馈
如果你对本项目有任何改进建议、发现了 bug 或者想要贡献代码，请通过以下方式联系我们：
- 提交 issue 到项目的 GitHub 仓库。
- 发起 pull request 参与项目开发。
